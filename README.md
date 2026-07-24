# AI-Powered Smart Laboratory Equipment Borrowing System with RFID Integration

## Problem Statement
Traditional laboratory equipment borrowing processes can be overwhelming, unorganized, and prone to missing items. Students often struggle to identify all necessary components for an activity, while technicians face difficulties tracking real-time inventory, overdue items, and partial returns.

## Target Users and Stakeholder Value
* **Target Users:** Engineering/Science Students and Laboratory Technicians.
* **Stakeholder Value:** Provides a clean, role-based, progressive disclosure interface that prevents cognitive overload. It ensures accurate real-time inventory tracking, secures transactions via ESP32/RFID hardware authentication, and features a proactive rule-based AI that automatically recommends complementary equipment (e.g., breadboards and jumper wires for microcontrollers) to streamline the checkout process.

## Team Members and Roles
* **Product Owner:** Cardenas, Mia Gabrielle C.
* **Scrum Master:** Aclan, Althea Denise P.
* **Lead Dev (Full Stack):** Santilices, Rea Joy I.
* **Lead Dev (IoT/Hardware):** Napiza, Emmanuel Joseph B.
* **QA / DevOps:** Adarayan, Alvin James

## Planned Technology Stack
* **Frontend:** [e.g., React, HTML/CSS]
* **Backend:** Node.js
* **Database:** MongoDB Atlas
* **Hardware/Embedded:** ESP32, RFID Reader, Wokwi

## Repository Structure
* `/frontend`: User interface, student dashboard, and admin dashboard.
* `/backend`: API, inventory logic, and rule-based AI recommendation engine.
* `/embedded`: ESP32 and RFID hardware integration scripts.
* `/docs`: Project documentation, Sprint 0 reports, and traceability records.

## Branching and Pull-Request Rules
* All feature work must branch from `develop`.
* Branch format: `feature/<CLICKUP-key>-<short-description>` or `bugfix/<CLICKUP-key>-<short-description>`.
* Commit format: `<CLICKUP-key> <imperative description>`.
* Pull requests must target the `develop` branch.
* At least one approving review from a peer is required before merging.

## Setup Instructions
1. Clone the repository: `git clone [repository-url]`
2. Navigate to the project directory: `cd cpsoft1l-smart-environment-[teamname]`
3. Copy `.env.example` to a new `.env` file and insert necessary database and hardware connection variables.
4. Run `npm install` in the backend and frontend directories.
5. Start the development server using `npm start`.

## Security and AI Disclosure

### AI Tools Usage Disclosure
- **AI Tools Used:** ChatGPT (OpenAI) and Gemini (Google AI)
- **Specific Parts Used:** 
  - **ChatGPT:** Utilized to verify, outline, and structure the core user interface workflow and system navigation logic (as suggested by the Product Owner).
  - **Gemini:** Assisted the developer in troubleshooting Git version control workflows, specifically resolving VS Code staging errors, formatting strict commit messages, and safely navigating GitHub Pull Request updates to align with the team's Git Etiquette.
- **Student Responsibility:** All technical configurations, hardware integrations (ESP32 and RFID), documentation layouts, and final verifications were personally reviewed, executed, and approved by the student developer (Adarayan, Alvin James).