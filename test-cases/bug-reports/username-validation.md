# 🐞 Bug Report — Username Field Validation

**Summary:**  
Username field accepts Cyrillic characters but crashes upon submission.

**Steps to Reproduce:**
1. Go to registration form
2. Enter `Тест` into the "Username" field
3. Fill other fields correctly
4. Click "Submit"

**Expected Result:**  
Error message: "Only Latin characters allowed"

**Actual Result:**  
App crashes with `500 Internal Server Error`

**Environment:**  
- macOS Sequoia 15.4  
- Chrome 124  
- App version: 2.1.0

**Attachments:**  
_(optional)_ Screenshot + console log
