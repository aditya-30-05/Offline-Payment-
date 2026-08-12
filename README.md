# OfflinePay AI 💳📶

> **Secure Offline Digital Payment System using NFC, Bluetooth, and QR Code**

## 📌 Overview

OfflinePay AI is a secure digital payment system that enables users to send and receive payments **without an internet connection**. Transactions are exchanged locally using **NFC**, **Bluetooth**, or **QR Codes** and are securely synchronized with the cloud once internet connectivity is restored.

The project aims to provide reliable digital payments in areas with poor or no network connectivity, making it suitable for rural regions, disaster recovery, underground transport systems, and remote locations.

---

## ✨ Features

* 📶 Works without internet
* 📷 QR Code Offline Payment
* 🔐 End-to-End Digital Signatures
* 💾 Encrypted Local Transaction Storage
* ☁️ Automatic Cloud Synchronization
* 🤖 AI-Based Fraud Detection
* 📊 Merchant Dashboard
* 🧾 Offline Payment Receipts

---

## 🎯 Problem Statement

Digital payment systems rely heavily on internet connectivity. During network outages or in remote areas, users cannot perform digital transactions.

OfflinePay AI provides a secure mechanism for making payments even when no internet or mobile network is available.

---

## 💡 Solution

The application creates digitally signed offline transactions that are transferred directly between devices using local communication methods.

Each transaction is:

* Digitally signed
* Timestamped
* Assigned a unique Transaction ID
* Stored securely on both devices
* Synced with the server when connectivity returns

---

## 🏗️ System Architecture

```text
Customer App
      │
      │ NFC / Bluetooth / QR
      ▼
Merchant App
      │
      │ Store Offline Transaction
      ▼
Encrypted Local Database
      │
      │ Internet Available
      ▼
Cloud Server
      │
      ▼
AI Fraud Detection
      │
      ▼
Transaction Verification & Settlement
```

---


---

## 🔄 Payment Flow

1. User enters payment amount.
2. App creates a secure transaction.
3. Transaction is digitally signed.
4. Payment is transferred using:

   * NFC
   * Bluetooth
   * QR Code
5. Merchant verifies the signature.
6. Transaction is stored locally.
7. Once online, both devices sync with the server.
8. Server verifies and settles the transaction.

---

## 🔐 Security Features

* Digital Signatures
* AES Encrypted Local Storage
* Secure Transaction IDs
* Timestamp Validation
* Duplicate Transaction Detection
* Offline Spending Limits
* Device Authentication

---

## 🤖 AI Features

* Detect duplicate transactions
* Fraud risk analysis
* Transaction anomaly detection
* Spending pattern analysis
* Merchant risk scoring

---

## 🌍 Use Cases

* Rural Banking
* Disaster Relief
* Remote Villages
* Military Communication
* Public Transport
* Large Events
* Underground Metro Stations
* Temporary Network Outages

---

## 📁 Project Structure

```text
OfflinePay-AI/
│
├── mobile-app/
├── backend/
├── ai-engine/
├── database/
├── api/
├── docs/
├── assets/
├── screenshots/
└── README.md
```

---

## 🚀 Future Scope

* Offline CBDC (Digital Rupee) Support
* Wearable Payments
* Smart Card Integration
* Multi-Currency Support
* Cross-Border Offline Transactions
* Mesh Network Payments
* Voice-Based Offline Payments
* IoT Device Payments

---

---

## 📄 License

This project is developed for educational, research, and hackathon purposes.
