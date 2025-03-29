**Tech Stack Used**
✅ Language: Java ☕
✅ Automation Tool: Selenium WebDriver 🌐
✅ Test Framework: TestNG 🧪
✅ Build Tool: Maven ⚙️
✅ Reporting: Extent Reports / Allure Reports 📊
✅ CI/CD: Jenkins (Optional) 🔄
**How to run the test**
Selenium-POM-DemoQA/
│── src/main/java/co.crm.qa.pages     # Page Classes
│    ├── ElemetPage.java
│    ├── HomePage.java
│    ├── LoginPage.java
│    ├── SearchPage.java
│
│── src/main/java/com.crm.qa.test    # Test Classes
│    ├── ElementTest.java
│    ├── HomeTest.java
│    ├── LoginTest.java
│    ├── SearchTest.java
│
│── src/main/java/com.crm.qa.base     # Utility Classes
│    ├── TestBase.java
│    
│
│── src/main/java/com.crm.qa.config   # Test Data & Configurations
│    ├── config.properties
│
│── pom.xml                              # Maven Dependencies
│── testng.xml                           # TestNG Test Suite
│── README.md                            # Project Documentation

**
How to Run the project**
 Clone the Repository
 git clone https://github.com/your-username/Selenium-POM-DemoQA.git
cd Selenium-POM-DemoQA

Configure Properties File
Edit config.properties file inside src/test/resources/ to set browser, URL, and credentials.

Run Tests with Maven
mvn test -Dsurefire.suiteXmlFiles=testng.xml

Run Specific Test via TestNG

mvn test -Dsurefire.suiteXmlFiles=testng.xml
** Maven Dependencies (POM.xml)**
<dependencies>
    <!-- Selenium WebDriver -->
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.10.0</version>
    </dependency>

    <!-- TestNG -->
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.4.0</version>
        <scope>test</scope>
    </dependency>

    <!-- WebDriver Manager -->
    <dependency>
        <groupId>io.github.bonigarcia</groupId>
        <artifactId>webdrivermanager</artifactId>
        <version>5.3.2</version>
    </dependency>
</dependencies>


**For any queries, feel free to connect with me on LinkedIn  https://www.linkedin.com/in/meena-kumari-754451197/ or reach out via email.**
