# HTTPS-Access-Failure-Analysis

### 🛡️ Cybersecurity-Incident-Report: HTTPS Access Failure Analysis

This project presents a real-world cybersecurity incident response scenario focused on diagnosing issues related to **HTTPS traffic failure**. The incident involves a security team investigating an error accessing a background check web portal, which was unreachable on **port 443**, commonly used for secure web communication.

The report highlights how **network protocol analysis tools** like `tcpdump` are used to detect connectivity failures and how such incidents are addressed through layered investigation, firewall inspection, and system-level forensics.

---

## 🧾 Project Overview

The project is divided into two key components:

---

### 🔍 Incident Summary

- The **Human Resources (HR) team** reported that they were unable to access the **secure background check portal**.
- Initial testing revealed that **port 443 was unreachable**, preventing HTTPS access.
- This suggested either a **misconfiguration in the firewall** or a **potential attack** on the web server.

---

### 🛠️ Investigation & Findings

- The network security team used `tcpdump` to analyze network traffic.
- Logs confirmed that **port 443** (HTTPS) was not responsive.
- Further investigation targeted the **firewall settings** and **web server integrity**.
- Suspicion arose that a **disgruntled new hire** might have deliberately attacked the server to avoid a background check.
- The team continued monitoring logs and coordinating with system administrators to rule out malicious activity and restore functionality.

---

## 📄 Files Included

- `Example of a Cybersecurity Incident Report.docx` — Full technical report with incident context, logs, and recommendations  
- `README.md` — This project overview and documentation

---

## 🚀 How to Use This Project

1. Open the `.docx` report to explore the full incident breakdown.
2. Use it as a **case study** for learning about HTTPS issues and port analysis.
3. Refer to the structure and methodology when writing your own **incident response documentation**.

---

## 🎓 Learning Outcomes

By reviewing this project, you will:

- Understand how **HTTPS (port 443)** traffic failures can impact web-based services.
- Learn how to use `tcpdump` to analyze secure web traffic connectivity.
- Identify the steps in **incident response and investigation** involving suspected web server attacks.
- Practice **critical thinking** when evaluating both technical and behavioral factors (such as insider threats).

---

## 🧰 Tools Used

- `tcpdump` (for packet capture and traffic analysis)
- Web browser (used to simulate user traffic and detect response failure)
- Firewall and server logs (used during root cause analysis)

---

## 📌 Notes

This report was developed for **academic and training purposes** as part of a cybersecurity practical assignment. It serves as a realistic example of how web access issues are diagnosed and addressed using **layered network analysis techniques**.
