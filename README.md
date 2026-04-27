 Project Structure

- src/main/java
  - base        → Base classes
  - pages       → Page Object classes
  - utils       → Utilities (config, report, screenshot)

- src/test/java
  - base        → Test setup (BaseTest)
  - tests       → Test cases
  - listeners   → TestNG listeners
  - utils       → Retry logic

- src/test/resources
  - config.properties

- reports/       → Extent Reports
- screenshots/   → Failure screenshots

- testng.xml     → Test execution file
- pom.xml        → Maven dependencies
