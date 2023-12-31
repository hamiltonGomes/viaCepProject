# Via CEP Project

## Features

- **CEP Lookup:** You can enter a CEP and obtain detailed information about the corresponding address.

- **Address Lookup:** You can search for addresses by state, city, and street name.

- **Listing Addresses:** The project enables you to list the addresses that have been queried and stored.

- **JSON Storage:** The results of the queries are stored in a JSON file for future reference.

## Future Features

- **Database Storage:** Instead of storing addresses in a JSON file, I'm planning to integrate a database, such as SQLite or MySQL, to provide more robust address management and search capabilities.

- **Geolocation:** I'm exploring the addition of geolocation features to display addresses on maps and calculate distances between addresses for a richer user experience.

## How to Use

1. Clone the repository to your local environment:
`git clone https://github.com/hamiltonGomes/viaCepJavaProject.git`
2. Compile the project:
`javac -d out -cp .:libs/gson-2.10.1.jar src/main/*.java`
3. Run the program:
`java -cp out:libs/gson-2.10.1.jar main.Main`
4. Follow the instructions in the console to perform ZIP code and address searches, list addresses, and store them in a JSON file.

## Requirements
- Java Development Kit (JDK) 8 or higher
- GSON library (libs/gson-2.10.1.jar)

## Author
[Hamilton Gomes](https://github.com/hamiltonGomes)
