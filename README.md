#TBC UI Automation Project Overview This project contains automated UI tests for the TBC Bank website, covering critical user journeys for both desktop and mobile users. The tests are implemented using Java, Selenide, and TestNG, with a Gradle build for dependency management and parallel execution. Target URL: https://www.tbcbank.ge

Tech Stack Java 11/17 Selenide 7.2.0 TestNG 7.9.0 Gradle Chrome WebDriver

Automated Scenarios Locations – ATM & Branches View locations on the map Filter by ATM or Branch Loan Calculator Enter loan amount Click calculate Verify monthly payment result Deposit Page – My Goal Deposit Access deposit product page Verify content and CTA buttons Mobile UI Verify homepage usability in mobile viewport Base Smoke Tests Verify critical pages load successfully

Mobile ≠ Desktop Certain elements behave differently on mobile (responsive menu, layout, font size) Separate assertions verify mobile-specific visibility and usability

Notes Tests are UI smoke tests covering business-critical pages Designed for maintainability and scalability Can be extended with additional scenarios as needed
