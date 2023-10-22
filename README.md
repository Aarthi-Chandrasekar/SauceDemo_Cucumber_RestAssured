Web and API Automation Framework with Selenium and RestAssured

**About:**

A hybrid testing framework developed in Java, integrating Selenium WebDriver for web UI automation, RestAssured for API verifications, and leveraging the Cucumber framework for BDD style testing.

**Core Components:**

1. Language: Java.

2. Web Automation: Selenium WebDriver

3. API Testing: RestAssured

4. Behavior-Driven Approach: Cucumber BDD

5. Build Tool: Maven

**Features:**

1. Focused on both web and API test automation.

2. Adopts a BDD style approach, enhancing test readability and maintainability.

3. Follows the page object design pattern for organized code.

4. Bundled with sample tests for both web UI and API scenarios.

5. Implemented data-driven automated testing by utilizing JSON files with the Jackson-databind library.

6. Supports multiple browsers.

7. Integrated with Allure for better test reports.


**Setup Instructions:**

**Prerequisites:**

1. Install Java 8

2. Setup Maven

3. Allure Setup: Follow instructions from Allure's official site (https://docs.qameta.io/allure/)

4. IDE configuration: Launch Eclipse Navigate to the Eclipse Marketplace and install the Cucumber Eclipse Plugin

**Executing Tests:**

Go to TestRunner.java, right-click, then choose 'Run as -> JUnit Test' or run "mvn clean install" in terminal.

To view report run the following command: allure serve allure-results