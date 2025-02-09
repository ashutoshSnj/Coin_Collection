Managing Coin Collection

Overview

This application is designed to efficiently manage a coin collection. The project leverages Hibernate, Stream API, and Collection Framework within a Maven setup to provide seamless data management and processing.

Features

1. Addition of Coins

Users can add a new coin to the collection by providing the following details:

Country

Denomination

Year of Minting

Current Value

Acquired Date

2. Search and Filtering

Users can search and filter coins in the collection based on the following criteria:

List Creation:

All coins from a particular Country

Coins based on Year of Minting

Coins sorted by Current Value

Specific Coin Search:

By Country + Denomination

By Country + Year of Minting

By Country + Denomination + Year of Minting

By Acquired Date + Country

3. Persistence

On application startup, the existing coin collection is loaded from the database into a collection in the application.

Users have the option to save the current state of the collection back to the database.

CRUD operations are performed using Hibernate.

Technologies Used

Java

Maven

Hibernate (for database interaction and persistence)

Stream API (for efficient data processing and filtering)

Collection Framework (for managing and storing coin data efficiently)

MySQL (as the database)

Setup Instructions

Clone the repository:

git clone <https://github.com/ashutoshSnj/Coin_Collection.git>

Navigate to the project directory:

cd coin-collection-management

Build the project using Maven:

mvn clean install

Configure database settings in hibernate.cfg.xml.

Run the application:
java -jar target/coin-collection.jar
