# WordPress Authentication Manual Testing

## 📌 Project Overview

This project contains manual testing documentation for a WordPress-based blog website that implements authentication and access restriction features.

The purpose of this project is to demonstrate structured manual testing practices including test planning, test case writing, execution, and bug reporting.

---

## 🎯 Application Features Tested

- User Registration
- User Login
- Logout
- Restricted Page Access (Authorization)
- Responsive UI (Basic UI Testing)

---

## 🔍 Scope of Testing

The following testing types were performed:

- Functional Testing
- Negative Testing
- Boundary Value Testing
- Authorization Testing
- Session Testing
- Basic UI Testing

---

## 🧪 Test Approach

### 1️⃣ Requirement Analysis

Reviewed authentication flow and access control logic:

- Unauthenticated users cannot access restricted pages
- Registered users can log in
- Logged-in users can access protected content

### 2️⃣ Test Design

Created:

- Test Scenarios
- Detailed Test Cases
- Bug Report Template
- Test Summary Report

### 3️⃣ Test Execution

All test cases were executed manually using a web browser.

---

## 🛠 Tools Used

- Google Chrome
- Microsoft Excel
- GitHub
- Chrome DevTools (for basic inspection)

---

## 📊 Test Summary

| Metric               | Result |
| -------------------- | ------ |
| Total Test Cases     | 25     |
| Passed               | 0      |
| Failed               | 0      |
| High Severity Bugs   | 0      |
| Medium Severity Bugs | 0      |
| Low Severity Bugs    | 0      |

---

## 🐞 Example Test Areas Covered

### ✅ Registration Testing

- Valid registration
- Duplicate email
- Invalid email format
- Empty required fields
- Password minimum length validation

### ✅ Login Testing

- Valid credentials
- Incorrect password
- Unregistered email
- Empty fields

### ✅ Authorization Testing

- Access restricted page without login
- Access restricted page after login
- Access restricted page after logout

### ✅ Session Testing

- Browser refresh after login
- Back button behavior after logout
