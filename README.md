# 🛒 DemoWebShop Hackathon – Manual + Automation Testing Project

This repository contains my **Hackathon Project** for the  
[Demo Web Shop](https://demowebshop.tricentis.com/) e-commerce application.  
It includes **complete Manual Testing documentation** and a fully implemented **End-to-End Automation Framework** using **Selenium, Java, TestNG, and Page Object Model (POM)**.

This project demonstrates real-world QA skills with both **manual validation** and **scalable automation scripting**, designed for industry-level test coverage.

---

## 🚀 Project Overview

### 🔍 Manual Testing  
- Complete functional testing of Demo Web Shop  
- Test Plan, Test Scenarios, and Detailed Test Cases  
- Bug Reporting with severity & priority  
- Mind Map for test coverage  
- Test Summary Report after execution  

### 🤖 Automation Testing  
- Built using **Selenium WebDriver + Java + TestNG**  
- Framework designed with **Page Object Model (POM)**  
- Full **End-to-End automation** of core e-commerce flows  
- Includes validations, assertions, reusable utilities, and test data handling  

---

## 🧩 Key Features

### 📝 Manual Testing
- ✔ Detailed and well-structured QA documentation  
- ✔ Realistic scenarios based on e-commerce behaviors  
- ✔ Complete defect tracing with expected vs actual results  
- ✔ Test execution summary with final status  

### ⚙️ Automation Testing
- ✔ Modular **POM** design for scalability  
- ✔ Separate page classes, reusable methods & locators  
- ✔ TestNG annotations (BeforeClass, BeforeMethod, AfterMethod)  
- ✔ End-to-End flows: Login → Add to Cart → Checkout → Order Processing  
- ✔ Cross-browser ready structure  
- ✔ Screenshot capture for failures (optional)  

---

## 📁 Project Folder Structure

```
DemoWebShop_Hackathon/
│
├── Manual_Testing/
│ ├── TestPlan.docx
│ ├── TestScenarios_TestCases.xlsx
│ ├── BugReport.xlsx
│ ├── MindMap.png
│ └── TestSummaryReport.docx
│
├── Automation/
│ ├── src/
│ │ ├── main/java/
│ │ │ └── pages/
│ │ │ ├── LoginPage.java
│ │ │ ├── HomePage.java
│ │ │ ├── ProductPage.java
│ │ │ ├── CartPage.java
│ │ │ └── CheckoutPage.java
│ │ │
│ │ ├── test/java/
│ │ ├── LoginTest.java
│ │ ├── AddToCartTest.java
│ │ ├── CheckoutTest.java
│ │ └── EndToEndTest.java
│ │
│ ├── testng.xml
│ ├── pom.xml
│ └── README.md
│
└── README.md
```

---

## 🧪 Automated Test Coverage

This automation suite covers all major Demo Web Shop workflows:

- 🔐 Login  
- 📄 Product Browsing  
- ➕ Add to Cart  
- 🛒 Shopping Cart Validations  
- 💳 Checkout & Billing  
- ✔ Order Confirmation  
- 🚪 Logout  

Each flow is completely automated using a **TestNG-based modular structure**.

---

## ▶️ How to Run Automation Tests

### 1️⃣ Clone the repository  
```bash
git clone <https://github.com/Shivshanker869/Hackathon-project>
