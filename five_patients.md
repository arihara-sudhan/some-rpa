# Five Patients - Claim Status Portal

A simple web-based Claim Status Enquiry system with login authentication and hardcoded patient data for demo purposes.

---

## 🔐 Login Credentials

To access the portal:

- **Username:** `ari`
- **Password:** `verysecret2026`

---

## 🧾 How to Use

1. Open `index.html` in a browser
2. Login using the credentials above
3. Enter patient claim details
4. Click **"Check Claim Status"**
5. View the claim result:
   - Paid
   - Denied
   - Partially Paid
   - Pending
   - No Claim Found

---

## 📊 Test Data (Use these inputs)

### 1. PAID CLAIM
- Member ID: `M1001`
- Last Name: `Smith`
- Date of Birth: `1990-04-12`
- Date of Service: `2025-01-10`
- Claim Number: `CLM9001`
- Provider Name: `Apollo Hospital`
- Payer Name: `Aetna`

---

### 2. DENIED CLAIM
- Member ID: `M1002`
- Last Name: `Johnson`
- Date of Birth: `1988-07-22`
- Date of Service: `2025-02-15`
- Claim Number: `CLM9002`
- Provider Name: `City Care`
- Payer Name: `Cigna`

---

### 3. PARTIALLY PAID CLAIM
- Member ID: `M1003`
- Last Name: `Williams`
- Date of Birth: `1975-03-30`
- Date of Service: `2025-03-01`
- Claim Number: `CLM9003`
- Provider Name: `Global Clinic`
- Payer Name: `UnitedHealth`

---

### 4. PENDING CLAIM
- Member ID: `M1004`
- Last Name: `Brown`
- Date of Birth: `1995-11-18`
- Date of Service: `2025-04-20`
- Claim Number: `CLM9004`
- Provider Name: `Sunrise Medical`
- Payer Name: `Humana`

---

### 5. NO CLAIM FOUND
- Member ID: `M1005`
- Last Name: `Davis`
- Date of Birth: `1982-09-09`
- Date of Service: `2025-05-05`
- Claim Number: `CLM9005`
- Provider Name: `Metro Hospital`
- Payer Name: `BlueCross`

---

## ⚙️ Features

- Login authentication (front-end only)
- Claim status validation
- 5 hardcoded patient records
- Status types:
  - Paid
  - Denied (with reason)
  - Partially Paid (with reason)
  - Pending (with reason)
  - No Claim Found

---

## 🚨 Note

This is a **demo project only**. No real database or backend is connected. All data is stored in JavaScript inside the browser.

---
