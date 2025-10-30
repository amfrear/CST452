# 📘 CST-452 Milestone 4 – Development (Coding Phase)

**Project Title:** Medical Journey Log  
**Student:** Alex Frear  
**Course:** CST-452 – Capstone Project II  
**Institution:** Grand Canyon University  

---

## 🩺 Project Overview
The **Medical Journey Log** is a web-based application designed to help caregivers track their children’s medical experiences, including symptoms, treatments, milestones, and appointments. The system simplifies communication between caregivers by centralizing health information in an accessible, secure way.

This milestone focused on **developing and implementing key features** outlined during the design phase, transforming the technical specification into a fully functioning web application.

---

## 🧩 Milestone 4 Objectives
According to the CST-452 Capstone Handbook, Milestone 4 represents the **Development Phase**, where students:
- Translate design specifications into working code.  
- Build and integrate core system components.  
- Implement database and UI functionality.  
- Demonstrate the application running successfully through screencasts.

---

## 🧠 Features Implemented
This milestone introduced **full CRUD functionality** for *Children* and *Symptoms* within the Medical Journey Log:

| Feature | Description |
|----------|-------------|
| **Add Child / Symptom** | Allows caregivers to log children and their symptoms. |
| **Edit Child / Symptom** | Enables correction or updates to existing records. |
| **Delete Child / Symptom** | Supports deletion while enforcing data safety rules (e.g., preventing child deletion while symptoms exist). |
| **Success & Error Alerts** | Added TempData messages displayed through Bootstrap alerts. |
| **Database Integration** | Connected to MySQL through Entity Framework Core. |

---

## 🧰 Technologies Used
- **Language:** C# (.NET 7)  
- **Framework:** ASP.NET Core Razor Pages  
- **Database:** MySQL (via EF Core ORM)  
- **IDE:** Visual Studio / VS Code on macOS  
- **UI:** Bootstrap 5  
- **Version Control:** Git + GitHub  

---

## 🎥 Screencasts
Two short screencasts were recorded to demonstrate this milestone’s deliverables:

1. **Code Review Video** – Walkthrough of the four primary PageModel files:
   - `EditChild.cshtml.cs`  
   - `DeleteChild.cshtml.cs`  
   - `EditSymptom.cshtml.cs`  
   - `DeleteSymptom.cshtml.cs`  

2. **Application Running Video** – Demonstrates the working application, including:
   - Editing and deleting children and symptoms.  
   - Error handling when attempting to delete a child with existing symptoms.  
   - Validation messages and database confirmation.

*(Screencast links will be provided upon submission to GCU’s LMS.)*

---

## 📄 Included Files

| File | Description |
|------|-------------|
| `/MedicalJourneyLog/` | Full application source code. |
| `Milestone 4 Submission Document.pdf` | Formal report and screenshots per GCU Milestone 4 rubric. |
| `.gitignore` | Filters out temporary and build files. |

---

## 🚀 Next Steps
Milestone 5 will focus on **system testing**, validating functionality through structured test cases (TC-001–TC-010) and documenting results. The application will then progress toward refinement, final evaluation, and presentation.

---

## 🏫 Acknowledgment
This project is developed as part of the CST-452 Capstone sequence at **Grand Canyon University** under the Bachelor of Science in Software Development program.
