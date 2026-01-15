# Bug ID: BUG-002
## Add to cart buttons do not reset after selecting Reset App State

## Environment
- Application: Sauce Demo (Swag Labs) – https://www.saucedemo.com/
- Platform: Web
- Browser / Version: Safari 26.2
- OS: macOS Tahoe 26.2

## Preconditions
- User is logged in and on the Products page
- User has added one or more products to the cart

## Steps to Reproduce
1. Click the hamburger menu (top left)
2. Select Reset App State
3. Observe the cart badge
4. Observe the buttons for the previously added products

## Expected Result
- Cart badge is cleared (empty state)
- Buttons for all products reset to "Add to cart"

## Actual Result
- Cart badge may reset, but the buttons for previously added products remain in the "Remove" state and do not reset

## Severity
Medium

## Priority
Medium

## Status
New

## Bug Type
Functional


## Notes
Reset App State does not fully reset the UI state for product buttons.
