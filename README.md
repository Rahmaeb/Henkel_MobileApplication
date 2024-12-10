# Manual Testing - Henkel App Features

## Project Overview
This repository contains manual testing documentation for key features of the Henkel Mobile Application. The testing focuses on the following core functionalities:

1. **Mobile Number Authentication for Login**
2. **User Registration & Login**

The goal is to validate the user authentication process, ensure registration fields are working correctly, and identify any bugs or issues in the features.

## Objectives
- **Mobile Number Authentication**: Verify that the app correctly handles mobile number authentication, including country code selection, OTP generation, and the validation of Terms & Conditions.
- **User Registration & Login**: Ensure the registration process works smoothly with the correct handling of mandatory fields, country-specific data, and referral code functionality.
- **Document any bugs or issues found during testing.**
- **Provide clear test cases and expected outcomes for each feature.**

## Key Features of the Interface

### 1. Mobile Number Authentication for Login
- **Country Code Selection**: The app allows the user to select the country code from a dropdown.
- **OTP Authentication**: The app sends a one-time password (OTP) via SMS to the mobile number for verification.
- **Terms & Conditions**: The user must accept the terms and conditions to proceed to registration.
- **Resend OTP**: Users can resend the OTP if not received or expired.
- **Expected Result**: The mobile number is authenticated, and the user is redirected to accept Terms & Conditions.

### 2. User Registration & Login
- **Registration Fields**:
  - **First Name**, **Last Name**, **Gender**, **Birthdate**: Mandatory fields for user registration.
  - **Email**: Optional but unique, required for profile editing.
  - **Referral Code**: Optional, used for rewarding users for referring others to the app.
- **Mobile Number**: Pre-filled after authentication.
- **Expected Result**: User completes registration, receives an SMS for confirmation, and is redirected to the Home screen after successful registration.

## Repository Contents
- TC for Mobile Number Authentication.xlsx: Contains detailed manual test cases for validating the mobile authentication.
- TestCases & bug report for User Registration & Login.xlsx: Contains detailed manual test cases for validating user registration features and bugs discovered during the testing phase.
- README.md: Overview and objectives for testing.
- Henkel user story.pdf: Detailed documentation of the user stories and feature descriptions for reference.


