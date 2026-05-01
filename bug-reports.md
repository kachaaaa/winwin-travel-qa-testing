# 🐞 Bug Reports – WinWin Travel

---

## Bug 1: Registration with existing email shows generic error message

**Severity:** Medium  
**Priority:** Medium  

**Steps to reproduce:**
1. Open registration form  
2. Enter an email that is already registered  
3. Enter valid password  
4. Submit the form  

**Expected result:**  
User should see a clear message like "Email already exists"

**Actual result:**  
Generic error message is displayed:  
"Uh-oh! Something went wrong!"

---

## Bug 2: System allows email with leading whitespace

**Severity:** Medium  
**Priority:** Medium  

**Steps to reproduce:**
1. Enter email with leading space: " user@gmail.com"  
2. Submit registration form  

**Expected result:**  
System should trim whitespace or show validation error  

**Actual result:**  
Registration is allowed with email containing whitespace  

---

## Bug 3: Hotel images are not loaded

**Severity:** High  
**Priority:** High  

**Steps to reproduce:**
1. Open hotel page  
2. Observe image section  

**Expected result:**  
Images should be displayed  

**Actual result:**  
Text "Image cannot be loaded" is shown  

---

## Bug 4: Landing page link returns 404

**Severity:** High  
**Priority:** Medium  

**Steps to reproduce:**
1. Open URL: /app/landings/en  

**Expected result:**  
Landing page opens  

**Actual result:**  
404 error page is displayed  

---

## Bug 5: Text overflow breaks layout

**Severity:** Low  

**Steps to reproduce:**
1. Open hotel page  
2. Observe top-right section  

**Expected result:**  
Text fits within container  

**Actual result:**  
Text overflows outside container  

---

## Bug 6: Non-functional header features are accessible

**Severity:** Medium  

**Steps to reproduce:**
1. Click header features (Notifications, Language, etc.)  

**Expected result:**  
Unavailable features should be hidden or disabled  

**Actual result:**  
User sees "This feature is under development"
