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
  * **Security**: Brute-force defense lockout and browser password manager (Google Autofill) integration.

---

## 🛠️ Technology Stack

* **Frontend**: React 18 (Standalone Compiled Bundle), Modern CSS3 / Glassmorphism
* **Backend Database**: Google Cloud Firestore (Real-Time WebSockets)
* **Hosting**: Google Firebase Hosting (Global CDN, SSL Encrypted)
* **Build Tooling**: esbuild & Node.js

---

## 🚀 Quick Setup & Deployment

```bash
# 1. Clone repository
git clone https://github.com/iam-sharath/cultural-association-ppd.git

# 2. Open project directory
cd cultural-association-ppd

# 3. Deploy updates to Firebase Hosting
npx firebase-tools deploy --only hosting
```

---

## 📜 License
Distributed under the MIT License. Developed for Cultural Association — Praneeth Pranav Daffodils.
