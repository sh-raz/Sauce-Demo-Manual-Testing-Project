# Bug ID: BUG-001
## Cart items persist after logout when logging in with a different user
<Short clear summary of the bug>

## Environment
- Application: Sauce Demo(Swag labs) - https://www.saucedemo.com/
- Platform: Web
- Browser / Version: Safari version 26.2
- OS: MacOs Tahoe 26.2

## Preconditions
- User A has a valid account
- User B has a valid account


## Steps to Reproduce
1. Log in with User A
2. Add one or more products to the cart
3. Log out
4. Log in with User B


## Expected Result
The cart should be empty for User B

## Actual Result
The cart contains products added by User A
## Severity
Medium

## Priority
Medium

## Status
New

## Bug Type
Functional

## Attachments 
<Screenshot>
- Video:

## Notes 

