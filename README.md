# PDM-Tracker

**Android application** supporting Uganda’s **Parish Development Model (PDM)**.

The app digitizes parish-level data collection, household registration, beneficiary tracking, and reporting to improve coordination between local leaders and government development programs.

## Problem
At the parish level, data is often collected manually, beneficiary tracking is difficult, transparency in fund allocation is limited, and monitoring is inconsistent.

## Solution
A mobile system that enables:
- Digital household and beneficiary registration
- Role-based access for local leaders and officers
- Tracking of PDM funds and activities
- Real-time status updates and basic reporting
- Foundation for offline support in low-connectivity areas

## Tech Stack
- **Language:** Kotlin
- **Platform:** Android
- **Architecture:** MVVM (recommended)
- **UI:** Material Design Components
- **Backend / Data:** Firebase / Room (depending on implementation stage)
- **IDE:** Android Studio

## Key Features
- User authentication and role-based access (Admin, LC1, Parish Officer, Citizen)
- Household registration with demographic data
- Beneficiary tracking and funding status
- Simple reporting dashboard
- Designed for future offline sync

## Getting Started
1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle
4. Add your `google-services.json` (if using Firebase)
5. Run on an emulator or physical device

## Project Status
Core structure and feature design are in place. Some advanced features (full offline support, advanced reporting) are planned for future iterations.

## Why this project
Built to address real grassroots development challenges in Uganda by bringing digital tools closer to local administration and citizens.
