# Signorchoicetestreport
SignorChoice is an e-commerce platform specializing in perfumes. The objective of testing the site is to ensure that it provides a seamless user experience and meets quality standards.
Test Conducted By: Md.Kamrul Hasan Dipta
Test Date: 08-05-25 and 09-05-25
Test Environment: Desktop(Windows Operating System 10, 11, Browser: Chrome, Firefox, Mobile: Android and iOS)

**Objectives/Test Objectives**

Validate and check every functionality of the website from the login page, product search functionality, navigation, product cart, checkout, product category, and payment system to user authentication.
Check website performance, load, and stress(under extreme conditions like event sales and black Friday), response time(under normal and peak loads), and responsiveness.
Security vulnerability checking like secure authentication, finding security loopholes performing penetration tests, and Secure API communication using Postman.
UX/UI consistency verification across different devices
Usability test to identify broken links or errors

**Test Scopes**

**Functional Testing:** User login, password change, reset, forget the password, product search, category-wise product search, add-to-cart, increase and decrease item, product differentiation depending on fragrance and size, check-out, and payment processing.

**Usability Testing:** Navigation, user-friendliness, visual consistency

**Performance Testing:** Load time, server response, API response, Stress Handling

**Security Testing:** SSL certification validation, input validation, payment gateway and its validation, data encryption, Secure API communication

**Compatibility Testing:** Cross-browser, different environment, and device responsiveness 



**Test Cases**

**Functional Testing(User Role: Customer)**


![g1](https://github.com/user-attachments/assets/1653d06e-d66c-4742-877b-cc1499f9c784)


**Usability Testing**

![g2](https://github.com/user-attachments/assets/d656873b-0e84-4600-b18c-f9441a4274b1)


**Performance and Load Testing(Jmeter)**

Environment Setup
Tool: Apache JMeter 5.6.3, Grafana, K6
Concurrency Levels Tested: 10, 50, 100 users and peak load = 500 users

**Tested Endpoints: **
Homepage
Product Listing
Login
Checkout

**Test Results**


![g3](https://github.com/user-attachments/assets/d352ed21-00c2-48b7-94b3-b93be47dde46)


