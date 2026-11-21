# Test Cases — AutomationExercise

Source: Zephyr Advanced export from Jira. Test case descriptions and steps are transcribed from the export.

## P1-T1 — Login User with incorrect email and password
**Folder:** Authentication
**Workflow Status:** Approved

**Objective:** Verify that the application displays an error message when a user attempts 
to log in with an incorrect email address and password.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Signup / Login button | The login page is displayed successfully |
| 2 | Enter an invalid email address in the Email Address field. | The email address is entered into the field. |
| 3 | Enter an incorrect password in the Password field. | The password is entered into the field. |
| 4 | Click the Login button. | An error message is displayed indicating that the email address or password  is incorrect. |

## P1-T2 — Register User with existing email address
**Folder:** Authentication
**Workflow Status:** Approved

**Objective:** Verify that the application prevents a new user from registering with an 
email address that is already registered and displays an appropriate error 
message.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Signup / Login button | The login page is displayed successfully |
| 2 | Enter a name and an already registered email address in the New User  Signup! section. | The name and email address are entered into their respective fields. |
| 3 | Click the Signup button. | The application rejects the registration attempt because the email address  is already registered. |
| 4 | Verify the error message displayed on the page. | The error message Email Address already exist! is visible. |

## P1-T11 — Open Login Page
**Folder:** Authentication
**Workflow Status:** Approved

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Signup / Login button | The login page is displayed successfully |

## P1-T3 — Contact Us
**Folder:** Contact Us
**Workflow Status:** Approved

**Objective:** Verify that a user can submit the Contact Us form successfully.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Contact Us button. | The Contact Us page is displayed, and the contact form is visible. |
| 2 | Enter a name, email address, subject, and message in the Contact Us form. | All required form fields accept the entered data. |
| 3 | Upload a sample file using the Choose File option. | The selected file is attached successfully. |
| 4 | Click the Submit button. | A confirmation dialog appears asking the user to confirm the submission. |
| 5 | Click OK on the confirmation dialog. | The confirmation dialog closes. |
| 6 | Verify that the success message is displayed. | The success message Success! Your details have been submitted successfully.  is displayed. |

## P1-T4 — Verify Test Cases Page  Copy
**Folder:** Test Cases Page
**Workflow Status:** Approved

**Objective:** Verify that the Test Cases page opens successfully and displays the 
available test cases.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Test Cases button in the navigation bar. | The Test Cases page opens successfully. |
| 2 | Verify that the Test Cases page heading is displayed. | The page heading Test Cases is visible. |
| 3 | Verify that the page contains a list of test cases with their descriptions  or steps. | The page displays the available test cases and their corresponding  instructions. |
| 4 | Verify that the test cases page content is readable and accessible. | The test cases and their instructions are displayed without a page-loading  error. |

## P1-T5 — View All Products and Product Details
**Folder:** Products
**Workflow Status:** Approved

**Objective:** Verify that the Products page displays the product list and that a user can 
open a product's details.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Products button in the navigation bar. | The Products page opens successfully. |
| 2 | Verify that the product list is displayed. | A list of products is displayed with product information. |
| 3 | Click on the View Product button for any product. | The selected product's details page opens. |
| 4 | Verify that the product details are displayed. | The product name, category, price, availability, condition, and brand are  displayed. |
| 5 | Verify that the product image is displayed. | The selected product's image is visible. |

## P1-T6 — Search Product
**Folder:** Products
**Workflow Status:** Approved

**Objective:** Verify that a user can search for a product and view relevant search 
results.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Products button in the navigation bar. | The Products page opens successfully, and the search field is visible. |
| 2 | Enter a product name in the search field. | The product name is entered into the search field. |
| 3 | Click the search button. | The search request is processed. |
| 4 | Verify the Searched Products heading and the search results. | The Searched Products heading is displayed, and relevant products matching  the search term are shown. |

## P1-T7 — Verify Subscription in Home Page Copy Name
**Folder:** Subscription
**Workflow Status:** Approved

**Objective:** Verify that a user can subscribe to the website's newsletter from the home 
page.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Scroll down to the bottom of the home page. | The Subscription section is visible at the bottom of the page. |
| 2 | Verify that the SUBSCRIPTION heading is displayed. | The SUBSCRIPTION heading is visible. |
| 3 | Enter a valid email address in the email field. | The email address is entered into the subscription field. |
| 4 | Click the subscription arrow button. | The subscription request is submitted successfully. |
| 5 | Verify the subscription confirmation message. | The message You have been successfully subscribed! is displayed. |

## P1-T8 — Verify Subscription in Cart Page
**Folder:** Subscription
**Workflow Status:** Approved

**Objective:** Verify that a user can subscribe to the website's newsletter from the Cart 
page.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Cart button in the navigation bar. | The Cart page is displayed successfully. |
| 2 | Scroll down to the bottom of the Cart page. | The Subscription section is visible. |
| 3 | Verify that the SUBSCRIPTION heading is displayed. | The SUBSCRIPTION heading is visible. |
| 4 | Enter a valid email address in the subscription email field. | The email address is entered into the subscription field. |
| 5 | Click the subscription arrow button. | The subscription request is submitted successfully. |
| 6 | Verify the subscription confirmation message. | The message You have been successfully subscribed! is displayed. |

## P1-T9 — Add Products in Cart
**Folder:** Cart
**Workflow Status:** Approved

**Objective:** Verify that a user can add multiple products to the cart and that the cart 
displays the correct product details, quantities, and prices.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Products button in the navigation bar. | The Products page opens, and the product list is displayed. |
| 2 | Click Add to cart for the first product. | The product is added to the cart, and a confirmation modal appears. |
| 3 | Click Continue Shopping in the confirmation modal. | The modal closes, and the Products page remains available. |
| 4 | Click Add to cart for a second product. | The second product is added to the cart. |
| 5 | Click View Cart. | The Cart page opens and displays both added products. |
| 6 | Verify the product details in the cart. | Each product displays the correct name, price, quantity, and total price. |

## P1-T10 — Remove Products From Cart
**Folder:** Cart
**Workflow Status:** Approved

**Objective:** Verify that a user can remove a product from the cart successfully.

| Step | Test Step | Expected Result |
|---|---|---|
| 1 | Click on the Products button in the navigation bar. | The Products page opens successfully. |
| 2 | Click Add to cart for any product. | The product is added to the cart successfully. |
| 3 | Click View Cart to open the Cart page. | The Cart page opens and displays the added product. |
| 4 | Click the X button next to the product in the cart. | The selected product is removed from the cart. |
| 5 | Verify that the removed product is no longer displayed in the cart. | The product removed in Step 5 |
