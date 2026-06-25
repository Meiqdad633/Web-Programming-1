# HTML Contact Form

## Source Code Overview

### Form Purpose

This contact form is designed to collect user information, including:

-   Name
-   Email Address
-   Phone Number
-   Message
-   Preferred Contact Method
-   Inquiry Type

The project demonstrates the use of **HTML forms**, **GET and POST
methods**, and **client-side validation**.

------------------------------------------------------------------------

## Name Field

The **Name** input field allows users to enter their full name.

-   Uses the `required` attribute.
-   Prevents form submission if left empty.

------------------------------------------------------------------------

## Email Field

The **Email** input field collects the user's email address.

-   Uses the `email` input type.
-   Ensures the entered email follows a valid format.

------------------------------------------------------------------------

## Phone Number Field

The **Phone Number** field collects the user's contact number.

-   Uses JavaScript validation with a regular expression.
-   Accepts **exactly 10 numeric digits**.

------------------------------------------------------------------------

## Message Field

The **Message** textarea allows users to enter detailed information
about their inquiry.

-   Uses the `required` attribute.
-   Prevents empty submissions.

------------------------------------------------------------------------

## Preferred Contact Method

Radio buttons allow the user to choose one preferred contact option:

-   Email
-   Phone
-   Both

Radio buttons ensure that **only one option** can be selected.

------------------------------------------------------------------------

## Inquiry Type Dropdown Menu

A dropdown menu is provided to categorize the user's inquiry.

Available options include:

-   General Inquiry
-   Support Request
-   Feedback

Using a dropdown menu improves usability and keeps user input
consistent.

------------------------------------------------------------------------

## Preview Feature (GET Method)

The preview feature displays the entered information on the same page
before final submission.

This allows users to:

-   Review their information
-   Verify accuracy
-   Make corrections if necessary

------------------------------------------------------------------------

## Client-Side Validation

JavaScript validation checks the following conditions before submission:

1.  All required fields are completed.
2.  The email address is in a valid format.
3.  The phone number contains exactly **10 digits**.

If any validation rule fails, an appropriate error message is displayed.

------------------------------------------------------------------------

## Local Storage

The browser's **Local Storage** feature is used to save form data
locally on the user's device.

This demonstrates simple client-side data persistence without requiring
a server or database.

------------------------------------------------------------------------

## POST Method

The form uses the **POST** method for final submission.

POST is commonly used because it:

-   Sends data securely in the request body.
-   Does not expose user information in the URL.
-   Is suitable for submitting form data.

------------------------------------------------------------------------

## Features

-   HTML Contact Form
-   GET Preview Feature
-   POST Submission
-   Client-Side Validation
-   Email Format Validation
-   10-Digit Phone Validation
-   Local Storage Support
-   User-Friendly Interface

------------------------------------------------------------------------

## Technologies Used

-   HTML5
-   CSS3
-   JavaScript
-   Local Storage API
-   GET Method
-   POST Method
