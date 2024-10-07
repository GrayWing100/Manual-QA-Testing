# Test Case Samples
![Facebook Login Screenshot](https://github.com/GrayWing100/Manual-QA-Testing/blob/main/pictures/Facebook.png)

### :one: Test Cases: Verify successful login with valid credentials :arrow_down:

### Test ID: FB-01

**Test Title:** Test login with correct credentials

**Description:** Test the login by using valid credentials to ensure successful access to the Facebook account.

**Prerequisites:** 
- A web browser (Chrome, Firefox, Safari, etc.)
- An active Facebook account for testing
- Access to the Facebook login page (https://www.facebook.com/)
- Stable internet connection

**Steps to reproduce:**
1. Open the browser and go to https://www.facebook.com/.
2. Enter a valid username and password in the respective fields.
3. Press the login button
4. Observe if the user is redirected to the Facebook homepage.

**Expected result:** The user should be successfully logged in and redirected to the homepage.

**Actual result:** User is able to login.

**Test Data:** Username: `Valid username` & Password: `Valid password`

#


### 2️⃣: Test Cases: Test login with invalid credentials :arrow_down:

### Test ID: FB-02

**Test Title:** Test login with invalid credentials

**Description:** Ensure that login is unsuccessful when using invalid credentials.

**Prerequisites:** 
- A web browser (Chrome, Firefox, Safari, etc.)
- Access to the Facebook login page (https://www.facebook.com/)

**Steps to reproduce:**
1. Open the browser and go to https://www.facebook.com/.
2. Enter an incorrect username and password.
3. Click on the "Login" button.
4. Observe if the user can log in or if an error message is displayed.

**Expected result:** An error message should be displayed in red text, stating: "The password that you've entered is incorrect."

**Actual result:** Error message is displayed stating "The password that you've entered is incorrect."

**Test Data:** Username: `Invalid username` & Password: `Invalid password`

#


### 3️⃣ : Test Cases: Verify login with empty fields :arrow_down:

### Test ID: FB-03

**Test Title:** Verify login with empty fields

**Description:** Test unsuccessful login when both or either of the fields (email/phone and password) are left empty.

**Prerequisites:** 
- A web browser (Chrome, Firefox, Safari, etc.)
- Access to the Facebook login page (https://www.facebook.com/)

**Steps to reproduce:**
1. Open the browser and navigate to https://www.facebook.com/.
2. Leave both **email/phone** and **password** fields empty.
3. Click the "Login" button.
4. Observe if an error message is shown.
5. Reload the page and enter only **email/phone**, leaving the password field empty.
6. Click the "Login" button.
7. Reload the page again, this time enter only the **password**, leaving the email/phone field empty.
8. Click the "Login" button.

**Expected result:** 
- Step 4: An error message should be displayed stating "Please enter your email or phone number" in red text, next to the respective field or at the top of the form.
- Step 6: The same error message should be displayed for the empty password field: "Please enter your password."
- Step 8: The same message for the empty email field: "Please enter your email or phone number."

**Actual result:** Error messages are displayed correctly when both or either of the fields are left empty.

**Test Data:** None

**Additional Checks:**
- Verify that the error message is shown in a prominent color (e.g., red).
- Ensure that the **Login** button becomes inactive or remains clickable but provides appropriate feedback (e.g., error highlight).
- Check the form behavior across different browsers to ensure consistent validation.







