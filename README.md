# 🛡️ Dynamic & Static Malware Analysis Report

A comprehensive security analysis portal and interactive demonstration designed for malware triage, dynamic execution inspection, and static indicator verification.

---

## 📋 Overview

This repository contains a full-featured, secure, web-based dashboard designed to document dynamic and static malware analysis tasks. Built using Tailwind CSS and vanilla JavaScript, it simulates an authenticated security portal equipped with a Matrix-style hacker animation, interactive task cards, dynamic execution details, and a VirusTotal threat intelligence search utility.

### 👤 Lead Analyst Profile
* **Analyst Name:** Pratik Ingale
* **Certifications:** Certified Ethical Hacker (CEH) | Computer Hacking Forensic Investigator (CHFI)
* **Rank / Distinction:** TryHackMe Top 2%

---

## ⚡ Key Features

* **🔐 Authenticated Access Modal:** Simulated credential validation system storing session auth state.
* **🌐 Dynamic Sandbox Integration:** Direct interface for sandbox analysis execution logs via [ANY.RUN](https://any.run/).
* **🔍 Static Hash Extraction Workflow:** Step-by-step workflow covering file hashes, suspicious payload identification, and threat intel lookup.
* **🛠️ Integrated VirusTotal Search Tool:** Built-in hash query tool that redirects directly to VirusTotal search results for fast static verification.
* **💻 Matrix Hacker UI & Animations:** Custom canvas/text scrambling animation engine for active security state feedback.

---

## 📂 File Structure & Analysis Context

### Target Sample Metadata

| Parameter | Details |
| :--- | :--- |
| **Target File** | `phishing and malware analysis` |
| **Sample Payload** | `Payment-updated.pdf` |
| **Analysis Status** | `Infected` |
| **Access Note** | `Password Protected` |

### Sandbox Execution Tasks (Dynamic Analysis)

1. **Task 1:** `8bfd4c58-ec0d-4371-bfeb-52a334b69f59`
   * Link: [https://app.any.run/tasks/8bfd4c58-ec0d-4371-bfeb-52a334b69f59](https://app.any.run/tasks/8bfd4c58-ec0d-4371-bfeb-52a334b69f59)
2. **Task 2:** `82d8adc9-38a0-4f0e-a160-48a5e09a6e83`
   * Link: [https://app.any.run/tasks/82d8adc9-38a0-4f0e-a160-48a5e09a6e83](https://app.any.run/tasks/82d8adc9-38a0-4f0e-a160-48a5e09a6e83)

---

## 📖 Analysis Workflow & Tutorial

1. **Launch Sandbox Environment:**
   Click **Open Task** on any task card within the report dashboard to launch the interactive sandbox environment.
2. **Inspect Dynamic Execution:**
   Observe interactive process trees, network DNS/HTTP traffic, and extracted secondary file payloads (e.g., `Payment-updated.pdf`).
3. **Extract Static Checksums:**
   Copy the `MD5` or `SHA-256` static file hash from the sandbox indicators or main task panel.
4. **Threat Intelligence Query:**
   Paste the hash into the VirusTotal Search bar on the portal or query directly on [VirusTotal Search](https://www.virustotal.com/gui/home/search) to complete the static analysis cross-check.

---

## 🚀 How to Run Locally

1. **Open the File:**
   Double-click `index.html` to open it directly in any modern web browser, or launch it using VS Code Live Server.

2. **Portal Authentication Credentials:**
   * **Username:** `pratik`
   * **Password:** `pratik_38`

---

<p align="center">
  <i>Restricted Security Report — Authorized Personnel Only</i>
</p>
