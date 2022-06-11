## Senior QA Automation (Web) Technical Assessment

Company: [MataQuotes](https://www.metaquotes.net)

Products: [MetaTrader 5](https://www.metaquotes.net/en/metatrader5), [TeamWox](https://www.metaquotes.net/en/teamwox)

### Stack and Tools

<a href="https://java.com" title="Java">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/Java.svg" alt="Java" height="35"/>
</a>

<a href="https://junit.org/junit5" title="JUnit 5">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/JUnit5.svg" alt="JUnit 5" height="35"/>
</a>

<a href="https://selenide.org" title="Selenide">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/Selenide.svg" alt="Selenide" height="35"/>
</a>

<a href="https://logging.apache.org/log4j" title="Log4j">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/Log4j.png" alt="Log4j" height="35"/>
</a>

<a href="https://gradle.org" title="Gradle">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/Gradle.svg" alt="Gradle" height="35"/>
</a>

<a href="https://cucumber.io" title="Cucumber">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/Cucumber.svg" alt="Cucumber" height="35"/>
</a>

<a href="https://qameta.io/allure-report" title="Allure Report">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/AllureReport.svg" alt="Allure Report" height="35"/>
</a>

<a href="https://www.jetbrains.com/idea" title="JetBrains IntelliJ IDEA">
   <img src="https://raw.githubusercontent.com/aikfiend/aikfiend.github.io/master/icons/IntelliJIDEA.svg" alt="JetBrains IntelliJ IDEA" height="35"/>
</a>

### Coding Task

Create an automated e2e test for the economic calendar. The test should have the following steps:

1. Open https://www.mql5.com/en/economic-calendar

2. Filter calendar events using following parameters:

   |Period|Importance|Currency|
   |------|----------|--------|
   |Current month|Medium|CHF - Swiss frank|

3. Open the first event with the CHF currency in the list filtered

4. Verify that importance and country of the event displayed matches the filter applied

5. Log the event history for last 12 months using the following format:
   ```
   | Date             | Actual | Forecast | Previous |
   | 31 May 2019      | -0.7&  | 0.3%     | 0.0%     |
   ```

Requirements:

- Java 8

- Any Selenium wrapper can be used

- Any logging framework can be used 

- Google Chrome browser using Googlebot user agent

- (Optional) Any BDD framework can be used

- (Optional) HTML Report