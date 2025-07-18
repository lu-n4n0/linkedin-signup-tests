# Bug Report – Invalid Email Not Rejected During Signup

**Bug ID**: BUG-LINKEDIN-001  
**Severity**: Medium  
**Environment**: Chrome 114 / Windows 10  
**Status**: Open

## Steps to Reproduce:
1. Go to LinkedIn signup page
2. Enter “lucia.com” as email (without "@")
3. Enter a valid password
4. Click on “Join”

## Expected Behavior:
User is blocked and a validation message is shown

## Actual Behavior:
Form continues with no error message

## Comments:
Email field does not validate client-side input correctly.