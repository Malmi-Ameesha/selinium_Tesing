# README for Selenium Test Suite

### Prerequisites

Java Development Kit (JDK): Make sure Java is installed and the JAVA_HOME environment variable is set.
Apache Maven: Maven is used to manage dependencies and run the tests.
Selenium WebDriver: WebDriver should be included as a dependency in the Maven pom.xml file.
Google Chrome or Firefox: The browser where tests will be executed. Ensure the respective WebDriver binaries (ChromeDriver or GeckoDriver) are installed and set in the PATH.

### Instructions for Running the Tests

Clone the Repository: Clone the repository containing the test scripts to your local machine.
Set Up Dependencies: Use Maven or Gradle to set up the required dependencies
For Maven, ensure the pom.xml file includes Selenium dependencies.

```sh
   <dependencies>
   <dependency>
   <groupId>org.seleniumhq.selenium</groupId>
   <artifactId>selenium-java</artifactId>
   <version>4.1.0</version>
   </dependency>
   <dependency>
   <groupId>org.testng</groupId>
   <artifactId>testng</artifactId>
   <version>7.4.0</version>
   <scope>test</scope>
   </dependency>
   </dependencies>
```

For Gradle, ensure the build.gradle file includes Selenium dependencies.
Configure WebDriver: Ensure the appropriate WebDriver executable is available (ChromeDriver for Chrome, GeckoDriver for Firefox).
Run Tests: Execute the test suite using your IDE or through the command line.

### Test Scripts

The test scripts are located in the src/test/java directory.
Each script corresponds to a specific test case or suite of test cases.

### Test Results

The test results will be displayed in the console output and can be reviewed in detail.

