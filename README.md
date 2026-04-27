DemoBlaze/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── base/
│   │       │   └── BasePage.java
│   │       │
│   │       ├── pages/
│   │       │   ├── AuthPage.java
│   │       │   ├── CartPage.java
│   │       │   ├── HomePage.java
│   │       │   ├── OrderPage.java
│   │       │   └── ProductPage.java
│   │       │
│   │       └── utils/
│   │           ├── ConfigReader.java
│   │           ├── ExcelUtil.java
│   │           ├── ExtentManager.java
│   │           └── ScreenshotUtil.java
│
│   ├── test/
│   │   ├── java/
│   │   │   ├── base/
│   │   │   │   └── BaseTest.java
│   │   │   │
│   │   │   ├── listeners/
│   │   │   │   ├── RetryListener.java
│   │   │   │   └── TestListener.java
│   │   │   │
│   │   │   ├── tests/
│   │   │   │   ├── AuthTest.java
│   │   │   │   ├── CartTest.java
│   │   │   │   ├── FormValidationTest.java
│   │   │   │   ├── OrderTest.java
│   │   │   │   └── ProductTest.java
│   │   │   │
│   │   │   └── utils/
│   │   │       └── RetryAnalyzer.java
│   │   │
│   │   └── resources/
│   │       └── config.properties
│
├── reports/
│   └── ExtentReport.html
│
├── screenshots/
│   └── (failure screenshots)
│
├── testng.xml
├── pom.xml
└── README.md
