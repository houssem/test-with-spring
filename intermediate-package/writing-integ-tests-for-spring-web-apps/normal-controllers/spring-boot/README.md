# Writing Integration Tests for Spring Web Applications - Normal Controllers

## Running the Web Application

You can run the web application by using Maven or Gradle.

### Running the Web Application With Maven

You can run the web application by using the following command:

	mvn clean spring-boot:run -P dev
	
### Running the Web Application With Gradle

You can run the web application by using the following command:

	gradle clean bootRun

## Running Unit Tests

You can run unit tests by using either Maven or Gradle.

### Running Unit Tests With Maven

You can run unit tests by using the following command:

    mvn clean test -P dev

### Running Unit Tests With Gradle

You can run unit tests by using the following command:

	gradle clean test
	
## Running Integration Tests

You can run integration tests by using either Maven or Gradle.

### Running Integration Tests With Maven

    mvn clean verify -P integration-test

### Running Integration Tests With Gradle

You can run integration tests by using the following command:

	gradle clean integrationTest
	
## Running End-to-End Tests

### Prerequisites

You have to configure your local development enviroment by following these steps:

1. [Download ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)
2. Unpackage the downloaded archive.
3. Ensure that the archive is found from the path. 

If you need more details about this setup, take a look at the following resources:

* [ChromeDriver Documentation - Getting Started](https://sites.google.com/a/chromium.org/chromedriver/getting-started)

### Running End-to-End Tests With Maven

    mvn clean verify -P end-to-end-test

### Running End-to-End Tests With Gradle

You can run end-to-end tests by using the following command:

	gradle clean endToEndTest	
