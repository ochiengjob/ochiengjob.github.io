---
title: Lab Challenges
icon: fas fa-flask
order: 4
---

<style>
/* ===== Inline Style Fix for Dark Mode Visibility ===== */

/* General text contrast */
[data-theme="dark"] .content {
  color: #eaeaea !important;
}

/* Code and preformatted text */
[data-theme="dark"] pre,
[data-theme="dark"] code {
  background-color: #1e1e1e !important;
  color: #e0e0e0 !important;
  border-radius: 6px;
  border: 1px solid #333;
}

/* Tables */
[data-theme="dark"] table {
  border: 1px solid #444;
}
[data-theme="dark"] th,
[data-theme="dark"] td {
  border: 1px solid #555;
  padding: 8px;
}

/* Images */
[data-theme="dark"] img {
  background-color: #fff;
  border-radius: 8px;
  padding: 4px;
}

/* Blockquotes (problem statements, lessons learned, etc.) */
[data-theme="dark"] blockquote {
  background-color: #2a2a2a;
  border-left: 4px solid #4fc3f7;
  color: #ddd;
  padding: 12px 18px;
  border-radius: 6px;
  margin: 15px 0;
}

/* Lab challenge cards */
.lab-card {
  background-color: #f8f9fa;
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 15px 20px;
  margin-bottom: 20px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease-in-out;
}

.lab-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

[data-theme="dark"] .lab-card {
  background-color: #1e1e1e;
  border: 1px solid #333;
  color: #eaeaea;
}
</style>

# 🧪 Lab Challenges

Explore some of my completed lab challenges from cybersecurity and AI trainings — each one documents the **problem**, **approach**, **tools**, and **key lessons learned**.

---

<div class="lab-card">

### 🔍 Network Traffic Analysis
**Problem:** Detect and analyze suspicious activity in a captured network file.  
**Approach:** Used Wireshark and Zeek to inspect packet behavior, identify anomalies, and extract IoCs (Indicators of Compromise).  
**Tools:** Kali Linux, Wireshark, Zeek  
**Key Lessons:** Understanding packet-level communication patterns is crucial for detecting hidden data exfiltration.

</div>

---

<div class="lab-card">

### 🧠 Machine Learning for Malware Detection
**Problem:** Classify unknown binaries as benign or malicious using machine learning.  
**Approach:** Extracted opcode and API call features, trained multiple classifiers, and evaluated accuracy.  
**Tools:** Python, Scikit-learn, Pandas  
**Key Lessons:** Feature selection dramatically impacts accuracy; Random Forest performed best on imbalanced datasets.

</div>

---

<div class="lab-card">

### 🕵️‍♂️ Web Exploitation CTF Challenge
**Problem:** Exploit a vulnerable PHP application to retrieve hidden credentials.  
**Approach:** Performed manual testing and SQL injection to gain backend access.  
**Tools:** Burp Suite, SQLmap, Kali Linux  
**Key Lessons:** Even simple misconfigurations in form inputs can lead to critical data exposure.

</div>
