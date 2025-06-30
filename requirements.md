# Test Automation Framework for Elevate Application

## 1. Overview
This test automation framework is designed to provide a robust, scalable and feature-rich solution for automated testing of Content Management System Elevate. The framework encompasses various features , including hybrid framework, logging, retry mechanism, self healing, cross-browser testing, multiple environments, password encryption, code quality, reusable utilities, data generation etc.

## 2. Page Object Model(POM)
Page Object Model (POM) is a design pattern used in test automation frameworks to enhance code readability, maintainability, and reusability. In this approach, each web page or significant component of the application under test is represented by a separate class, often called a Page Object.

Each Page Object class contains:
a. Locators (as class members) to identify UI elements on the page.
b. Methods (as class functions) that encapsulate interactions or behaviors that can be performed on those elements (e.g., clicking a button, entering text, retrieving values).
c. Assertions (optionally) can also be defined in the test classes or within page methods, based on the structure and guidelines being followed.

Advantages of POM Implementation:
a. Separation of concerns – Test logic is separated from UI structure.
b. Code reusability – Common actions can be reused across tests.
c. Easy maintenance – UI changes require updates only in one place.
d. Improved readability – Clear representation of page functionality.


