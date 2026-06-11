# Automated Credit Risk Assessment & Application Workflow

An end-to-end automated pipeline built with power bi dash board that trains a predictive risk model, ingests financial application data from **Google Sheets**, evaluates applicants through multi-tiered conditional logic, and sends automated decision notifications via **Gmail**.

---

## 🚀 System Architecture & Workflow

The entire automation engine is driven by an asynchronous node-based workflow in n8n. It processes batch applications sequentially, passing them through structured evaluation matrices (`IF` filters) to arrive at three primary states: **Auto-Approve**, **Manual Review**, or **Auto-Reject**.

### Workflow Visual Map
<img src="./Screenshot (31).png" alt="Power BI Credit Risk Analytics Dashboard" width="100%"/>



