# Loan-Application-Status-Tracker
# 🏦 Loan Application Status Tracker

A modern low-code app built with Microsoft Power Platform to track, submit, and monitor loan applications securely using SharePoint, Power Automate, and Azure DevOps.

---

## 🚀 Features
- 📋 Power Apps form to submit loan applications
- 🛡️ Azure AD login + audit logs with Application ID and timestamp
- 📧 Auto email notifications using Power Automate
- 📊 Power BI analytics for loan status & type (Windows only)
- 📁 SharePoint list backend with permission controls
- 📌 Agile tracking with Azure DevOps board

---

## 🛠️ Tech Stack

| Tool               | Purpose                    |
|--------------------|----------------------------|
| Power Apps         | UI form + logic (low-code) |
| SharePoint         | Data source (LoanApplications) |
| Power Automate     | Trigger + email flow       |
| Power BI (Windows) | Dashboard visualizations   |
| Azure DevOps       | Agile user stories & board |
| GitHub             | Documentation repository   |

---

## 📸 Screenshots

| Power Apps UI | SharePoint List | Azure DevOps Board |
|---------------|-----------------|---------------------|
| ![Form](screenshots/powerapps_ui.png) | ![List](screenshots/sharepoint_list.png) | ![Board](screenshots/devops_board.png) |

---

## 🎓 Learning Highlights

- Used `Patch()` and `Set()` functions in Power Fx
- Implemented automated emails for workflow triggers
- Created audit logging for admin tracking
- Practiced Agile task breakdown and DevOps usage
- (Optional) Connected Power BI to SharePoint for analytics

---

## 📹 Demo

demo_video.mp4



## 📁 Folder Structure

```bash
Loan-Application-Status-Tracker/
├── README.md
├── AGILE.md
├── /screenshots/
├── /flows/
├── /docs/
└── demo_video.mp4
