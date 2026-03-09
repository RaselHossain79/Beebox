# 🐝 bee-box (bWAPP) Learning Roadmap
> Structured Web Application Penetration Testing Practice

This repository documents my **hands-on web pentesting journey** using **bee-box (bWAPP)**.
The goal is to build **real pentester thinking**, not just tool usage.

---

## 🎯 Objective
- Learn web vulnerabilities in a **structured, OWASP-based way**
- Practice **manual exploitation first**
- Develop **analysis + documentation skills**
- Prepare for real-world pentesting labs (THM / HTB)

---

## 🧠 Core Methodology
For **every vulnerability**, I strictly follow this cycle:




# Learn → Observe → Exploit → Analyze → Document

This methodology ensures **understanding over memorization**.

---

## 🧱 Phase 0 — Lab Setup & Environment

### 🔹 Tools
- Attacker Machine: Kali Linux
- Target VM: bee-box (bWAPP)
- Browser: Firefox
- Proxy: Burp Suite

### 🔹 Checklist
- [ ] Find bee-box IP
- [ ] Access bWAPP login page
- [ ] Login with default credentials
- [ ] Open terminal & browser comfortably

⚠️ No exploitation before environment confidence.

---

## 🧩 Phase 1 — Vulnerability Learning Structure

All vulnerabilities are practiced according to **OWASP Top 10** mindset.

### 🔐 Recommended Order
1. Injection  
   - SQL Injection (GET / POST)
   - Command Injection
2. Broken Authentication
3. Sensitive Data Exposure
4. XML External Entity (XXE)
5. Broken Access Control
6. Security Misconfiguration
7. Cross-Site Scripting (XSS)
   - Reflected
   - Stored
   - DOM-based
8. Insecure Deserialization
9. Using Vulnerable Components
10. Insufficient Logging & Monitoring

---

## 🧪 Phase 2 — Practice Template (USE FOR EVERY VULNERABILITY)

### 🧠 1. Learn (Theory)
- What is the vulnerability?
- Why does it occur?
- What is the real-world impact?

---

### 👀 2. Observe (Inside bWAPP)
- Input type (GET / POST / Header / Cookie)
- Where does user input go?
- Any filtering or validation?

> Observation is more important than payloads.

---

### 💥 3. Exploit (Manual First)
- Try manual payloads
- Modify parameters
- Use Burp Repeater if needed

Example: ' OR 1=1 -- ; ls


❌ Avoid blind copy-paste  
✅ Understand why it works

---

### 🔍 4. Analyze
- Why did the exploit succeed?
- What security control was missing?
- How would a developer fix this?

Think like **attacker + defender**.

---

### 📝 5. Document
For every vuln, record:
- Vulnerability Name
- Affected Page / Parameter
- Payload Used
- Result / Impact
- Recommended Fix

---

## ⏱️ Daily Practice Routine

✅ Even **1 vulnerability/day** is excellent progress.

---

## 🛠️ Tools Usage Rule
- Manual testing first
- Tools second
- Automation last

Tools to use gradually:
- Browser DevTools
- Burp Suite
- curl
- sqlmap (after understanding)
- Metasploit (only when relevant)

---

## ❌ Common Mistakes to Avoid
- ❌ Chasing reverse shells too early
- ❌ Depending fully on tools
- ❌ Skipping documentation
- ❌ Random vulnerability jumping

---

## 🔁 Phase 4 — After bee-box
Once confident:
- Move to TryHackMe (guided)
- Then Hack The Box (realistic)
- Revisit bee-box for revision

bee-box = **foundation lab**

---

## 🧠 Pentester Mindset Notes
- Payloads are tools, **logic is the weapon**
- Observation > Exploitation
- Notes today = confidence tomorrow
- Think: *“Why does this exist?”*

---

## 📌 Status Tracker
- [ ] SQL Injection
- [ ] Command Injection
- [ ] XSS
- [ ] Authentication Issues
- [ ] Access Control

---

## 🚀 Goal
Become a **thinking web pentester**, not a script runner.
