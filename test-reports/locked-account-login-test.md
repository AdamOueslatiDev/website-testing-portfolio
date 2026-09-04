# Locked Account Login Test

## Website
SauceDemo

## Feature Tested
Login behavior for a locked user account

## Test Account
Username: locked_out_user

## Test Steps

1. Opened the SauceDemo login page.
2. Entered the username "locked_out_user".
3. Entered the correct password.
4. Clicked the "Login" button.
5. Checked the error message.
6. Verified that access to the products page was blocked.
7. Closed the error message using the X button.
8. Tried logging in again.
9. Verified that the error message appeared again.

## Expected Result

- The locked user should not be able to access the products page.
- A clear error message should explain that the account is locked.
- The error message should be closable.
- The user should remain unable to log in while the account is locked.

## Actual Result

The website correctly displayed the message:

"Epic sadface: Sorry, this user has been locked out."

The user could not access the products page. The error message could be closed, and it appeared again when attempting to log in again.

## Test Status

PASS ✅

## Tester

Adam Oueslati
