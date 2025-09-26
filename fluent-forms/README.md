# Fluent Forms → Email Automation (Make.com) 09262025

This repository contains a **Make.com scenario blueprint** that captures Fluent Forms submissions from WordPress via webhook and sends them to your email inbox — no paid Fluent Forms extensions required.

---

## 📌 Overview

- **Trigger:** Fluent Forms Webhook (free version)
- **Action:** Send formatted email with all form submission data
- **Use Case:** Replaces Fluent Forms' built-in email notifications when using the free version

---

## 🛠 Prerequisites

- WordPress with **Fluent Forms (Free)** installed
- A [Make.com](https://www.make.com) account (free tier is fine)
- Optional: SMTP credentials (Zoho, Gmail, etc.) if you want to send email through your own mail server

---

## 🚀 Setup Instructions

### 1. Import the Scenario
1. Download the JSON file in this repository (e.g. `fluent-form-email.json`).
2. In Make.com, go to **Scenarios → Import Blueprint**.
3. Upload the JSON file.

### 2. Configure the Webhook
1. Open the imported scenario in Make.com.
2. Click the **Webhook** module → Copy the Webhook URL.
3. In WordPress, go to **Fluent Forms → Your Form → Settings & Integrations → Webhooks**.
4. Paste the webhook URL and enable it.

### 3. Test and Map Fields
1. Switch the scenario to **Listening**
