# Google Sheets Email Automation Project

## 📊 Project Overview
This project automates sending Google Sheets data via email, including:

- Multiple sheets and multiple tables per sheet
- Cleanly formatted HTML tables with visible borders
- Preserves cell colors, fonts, and header styles
- Exports and attaches the **entire Google Sheet as Excel (.xlsx)**
- Works with Gmail, Outlook, or any email provider

This eliminates the tedious task of manually taking screenshots and sending daily reports.

---

## 🧠 Motivation
Manual reporting was repetitive and error-prone.  
This automation project:

- Saves time ⏱️  
- Ensures consistent formatting 🧾  
- Sends professional email reports automatically 📧  
- Provides a downloadable Excel attachment for sharing 📎  

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Google Sheets | Source of data |
| Google Apps Script | Automation scripting (JavaScript) |
| Gmail (MailApp) | Sending emails |
| Google Drive API | Export Google Sheets as Excel |
| Time-driven Triggers | Optional daily automation |

---

## ⚙️ Features

✅ Converts Google Sheets to HTML tables  
✅ Handles multiple tables per sheet separated by blank rows  
✅ Preserves colors, font weights, and visible borders  
✅ Automatically detects table column counts  
✅ Attaches the full Google Sheet as Excel  
✅ Sends emails to any provider  
✅ Optional daily automation via triggers  

---

## 🧩 Project Structure
```text
Google-Sheets-Automation/
├── Source Google Sheet/
│   ├── Sheet1
│   ├── Sheet2
│   └── Sheet3
├── Apps Script/
│   └── sendGoogleSheetReportWithBorders.gs
└── README.md 
```
## 🧱 Step-by-Step Usage

1. **Prepare Google Sheet**
   - Create sheets and tables
   - Leave at least one blank row between tables

2. **Open Apps Script**
   - Go to **Extensions → Apps Script**
   - Paste the code into the editor

3. **Grant Permissions**
   - Click **Run → Review Permissions → Allow**

4. **Test Run**
   - Run `sendGoogleSheetReportWithBorders()`
   - Check your email: tables formatted, borders visible, Excel attachment included

5. **Optional: Automate Daily**
   - Go to **Triggers → + Add Trigger**
   - Choose the function `sendGoogleSheetReportWithBorders`
   - Select **Time-driven → Daily → Choose time**

---

## 📅 Future Enhancements

- Auto-adjust text color for headers
- Include charts/images in the email
- Dynamic subject line with current date
- Integration with Slack or Teams for notifications

---

## 👨‍💻 Author

**Pranav Kamat**  
Automation & Data Enthusiast  
📧 pranav.p.kamat@gmail.com

