
# Test Summary Report – Sauce Demo

## Application
Sauce Demo (Swag Labs)  
https://www.saucedemo.com/

## Test Type
Manual Functional Testing

## Test Scope
The following features were tested:
- Login
- Products page
- Checkout process

## Test Approach
Testing was performed manually using predefined test scenarios and test cases.  
Both positive and negative test cases were executed to validate core functionality and user flows.

## Test Coverage Summary
| Feature   | Coverage |
|----------|----------|
| Login    | ~90–95% |
| Products | ~90–92% |
| Checkout | ~95% |

Testing was stopped when acceptable risk coverage was achieved.

## Test Execution Result
- Most test cases passed successfully
- Core user flows are functional
- Some issues were identified during testing

## Defects Found
The following defects were reported:
- **BUG-001:** Cart items persist after logout when logging in with a different user
- **BUG-002:** Add to cart buttons do not reset after selecting Reset App State

Detailed bug reports are available in the `04-Bug-Reports` folder.

## Out of Scope
The following testing types were not performed:
- Performance testing
- Security testing
- Accessibility testing
- Cross-browser testing

## Overall Test Conclusion
The Sauce Demo application is stable for core e-commerce flows; however, some state management issues were identified.  
The application is suitable for demonstration purposes, with known limitations documented in bug reports.
