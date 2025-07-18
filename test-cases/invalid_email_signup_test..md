# Test Case: Invalid Email During Signup

**Tested Feature**: LinkedIn user signup form  
**Preconditions**: User is on the homepage of LinkedIn

## Steps:
1. Click on “Join now”
2. Enter “Lucia” as first name
3. Enter “lucia.com” (invalid email) in the email field
4. Enter a valid password
5. Click “Agree & Join”

## Expected Result:
An error message is displayed: “Please enter a valid email address”

## Actual Result:
❌ No error message is displayed, the form remains active

## Status:
FAILED