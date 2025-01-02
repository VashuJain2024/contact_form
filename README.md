# Contact Form 📬

This **Contact Form** is a simple, user-friendly web application built with HTML, CSS, and JavaScript. The form is designed to collect user information such as their name, email, phone number, and message. Submitted data is linked to a **Google Form**, allowing it to be stored in a Google Spreadsheet for easy management and analysis.

---

## 🚨 Important Note

**This form is currently not working as expected.**  
- Possible reasons include:
  - Incorrect or expired Google Form integration.
  - Issues with the form's POST endpoint.
  - Browser or iframe restrictions.  
Efforts to fix the issue are underway.

---

## Features ✨

- **Dynamic Data Collection**:
  - Users can submit their full name, email, phone number, and a message.
- **Google Form Integration**:
  - The form data is directly submitted to a linked Google Form, which stores it in a Google Spreadsheet.
- **Redirect on Submission**:
  - After successful submission, users are redirected to a confirmation or custom page.
- **Field Validation**:
  - Required fields ensure valid data entry.
  - Phone number validation supports international formats.

---

## How It Works 🔍

1. **User Input**:
   - Users fill in their details and submit the form.
2. **Google Form Integration**:
   - The form uses the **Google Form POST endpoint** (`formResponse`) to send data to a linked Google Spreadsheet.
3. **Hidden iFrame**:
   - Data is submitted via a hidden iframe to enable a smooth user experience.
4. **Redirection**:
   - After submission, the user is redirected to a specified page (e.g., a thank-you or home page).

---

## Installation and Setup 🚀

1. **Clone the repository**:
   ```bash
   git clone https://github.com/VashuJain2024/contact_form.git
   cd contact_form
