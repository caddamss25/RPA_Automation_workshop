# 🤖 RPA Automation Workshop

An end-to-end UiPath automation project that extracts student examination results from a university result portal and consolidates the data into Google Sheets.

## 📖 Overview
Demo result page link : https://inadequately-unimpearled-alline.ngrok-free.dev/
This project demonstrates how to automate a web-based result portal using **UiPath Modern Design Experience**.

The robot:

- Reads student details from Google Sheets
- Opens the university result portal
- Enters Register Number and Date of Birth
- Retrieves examination results
- Extracts the subject-wise marks table
- Adds student information to each subject record
- Merges all students' results into a single DataTable
- Writes the consolidated output back to Google Sheets

---

## 🚀 Features

- Modern UiPath Activities
- Google Sheets Integration
- Dynamic Web Automation
- Table Data Extraction
- DataTable Manipulation
- Automatic Result Consolidation
- Browser Automation
- Exception Ready Workflow
- Beginner Friendly Project

---

## 🛠️ Technology Stack

- UiPath Studio
- Google Sheets
- Chrome Browser
- Modern UI Automation
- DataTables

---

## 📂 Project Structure

```
RPA_Automation_Workshop
│
├── Main.xaml
├── project.json
├── README.md
├── Input
├── Output
└── Screenshots
```

---

## 📥 Input

Google Sheet

| Register Number | DOB |
|----------------|------------|
| 23152001 | 26/07/2004 |
| 23152002 | 16/09/2004 |
| 23152003 | 06/01/2004 |

---

## 📤 Output

| Subject Code | UE | IA | Total | Result | Remark | Student Name | Register Number |
|--------------|----|----|-------|--------|--------|--------------|-----------------|
| CS101 | 58 | 13 | 71 | PASS | | MANOJ R | 23152001 |
| CS102 | 65 | 25 | 90 | PASS | | MANOJ R | 23152001 |
| ... | ... | ... | ... | ... | ... | ... | ... |

---

## 🔄 Workflow

```
Read Student Data
        │
        ▼
Open Result Portal
        │
        ▼
Enter Register Number
        │
        ▼
Enter DOB
        │
        ▼
Click Get Result
        │
        ▼
Extract Student Details
        │
        ▼
Extract Marks Table
        │
        ▼
Add Student Information
        │
        ▼
Merge Data
        │
        ▼
Write Results to Google Sheets
```

---

## 📚 Activities Used

### UI Automation

- Use Application/Browser
- Type Into
- Click
- Get Text
- Navigate Back

### Data

- Read Range
- Write Range
- Extract Table Data
- Merge Data Table
- Add Data Column
- Assign
- For Each Row
- If

---

## 💡 Learning Objectives

This project helps you learn:

- UiPath Modern Activities
- Browser Automation
- Dynamic Selectors
- Google Sheets Automation
- Data Extraction
- DataTable Operations
- Exception Handling
- End-to-End RPA Workflow Design

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/<your-username>/RPA_Automation_Workshop.git
```

2. Open the project in **UiPath Studio**.

3. Configure your Google Sheets connection.

4. Update the input sheet with:
   - Register Number
   - Date of Birth

5. Run the workflow.

6. Review the generated output in Google Sheets.

---

## 📸 Screenshots

> Add screenshots here.

- Input Google Sheet
- Result Portal
- Extracted Results
- Final Google Sheet Output

---

## 🔮 Future Enhancements

- Status Tracking
- Retry Mechanism
- Screenshot on Error
- Email Notifications
- PDF Report Generation
- Database Integration
- UiPath Orchestrator Deployment
- Queue Processing
- Parallel Processing

---

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a Pull Request

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

**CADDAMSS**

**CADDAM Software Solutions**

🌐 https://www.caddamss.com/

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
