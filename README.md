# Signorchoicetestreport
SignorChoice is an e-commerce platform specializing in perfumes. The objective of testing the site is to ensure that it provides a seamless user experience and meets quality standards.
Test Conducted By: Md.Kamrul Hasan Dipta
Test Date: 08-05-25 and 09-05-25
Test Environment: Desktop(Windows Operating System 10, 11, Browser: Chrome, Firefox, Mobile: Android and iOS)

2. Objectives/Test Objectives

Validate and check every functionality of the website from the login page, product search functionality, navigation, product cart, checkout, product category, and payment system to user authentication.
Check website performance, load, and stress(under extreme conditions like event sales and black Friday), response time(under normal and peak loads), and responsiveness.
Security vulnerability checking like secure authentication, finding security loopholes performing penetration tests, and Secure API communication using Postman.
UX/UI consistency verification across different devices
Usability test to identify broken links or errors


3. Test Scopes

Functional Testing: User login, password change, reset, forget the password, product search, category-wise product search, add-to-cart, increase and decrease item, product differentiation depending on fragrance and size, check-out, and payment processing.

Usability Testing: Navigation, user-friendliness, visual consistency

Performance Testing: Load time, server response, API response, Stress Handling

Security Testing: SSL certification validation, input validation, payment gateway and its validation, data encryption, Secure API communication

Compatibility Testing: Cross-browser, different environment, and device responsiveness

4. Test Cases

4.1 Functional Testing(User Role: Customer)

Test Case ID
Test Scenario
Issues
Severity 
Priority
Recommendation
SCTC001
User/Account Registration and Login
The registration form lacks client-side validation for email format and password strength
No confirmation email is sent upon registration
Medium and Low
High and Medium
Implement real-time validation to guide during input
Integrate email verification to confirm user authenticity
SCTC002
Product Search and Navigation
The search functionality doesn’t handle partial matches effectively
Medium
High
Enhance the search algorithm to support fuzzy matching
SCTC003
Product Viewing
Product images lack zoom functionality, limiting detailed viewing
Low
Medium
Implement image zoom features for better product inspection
SCTC004
Cart Management
The cart doesn’t update items dynamically and requires adding to the cart by clicking			  
Medium
High
Use AJAX to update cart contents
SCTC005
Checkout Process 
Lack of multiple payment options, only one method available
Cash on Cash-on-delivery option is not available
Medium
High
Integrate additional payment gateways
Add cash on delivery option
SCTC006
General Link and UI Behavior
Several footer links are non-functional or redirect to the homepage
Low
Medium
Audit and correct all broken or misdirected links.				
SCT007
Order Confirmation
Users didn’t have any order confirmation email	
High
Medium
Confirm the order with the confirmation Email. Add the email confirmation functionality


