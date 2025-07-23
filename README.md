# Petstore API Automation Project

Welcome to the **Petstore API Automation Project**!  
This repository contains automated tests for Swagger’s Petstore APIs using **RestAssured** with **Java**.

## Project Overview

The goal of this project is to provide robust automated test coverage for the public [Swagger Petstore API](https://petstore.swagger.io/), ensuring its endpoints function as expected.

## Tech Stack

- **Java**
- **RestAssured**
- **TestNG** (Choose your preferred test framework)
- **Maven** (for build and dependency management)

## Getting Started

### Prerequisites

- JDK 8 or above installed
- Maven (recommended) or Gradle
- Internet connection to access Swagger Petstore

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Deepakrao64/PetstoreAPITests.git
   cd PetstoreAPITests
   ```

2. **Install dependencies:**
   ```bash
   mvn clean install
   ```

### Running Tests

Use the following command to run all tests:
```bash
mvn test
```
## Project Structure

```
PetstoreAPITests/
├── src/
│   └── test/
│       └── java/
│           └── ... (test classes)
├── pom.xml / build.gradle
└── README.md
```

## Features

- Automated testing of key Petstore API endpoints:
  - Pet operations (add, update, find, delete)
  - Store operations (orders, inventory)
  - User operations (create, login, logout)
- Test data management
- Easy extensibility for new endpoints or scenarios

## Contributing

Feel free to fork the repository and submit pull requests. Suggestions and improvements are welcome!

## Author

**Deepak Jadhav**
