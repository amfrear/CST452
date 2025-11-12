# Medical Journey Log – Milestone 5
**Grand Canyon University – CST-452: Software Development Capstone II**  
**Author:** Alex Frear  
**Date:** November 2025

## Project Overview
Medical Journey Log is a caregiver-focused application that helps families document medical information, symptoms, and daily health updates for their children.  
This folder represents the final iteration (Iteration 3) focusing on testing, verification, and documentation.

**Key functionality**
- Add, edit, and delete Children
- Add, edit, and delete Symptoms (per child)
- View child details with symptom history
- Server-side validation on all forms
- Local data storage with MySQL + EF Core

> Note: Authentication is intentionally out of scope for this prototype because it is designed for private, single-user caregiver use.

## Milestone 5 Focus
**Iteration 3 Goals**
- Regression testing of all CRUD modules
- UI/content polish
- Final documentation + screencast

**Results**
- All unit, integration, and system tests passed
- 100% of planned functionality implemented and verified

## Tech Stack
- .NET 7 / ASP.NET Core Razor Pages
- C#  
- Entity Framework Core (Pomelo MySQL Provider)  
- MySQL (MAMP)  
- Bootstrap 5

## Project Structure
    MedicalJourneyLog/
      Data/                    # EF Core context (ApplicationDbContext.cs)
      Models/                  # Child, Symptom (future: Caregiver, Notes, Milestones)
      Pages/                   # Razor Pages for CRUD
      wwwroot/                 # Static assets
      appsettings.json         # Config / connection string (dev)
      Program.cs               # Entry point

## Milestone 5 Deliverables
- Updated Implementation Plan (Iteration 3)
- Final Requirements Traceability Matrix
- Regression Test Results (Unit, Integration, System)
- Source Code Listing
- Final Screencast Video
- Milestone 5 Submission Document (PDF)


## Repository Notes
This folder contains the finalized app and submission artifacts for Milestone 5.  
Earlier iterations are available in their respective milestone folders for version tracking.

## Future Enhancements
- Caregiver authentication (ASP.NET Identity)
- Shared access between multiple caregivers
- Notes and Milestones entities with CRUD
- Cloud deployment (e.g., Azure App Service + managed MySQL)

## License / Academic Use
Developed for **GCU CST-452**. Intended for academic evaluation and demonstration.
