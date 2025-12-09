# Future Interns - Cybersecurity Internship 

This repository contains my project submissions for the **Cybersecurity Internship** at Future Interns.

## 📂 Repository Structure

| Task | Project Name | Description | Status |
| :--- | :--- | :--- | :--- |
| **Task 1** | Web Application Security Testing | Vulnerability assessment of OWASP Juice Shop (SQLi, XSS, Sensitive Data Exposure). | Completed |
| **Task 2** | *Coming Soon* | *Pending* | ⏳ |
| **Task 3** | *Coming Soon* | *Pending* | ⏳ |

---

## Task 1: Web Application Security Testing

**Objective:** Perform a vulnerability assessment on a vulnerable web application (**OWASP Juice Shop**) to identify security flaws using ethical hacking tools.

### Tools Used
* **Burp Suite Community Edition** (Traffic Analysis & Interception)
* **Docker** (Hosting the local Juice Shop instance)
* **Chromium** (Manual Testing)

### 🔍 Key Findings
I successfully identified and documented the following vulnerabilities:
1.  **SQL Injection (SQLi):** Bypassed authentication to log in as Administrator.
    * *Payload:* `' OR 1=1 --`
2.  **Cross-Site Scripting (DOM XSS):** Executed arbitrary JavaScript via the search bar.
    * *Payload:* `<iframe src="javascript:alert('xss')">`
3.  **Sensitive Data Exposure:** Uncovered hidden access to the Score Board.
    * *Endpoint:* `/#/score-board`

### Deliverables
* [View Security Assessment Report (PDF)](./Task1_Security_Report.pdf)

---

###  Author
**Rathnam S.**
*Aspiring Cybersecurity Analyst*
