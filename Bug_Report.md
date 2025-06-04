#  Bug Report

## Bug ID: BUG-001  
## Title: Login form shows "username is invalid" instead of "fields are required" when submitted empty

---

###  Description:
When the user submits the login form without entering both username and password, the system incorrectly returns an "invalid username" error message instead of indicating that both fields are required. This behavior misleads users and shows poor input validation handling.

---

###  Steps to Reproduce:
1. Navigate to the login page.
2. Leave both the **username** and **password** fields empty.
3. Click on the **Login** button.

---

###  Expected Result:
The system should display a required field error such as:  
> **"Username and password are required"**

---

###  Actual Result:
> **"Your username is invalid!"**

This suggests the form is treating empty input as invalid data instead of missing data.

---

###  Environment:
- **OS**: Windows 10  
- **Browser**: Chrome v124  
- **App Version**: Demo Login Page  
- **URL**: https://practicetestautomation.com/practice-test-login/

---

###  Severity: Medium  
###  Priority: Medium  
###  Status: Open  
###  Reported By: Haneef  
###  Date Reported: 2025-06-04
