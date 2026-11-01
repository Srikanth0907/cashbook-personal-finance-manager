# Cashbook – Personal Finance Manager

**Your Money. Your Accounts. Your Records.**

Cashbook is a personal finance management application designed to help individuals manage multiple accounts, record income and expenses, track transfers, monitor balances and understand their financial activity through reports.

The application is planned as a lightweight, mobile-first Progressive Web App (PWA), with local data storage and offline capabilities.

## Project Overview

| Item | Details |
|---|---|
| Application Name | Cashbook – Personal Finance Manager |
| Short Name | Cashbook |
| Version | 1.0 |
| Application Type | Progressive Web App (PWA) |
| Primary Currency | Indian Rupee (INR ₹) |
| Target Devices | Mobile, Tablet and Desktop |
| Hosting | GitHub Pages |
| Database | Browser IndexedDB |
| Development Status | Planning completed; development pending |

## Key Features – Planned for V1

- Multiple account management.
- Cash In and Cash Out transactions.
- Account-to-account transfers.
- Account balance tracking.
- Transaction history, search and filters.
- Monthly calendar and daily transaction summaries.
- Daily, weekly, monthly and yearly reports.
- Category-wise income and expense analysis.
- PDF and Excel report exports.
- JSON backup and restore.
- Optional PIN protection and data encryption.
- Installable PWA with offline capabilities.
- Light and Dark themes.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | User interface and responsive design |
| JavaScript | Application functionality |
| IndexedDB | Local financial data storage |
| Service Worker | Offline application support |
| Web App Manifest | PWA installation |
| Web Crypto API | Optional encryption |
| GitHub | Source code management |
| GitHub Pages | Application hosting |

## Privacy and Data Storage

Cashbook follows a local-first architecture.

- Personal financial records are intended to remain on the user's device.
- IndexedDB will be used for local database storage.
- GitHub Pages will host application files only.
- No cloud database or mandatory registration is planned for V1.
- Users will manage their own backup files.
- Application source code must never contain personal financial records, backup files, PINs or encryption keys.

**Important:** Local browser storage is device-specific. Users should maintain regular backups to protect against browser data clearing, device loss or application removal.

## Development Approach

The project will be developed incrementally, with each module tested and validated before proceeding to the next.

Development tools and workflow:

- GitHub website for source code management.
- Browser-based editing of project files.
- GitHub Pages for deployment.
- Browser-based testing and validation.

A dedicated desktop code editor or backend server is not required for the planned V1 architecture.

## Development Roadmap

1. Project foundation and technical validation.
2. IndexedDB database architecture.
3. Accounts management.
4. Financial calculation engine.
5. Transaction management.
6. Dashboard and Calendar.
7. Reports and exports.
8. Backup and Restore.
9. Security and Settings.
10. PWA installation and offline support.
11. Final testing and V1 release.

## Project Status

**Current Stage:** Repository created; foundation and technical validation pending.

This repository is the development home for Cashbook V1.0.

---

*Cashbook – Your Money. Your Accounts. Your Records.*
