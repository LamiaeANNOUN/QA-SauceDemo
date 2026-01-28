# QA-SauceDemo

## Project Overview

This project demonstrates **manual testing** of the SauceDemo e-commerce website. The focus is on validating the **core functional flows** of the application, including product browsing, cart management, and checkout, ensuring that the site behaves as expected and that input validation is correctly implemented.

## Application Under Test

* **Website:** SauceDemo
* **Modules Tested:**

  * Home / Products page
  * Cart page
  * Checkout – Your Information page
* **Features Tested:**

  * Navigation across pages
  * Adding/removing products to/from cart
  * Form fields (First Name, Last Name, Zip Code)
  * Buttons (Add to Cart, Remove, Continue, Cancel)
  * Error message display and input validation

## What Was Tested

* Product selection and adding to cart
* Cart functionality (viewing, updating quantities, removing items)
* Checkout flow with valid and invalid inputs
* Navigation buttons and links
* Error messages for invalid or missing input

## Test Artifacts

* **Test Cases:** Excel sheet with executed test cases and actual results
* **Bug Reports:** Excel sheet documenting three key defects:

  * BUG-01: First Name field accepts numeric characters (TC-06)
  * BUG-02: Last Name field accepts numeric characters (TC-07)
  * BUG-03: Zip Code field accepts alphabetic characters (TC-08)

## Test Execution Summary

* Manual testing covered all core user flows
* All major flows work as expected except for the input validation defects listed above
* Navigation and cart management are fully functional

## Key Observations

* Missing input validation in checkout fields allows invalid data
* Application UI is consistent and stable
* Cancel and Continue buttons function correctly

## Next Steps

* Automate failed and high-value test cases using **Selenium WebDriver with Java**
* Integrate automated tests with TestNG for regression testing

