# Login Functionality Test Cases

## Test Case 1: Valid Login
-**Test Case ID**: TC_Login_001
- **Test Objective**: Verify the user can log in with valid credentials.
- **Precondition**: The user has a valid account.
- **Steps**:
  1. Go to the login page.
  2. Enter a valid username.
  3. Enter the corresponding password.
  4. Click the "Login" button.
- **Expected Result**: The user is redirected to the dashboard

## Test Case 2: Invalid Login
-**Test Case ID**: TC_Login_002
- **Test Objective**: Verify error message for incorrect credentials.
- **Precondition**: User account exists.
- **Steps**:
  1. Go to the login page.
  2. Enter a valid username.
  3. Enter an invalid password.
  4. Click the "Login" button.
- **Expected Result**: Display an error message.

## Test Case 3: Empty Username and Password Fields
-**Test Case ID**: TC_Login_003
- **Test Objective**: Verify that the system shows an error message when both fields are empty.
- **Steps**:
  1. Open the login page: https://online.actitime.com/krn4/login.do.
  2. Leave the "Username" and "Password" fields empty.
  3. Click the "Login" button.
- **Expected Result**: The system should display an error message indicating that the fields cannot be left empty.

## Test Case 4: Empty Username Field
-**Test Case ID**: TC_Login_004
-**Test Objective**: Verify that the system shows an error message when the "Username" field is left empty and the password is entered.
-**Steps**:
  1. Open the login page: https://online.actitime.com/krn4/login.do.
  2. Leave the "Username" field empty.
  3. Enter a valid password in the "Password" field.
  4. Click the "Login" button.
- **Expected Result**: The system should display an error message indicating that the "Username" field cannot be left empty.

## Test Case 5: Empty Password Field
-**Test Case ID**: TC_Login_005
-**Test Objective**: Verify that the system shows an error message when the "Password" field is left empty, but a valid username is entered.
-**Steps**:
  1. Open the login page: https://online.actitime.com/krn4/login.do.
  2. Enter a valid username in the "Username" field.
  3. Leave the "Password" field empty.
  4. Click the "Login" button.
- **Expected Result**: The system should display an error message indicating that the "Password" field cannot be left empty.

## Test Case 6: Password Reset Link
-**Test Case ID**: TC_Login_006
-**Test Objective**: Verify that the user can access the password reset functionality.
-**Steps**:
  1. Open the login page: https://online.actitime.com/krn4/login.do.
  2. Click on the "Forgot your password?" link.
  3. Verify that the system redirects to the password reset page.
- **Expected Result**: The user should be redirected to the password reset page, where they can enter their email address to receive a reset link.

## Test Case 7: Login with Special Characters in Username and Password
-**Test Case ID**: TC_Login_007
-**Test Objective**: Verify that the system can handle special characters in both username and password fields.
-**Precondition**: The user has a valid username and password containing special characters.
-**Steps**:
  1. Open the login page: https://online.actitime.com/krn4/login.do.
  2. Enter a username with special characters in the "Username" field.
  3. Enter the corresponding password with special characters in the "Password" field.
  4. Click the "Login" button.
- **Expected Result**: The user is successfully logged in and redirected to the home page or dashboard.

## Test Case 8: Remember Me Functionality
-**Test Case ID**: TC_Login_008
-**Test Objective**: Verify that the "Keep me logged in" checkbox functions correctly.
-**Precondition**: The user has a registered account.
-**Steps**:
  1. Navigate to the login page.
  2. Enter a valid username in the "Username" field.
  3. Enter the correct password in the "Password" field.
  4. Check the "Keep me logged in" checkbox.
  5. Click the "Login" button.
  6. Log out from the application.
  7. Navigate back to the login page.
- **Expected Result**: The user should be automatically logged back in without needing to re-enter credentials.

## Test Case 9: UI Elements Verification
-**Test Case ID**: TC_Login_009
-**Test Objective**: Verify that all UI elements (fields, buttons, links) are correctly displayed and functional.
-**Steps**:
  1. Open the login page: https://online.actitime.com/krn4/login.do.
  2. Check the presence of the following:
    "Username" input field
    "Password" input field
    "Login" button
    "Forgot your password?" link
    "Keep me logged in" checkbox
  3. Verify that all these elements are visible and clickable.
- **Expected Result**: All elements should be visible and fully functional.

## Test Case 10: Login Session Timeout
-**Test Case ID**: TC_Login_010
-**Test Objective**: Verify that the user session times out after a period of inactivity.
-**Precondition**:  The user is logged in.
-**Steps**:
  1. Log in with valid credentials.
  2. Leave the application idle for a predetermined session timeout period (e.g., 15 minutes).
  3. Attempt to perform any action.
- **Expected Result**: The user is logged out and redirected to the login page with a message indicating session timeout.

## Test Case 11: Concurrent Login Attempt
-**Test Case ID**: TC_Login_011
-**Test Objective**: Verify that the application handles concurrent login attempts from multiple devices.
-**Precondition**: The user is logged in on one device.
-**Steps**:
  1. Login with valid credentials on Device A.
  2. Attempt to log in with the same credentials on Device B.
- **Expected Result**: Depending on the application policy, either:
    Device B successfully logs in, and Device A is logged out.
    Device B receives an error message indicating the account is already in use.

## Test Case 12: Browser Compatibility
-**Test Case ID**: TC_Login_012
-**Test Objective**: Verify that the login functionality works across different browsers.
-**Steps**:
  1. Open the login page in different web browsers (e.g., Chrome, Firefox, Safari, Edge).
  2. Enter valid credentials in each browser.
  3. Click the "Login" button in each browser.
- **Expected Result**: The user is successfully logged in and redirected to the dashboard/home page in all browsers.

## Test Case 13: Mobile Responsiveness
-**Test Case ID**: TC_Login_013
-**Test Objective**: Verify that the login page is responsive on mobile devices.
-**Steps**:
  1. Open the login page on a mobile device or use browser developer tools to simulate a mobile device.
  2. Enter valid credentials.
  3. Click the "Login" button.
- **Expected Result**: The login page is displayed correctly, and the user can log in without issues.







