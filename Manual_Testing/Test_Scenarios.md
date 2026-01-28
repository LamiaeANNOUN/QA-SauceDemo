# SauceDemo QA Project – Test Scenarios

## Project Overview
This document lists high-level test scenarios for the SauceDemo e-commerce web application.  
These scenarios cover the main user flows of login, product browsing, cart, checkout, and logout.  
The scenarios include positive, negative, and edge cases to ensure functional correctness and usability.

---

## Test Scenario List

### TS-01: Verify navigation to checkout page
Ensure that the user can successfully navigate from the cart page to the checkout information page.

### TS-02: Verify checkout page UI elements
Ensure that all required UI elements (input fields, buttons, labels) are displayed correctly on the checkout page.

### TS-03: Verify successful checkout information submission
Ensure that the user can proceed to the next step when all required checkout information is provided correctly.

### TS-04: Verify cancel checkout process
Ensure that clicking the **Cancel** button returns the user to the cart page without saving entered data.

### TS-05: Verify behavior when mandatory fields are empty
Ensure the system displays appropriate error messages when required fields are left empty.

### TS-06: Verify input validation for First Name field
Ensure the system handles valid and invalid inputs in the First Name field correctly.

### TS-07: Verify input validation for Last Name field
Ensure the system handles valid and invalid inputs in the Last Name field correctly.

### TS-08: Verify input validation for Zip/Postal Code field
Ensure the system handles valid and invalid inputs in the Zip/Postal Code field correctly.

### TS-09: Verify error message display
Ensure that appropriate error messages are displayed for invalid or missing input during checkout.

### TS-10: Verify data persistence after cancellation
Ensure that entered checkout information is **not retained** after clicking the Cancel button.

### TS-11: Verify navigation behavior using browser controls
Ensure the system handles navigation using browser back and forward buttons correctly during checkout.

### TS-12: Verify checkout page accessibility
Ensure that the checkout page is accessible and loads without errors.

### TS-13: Verify cart functionality
Ensure that adding and removing products in the cart updates the cart count and product list correctly.

### TS-14: Verify product listing and sorting
Ensure that the product list is displayed correctly and can be sorted by name or price.

### TS-15: Verify logout behavior
Ensure that the user can logout successfully from any page and is redirected to the login page.

---

## Notes
- Each scenario will be converted into one or more detailed test cases.  
- Scenarios cover both **positive** (valid data / expected behavior) and **negative** (invalid data / edge cases) testing.  
- Scenarios are designed for **manual execution** as well as **automation scripts**.

