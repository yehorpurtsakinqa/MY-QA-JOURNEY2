# Checklist: Registration and Search Functionality (bol.com)

## Positive Test Cases
1. **Registration:** Successful signup with a valid email and password.
2. **Cart Management:** Add an item to the cart as a registered user.
3. **Navigation:** "Bol" logo returns the user to the Home Page from any subpage.
4. **Search Function:** Find a product using a valid keyword (e.g., "Laptop").
5. **Localization:** Change region settings from NL to BE (Belgium).

## Negative Test Cases
1. **Empty Email:** Attempt registration with an empty email field.
2. **Unregistered Cart:** Verify behavior when adding items without login (should prompt for login at checkout).
3. **Empty Results:** Search for a non-existent product name.
4. **Invalid Input:** Search using only special characters or symbols.
5. **Empty Password:** Attempt registration with an empty password field.
