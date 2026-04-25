# 🚀 E-Commerce Test Automation & QA Workflow (nopCommerce)

## 📌 Overview
This repository showcases a comprehensive automation testing workflow performed on an e-commerce application (nopCommerce). It includes end-to-end activities such as test planning, test case design, defect reporting, automation testing, CI/CD integration, and reporting.

The project demonstrates a structured QA approach combining manual testing practices with automation frameworks using Selenium, TestNG, and Cucumber (BDD).

---

## 🛠️ Tech Stack
- Language: Java  
- Automation Tool: Selenium WebDriver  
- Frameworks: TestNG, Cucumber (BDD)  
- Database: MySQL (via JDBC)  
- CI/CD: Jenkins  
- Bug Tracking & Test Management: JIRA  

---

## 📂 Repository Structure
Day1_Test_Plan/              → Test planning documents  
Day2_Test_Cases/             → Designed test cases  
Day3_Defect_Report/          → Defect tracking and reporting  
Jenkins/                     → CI/CD setup files  
Nopcommerce/                 → Automation scripts and framework  
Reports/                     → Execution reports  
nopCommerce_Presentation/    → Project documentation  
README.md                    → Project overview  

---

## ⚙️ Key Features
- End-to-end QA lifecycle implementation (STLC)  
- Automation framework using Selenium + TestNG + Cucumber (BDD)  
- CI/CD integration with Jenkins  
- Structured defect tracking and reporting  
- Validation of core e-commerce workflows  

---

## 🧪 Automated Test Coverage

The following test scenarios are automated using step definitions and reusable page objects:

- User Registration (Step_Register.java)  
- User Login (Step_Login.java)  
- Search Functionality (Step_Search.java)  
- Add to Cart (Step_AddToCart.java)  
- Delete from Cart (Step_DeleteFromCart.java)  
- Add to Wishlist (Step_AddToWishlist.java)  
- Add Address (Step_AddAddress.java)  
- Change Currency (Step_ChangeCurrency.java)  
- Logout & Change Password (Step_Logout_ChangePassword.java)  
- Social Media Validation (Step_SocialMedia.java)  

### Framework Components
- Page Object Model: PageClass.java  
- Test Runner: TestRunner.java  

---

## ▶️ How to Run

1. Clone the repository  
git clone https://github.com/your-username/your-repo-name.git

2. Navigate to automation folder  
cd Nopcommerce

3. Run tests  
mvn test

(Ensure Java, Maven, and required dependencies are installed)

---

## 📊 Outcome
- Improved test coverage and execution efficiency  
- Reduced manual testing effort through automation  
- Strengthened understanding of end-to-end QA workflows  

---

## 🧠 Learning Highlights
- Hands-on experience with BDD and automation frameworks  
- Practical exposure to CI/CD pipelines using Jenkins  
- Developed understanding of system workflows and data validation  
- Built reusable and scalable test automation architecture  

---

## 🚀 Future Enhancements
- Parallel test execution  
- Advanced reporting (Allure/Extent Reports)  
- Docker-based execution  
- Performance and API testing integration  
