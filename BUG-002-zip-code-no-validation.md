# BUG-002 – Zip Code accepts any input

Date: 2025-07-23  
Tester: César  
Status: Open  
Severity: Medium  
Priority: Medium  
Page: Checkout – https://www.saucedemo.com/checkout-step-one.html  
Browser: Chrome 125 / Windows 11  

---

## Description

The "Zip/Postal Code" field accepts anything: letters, numbers, special characters, or a mix of all. There is no validation and the system lets you continue the checkout.

---

## Steps to Reproduce

1. Go to saucedemo.com and log in  
2. Add any product to the cart  
3. Go to checkout  
4. In the "Zip/Postal Code" field, enter something like: `abc123!@#`  
5. Click the "Continue" button

---

## Expected Result

The system should only accept valid zip codes — for example, only numbers. It should not allow special characters or letters.

---

## Actual Result

It accepts anything and moves to the next step without showing any error.

---

## Notes

I also tried leaving the field empty, and it still continues.  
Same happens with the "First Name" and "Last Name" fields — you can write numbers or symbols and the system accepts it.

## Attachments

<img width="1920" height="913" alt="image" src="https://github.com/user-attachments/assets/37e59e11-090f-4e7e-846c-7a55a536ea56" />

<img width="1920" height="913" alt="image" src="https://github.com/user-attachments/assets/1c85ce52-ac2b-4758-8a62-20befa1ffab9" />


