# JavaScript Security Analyzer

A powerful and extensible JavaScript analysis tool designed for security researchers, bug bounty hunters, and penetration testers. This tool performs automated analysis of client-side JavaScript to uncover potential vulnerabilities, sensitive information leaks, and hidden attack surfaces.

## 🚀 Features

* **JavaScript Extraction & Analysis**

  * Crawls target websites and extracts all linked and inline JavaScript files
  * Parses and analyzes code for patterns associated with security risks

* **Vulnerability Detection**

  * Identifies common client-side issues such as:

    * Exposed API endpoints
    * Hardcoded credentials or tokens
    * Insecure DOM manipulation (e.g., XSS sinks)
    * Misconfigured or sensitive variables

* **Endpoint & Asset Discovery**

  * Extracts hidden or undocumented API routes
  * Maps potential attack surfaces from JS logic

* **Subdomain Enumeration**

  * Discovers and scans subdomains related to the target
  * Expands analysis scope automatically

* **Automated Reporting**

  * Generates structured reports with findings categorized by severity
  * Outputs results into organized files for easy review and triage

* **Terminal Insights**

  * Real-time output showing discovered endpoints, secrets, and vulnerabilities
  * Clean and readable logging for efficient workflows

## 🎯 Use Cases

* Bug bounty reconnaissance
* Web application penetration testing
* Client-side attack surface mapping
* OSINT and asset discovery

## ⚙️ Design Philosophy

Built with a focus on automation, clarity, and actionable output. This tool minimizes noise while maximizing the discovery of high-value findings.

## 📌 Future Enhancements

* Advanced taint analysis
* Integration with vulnerability scanners
* Support for authentication-based crawling
* CI/CD pipeline integration

---

> This tool is intended for educational and authorized security testing purposes only.
