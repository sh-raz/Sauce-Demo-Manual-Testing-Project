# Sauce Demo – Manual Testing Project

## Project Overview
This project demonstrates a complete **manual testing cycle** performed on the **Sauce Demo (Swag Labs)** e-commerce web application.  
The goal of the project is to practice and showcase **real-world manual testing skills**, including test planning, test design, execution, and bug reporting.
The application simulates an online shopping experience where users can log in, browse products, add items to a cart, and complete checkout.

---

## Application Under Test
- **Name:** Sauce Demo (Swag Labs)
- **URL:** https://www.saucedemo.com/
- **Type:** Web-based e-commerce demo application

---

## Scope of Testing
The following core features were tested:
### Login
- Valid and invalid login attempts
- Empty field validation
- Locked-out user behavior
- Error message verification

### Products Page
- Product visibility and information
- Sorting by name and price
- Add / remove items from cart
- Cart badge updates
- Navigation to product details
- State persistence (refresh, navigation)
- Reset App State behavior

### Checkout
- Navigation from cart to checkout
- Checkout information validation
- Overview page verification
- Price, tax, and total calculation
- Order completion and confirmation
- Post-checkout cart reset

---

## Testing Approach
- Test scenarios were written to define **what to test**
- Detailed test cases were created to define **how to test**
- Tests were executed manually
- Observed issues were documented as bug reports
- Coverage was assessed based on functional risk

---

## Project Structure

sauce-demo-manual-testing/
- [01-Requirements](01-Requirements)
  - [app_overview.md](01-Requirements/app_overview.md)

- [02-Test-Scenarios](02-Test-Scenarios)
  - [login_scenarios.md](02-Test-Scenarios/LoginScenarios.md)
  - [product_scenarios.md](02-Test-Scenarios/ProductsScenarios.md)
  - [checkout_scenarios.md](02-Test-Scenarios/CheckoutScenarios.md)

- [03-Test-Cases](03-Test-Cases)
  - [login_test_cases.csv](03-Test-Cases/LoginTestCases.csv)
  - [product_test_cases.csv](03-Test-Cases/ProductsTestCases.csv)
  - [checkout_test_cases.csv](03-Test-Cases/CheckoutTestCases.csv)

- [04-Bug-Reports](04-Bug-Reports)
  - [BUG-001 – Cart persists after logout](04-Bug-Reports/BUG-001-cart-persists-after-logout.md)
  - [BUG-002 – Reset App State does not reset buttons](04-Bug-Reports/BUG-002-reset-app-state-does-not-reset-buttons.md)

- [05-Test-Reports](05-Test-Reports)
  - [test_summary.md](05-Test-Reports/test_summary.md)

---
## Test Coverage Summary
| Feature   | Coverage |
|----------|----------|
| Login    | ~90–95% |
| Products | ~90–92% |
| Checkout | ~95% |

---
## Sample Bug Found
Functional defects were identified and documented during testing.
Detailed bug reports, including steps to reproduce and expected vs actual results, are available in the [04-Bug-Reports](04-Bug-Reports) folder.

---

## Documentation Formats Used
- **Markdown (`.md`)** – Requirements, scenarios, bug reports, summaries
- **CSV (`.csv`)** – Detailed test cases (GitHub & tool friendly)

---

## Key Skills Demonstrated
- Manual test design techniques
- Positive & negative testing
- Boundary and validation testing
- Test case traceability
- Bug reporting with clear reproduction steps
- Risk-based coverage decisions
- Version control–friendly documentation






