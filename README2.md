# 🌐 Azure Monitor

## 🎯 Objective

This repository aims to demonstrate how to **maintain visibility**, **exercise control**, and **enable proactive response** to critical events in the **Azure Cloud environment**, such as the **deletion of a virtual machine (VM)**.

It serves as a **knowledge base** and **reference material** for professionals and students interested in cloud monitoring, governance, and incident response.

---

### ☁️ Azure Activity Logs
Track all control-plane operations (VM creation/deletion). Essential for auditing and investigations.

### 📊 Azure Monitor
Centralized platform for collecting metrics and logs across Azure resources. Supports custom alerts.

### 📈 Log Analytics
Query and analyze data from Azure Monitor using KQL (Kusto Query Language). Enables deep insights and custom dashboards.

### 🚨 Alert Rules
Trigger notifications or actions based on metrics or log queries. Crucial for early detection of critical events.

### 📬 Action Groups
Define notification settings (email, SMS, webhook, Logic App) for alerts. Enables automated responses.

---

## 💡 Use Case: VM Deletion Monitoring

### 🧭 Goal
Detect and respond when a **Virtual Machine is deleted**, ensuring the event is logged and stakeholders are notified.

### ✅ Suggested Steps
1. **Enable Activity Logs** on the subscription level.
2. **Stream logs** to a Log Analytics Workspace.
3. Create a **Log Analytics query** to detect deletion operations.
4. Configure an **Alert Rule** based on the query.
5. Link an **Action Group** to send email/Teams/Logic App notifications.

---

