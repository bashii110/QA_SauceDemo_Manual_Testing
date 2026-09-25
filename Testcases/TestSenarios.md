# Test Scenarios — SauceDemo

## 1. Login

| ID     | Test Scenario                                                                   |
| ------ | ------------------------------------------------------------------------------- |
| TS-001 | Verify that a user can log in with valid credentials.                           |
| TS-002 | Verify that login fails when an invalid username is entered.                    |
| TS-003 | Verify that login fails when an invalid password is entered.                    |
| TS-004 | Verify that login validation is displayed when the username is empty.           |
| TS-005 | Verify that login validation is displayed when the password is empty.           |
| TS-006 | Verify that a locked/blocked user cannot log in.                                |
| TS-007 | Verify that the user is redirected to the Products page after successful login. |
| TS-008 | Verify that the logout option ends the authenticated session.                   |

## 2. Products

| ID     | Test Scenario                                                                       |
| ------ | ----------------------------------------------------------------------------------- |
| TS-009 | Verify that the Products page loads successfully after login.                       |
| TS-010 | Verify that products display their name, price, image, and action button correctly. |
| TS-011 | Verify that a user can open a product's details.                                    |
| TS-012 | Verify that a user can add a product to the cart from the Products page.            |
| TS-013 | Verify that a user can add multiple products to the cart.                           |
| TS-014 | Verify that the cart badge reflects the number of selected products.                |

## 3. Product Sorting

| ID     | Test Scenario                                                                     |
| ------ | --------------------------------------------------------------------------------- |
| TS-015 | Verify that products can be sorted by name in ascending order.                    |
| TS-016 | Verify that products can be sorted by name in descending order.                   |
| TS-017 | Verify that products can be sorted by price from low to high.                     |
| TS-018 | Verify that products can be sorted by price from high to low.                     |
| TS-019 | Verify that the selected sorting option is correctly applied to the product list. |

## 4. Product Details

| ID     | Test Scenario                                                                    |
| ------ | -------------------------------------------------------------------------------- |
| TS-020 | Verify that a user can open a product details page.                              |
| TS-021 | Verify that the product details page displays the correct product name.          |
| TS-022 | Verify that the product details page displays the correct price and description. |
| TS-023 | Verify that a product can be added to the cart from its details page.            |
| TS-024 | Verify that a user can return to the Products page from product details.         |

## 5. Shopping Cart

| ID     | Test Scenario                                                            |
| ------ | ------------------------------------------------------------------------ |
| TS-025 | Verify that the cart opens successfully.                                 |
| TS-026 | Verify that added products appear correctly in the cart.                 |
| TS-027 | Verify that the correct product name, price, and quantity are displayed. |
| TS-028 | Verify that a product can be removed from the cart.                      |
| TS-029 | Verify that the cart badge updates after removing a product.             |
| TS-030 | Verify that a user can continue shopping from the cart.                  |
| TS-031 | Verify that a user can proceed to checkout from the cart.                |

## 6. Checkout

| ID     | Test Scenario                                                                |
| ------ | ---------------------------------------------------------------------------- |
| TS-032 | Verify that the checkout page opens successfully.                            |
| TS-033 | Verify that a user can continue checkout with valid customer information.    |
| TS-034 | Verify that validation is displayed when the first name is empty.            |
| TS-035 | Verify that validation is displayed when the last name is empty.             |
| TS-036 | Verify that validation is displayed when the postal code is empty.           |
| TS-037 | Verify that the checkout information is retained correctly when proceeding.  |
| TS-038 | Verify that the order summary displays the selected product correctly.       |
| TS-039 | Verify that the order total is calculated correctly.                         |
| TS-040 | Verify that a user can complete an order successfully.                       |
| TS-041 | Verify that the order confirmation is displayed after successful completion. |

## 7. Navigation

| ID     | Test Scenario                                                       |
| ------ | ------------------------------------------------------------------- |
| TS-042 | Verify that the main navigation menu opens correctly.               |
| TS-043 | Verify that the user can navigate to the Products page.             |
| TS-044 | Verify that the user can navigate to the Cart.                      |
| TS-045 | Verify that navigation controls take the user to the expected page. |

## 8. Logout

| ID     | Test Scenario                                                             |
| ------ | ------------------------------------------------------------------------- |
| TS-046 | Verify that a logged-in user can log out successfully.                    |
| TS-047 | Verify that logout returns the user to the login page.                    |
| TS-048 | Verify that authenticated pages cannot be accessed normally after logout. |

## 9. Negative and Exploratory Scenarios

| ID     | Test Scenario                                                                               |
| ------ | ------------------------------------------------------------------------------------------- |
| TS-049 | Verify application behavior when required fields are left empty.                            |
| TS-050 | Verify application behavior when invalid input is provided.                                 |
| TS-051 | Verify application behavior when a user rapidly repeats an action.                          |
| TS-052 | Verify application behavior when navigating backward and forward between pages.             |
| TS-053 | Verify application behavior after refreshing key application pages.                         |
| TS-054 | Verify that displayed prices and totals remain consistent throughout the shopping workflow. |
