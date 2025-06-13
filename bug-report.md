# 🐞 Paylocity - Bug Report

## Bug #1 - Login fails with valid credentials

**Type:** Functional  
**Severity:** High (blocker)  
**Priority:** High  
**Module:** Login  

### 🔁 Steps to Reproduce:
1. Navigate to: [https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login](https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login)
2. Enter username: `TestUser75`
3. Enter password: `+=wco*Pz1tLS`
4. Click the **Log In** button

### ✅ Expected Result:
The user should be successfully redirected to the Benefits Dashboard.

### ❌ Actual Result:
The system returns the error:  
> "The Password field is required."  
even though the password field was properly filled.

### 📸 Evidence:
![Login Error](https://github.com/mralexis99r/automation-test-paylocity/raw/main/images/login-error.png)


### 🔎 Additional Notes:
- Tested on the latest version of Chrome.
- Tried both typing and pasting the password.
- Also tested in incognito mode.
- Keyboard was set to English (US).
- This issue completely blocks UI exploration and testing.
