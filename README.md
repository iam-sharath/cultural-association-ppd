# 🏛️ Cultural Association — Praneeth Pranav Daffodils Financial Portal

A high-performance, real-time community financial accounting portal and festival ledger built for **Praneeth Pranav Daffodils (PPD)**. Features double-entry treasury management, strict 230-flat directory validation, dual-layer cloud synchronization, and automated audit reporting.

🌐 **Live Production URL**: [https://cultural-association-ppd.web.app](https://cultural-association-ppd.web.app)

---

## 🌟 Key Features

* **⚡ Live Double-Entry Treasury Ledger**: Real-time balance calculation (`Balance = Total Inflow - Total Outflow`) with live surplus ratio tracking.
* **🏢 Strict 230-Flat Validation**: Validates resident contributions across Blocks A (70 flats), B (70 flats), and C (90 flats) to prevent erroneous or duplicate entries.
* **🌟 Segregated Sponsorship Inflows**: Tracks external donors and business sponsors separately with custom tags (e.g., *Annadanam Sponsor*, *Lighting Sponsor*).
* **☁️ Dual-Layer Cloud Architecture**: 0ms instant startup via local device storage with background real-time Google Cloud Firestore synchronization.
* **📱 Tier-1 Mobile First Experience**: Apple Wallet style treasury card, iOS 18 bottom sheets, and wheel-scroll protected numeric inputs.
* **📄 Audit Reports & Exports**: 1-click generation of official PDF financial audit statements, complete CSV spreadsheets (UTF-8 BOM), and formatted WhatsApp community bulletins.
* **🔒 Enterprise Role-Based Access Control**:
  * **Admin**: Full control, delete/edit rights, multi-year festival management, custom categories.
  * **Cashier**: High-speed gate entry mode (add collections/expenses only).
  * **Security**: Official Google Cloud Authentication (JWT tokens, zero passwords in code), brute-force defense lockout, and browser password manager (Google Autofill) integration.

---

## 🛠️ Technology Stack

* **Frontend**: React 18 (Standalone Compiled Bundle), Modern CSS3 / Glassmorphism
* **Cloud Authentication**: Google Firebase Authentication (Signed Cloud JWT Tokens)
* **Backend Database**: Google Cloud Firestore (Real-Time WebSockets & Offline Cache)
* **Hosting**: Google Firebase Hosting (Global CDN, SSL Encrypted)
* **Build Tooling**: esbuild & Node.js
* **Testing & QA**: Puppeteer (Headless Chromium E2E Automation)


## 📜 Ownership & License
© 2026 Cultural Association — Praneeth Pranav Daffodils. All Rights Reserved.  
Proprietary software developed for the official administration of Praneeth Pranav Daffodils Community.
