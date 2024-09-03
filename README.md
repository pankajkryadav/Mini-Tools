# 🛠️ xlrsec Tools

This repository is a collection of various scripts, tools, and utilities by m4ll0k and me designed for security testing and bug bounty hunting. All files are organized within the `xlrsec` directory.

## 📁 Contents

Below is a list of the tools available in this repository:

### 🔍 Reconnaissance Tools

- **Domain and Subdomain Discovery**
  - [`altdns.py`](xlrsec/altdns.py)
  - [`github-subdomains.py`](xlrsec/github-subdomains.py)
  - [`availableForPurchase.py`](xlrsec/availableForPurchase.py)

- **Cloud Services Enumeration**
  - [`awsgen.py`](xlrsec/awsgen.py)
  - [`awsgen.sh`](xlrsec/awsgen.sh)
  - [`gctexposer.py`](xlrsec/gctexposer.py)

- **Web Asset Discovery**
  - [`collector.py`](xlrsec/collector.py)
  - [`getPaths.py`](xlrsec/getPaths.py)
  - [`find-all-links.py`](xlrsec/find-all-links.py)

### 🔐 Security Testing Tools

- **Command Injection**
  - [`protoscanner.py`](xlrsec/protoscanner.py)
  - [`smbrute.py`](xlrsec/smbrute.py)

- **Cross-Site Scripting (XSS)**
  - [`jsalert.py`](xlrsec/jsalert.py)
  - [`jsmonitor.py`](xlrsec/jsmonitor.py)
  - [`jsbeautify.py`](xlrsec/jsbeautify.py)
  - [`dynamicjs.py`](xlrsec/dynamicjs.py)

- **Server-Side Request Forgery (SSRF)**
  - [`ssrf.py`](xlrsec/ssrf.py)

- **Redos Vulnerability**
  - [`checkReDOS.py`](xlrsec/checkReDOS.py)

- **Content Security Policy (CSP)**
  - [`csp-host-checker.py`](xlrsec/csp-host-checker.py)

- **Other Injection Attacks**
  - [`paramsCFinder.py`](xlrsec/paramsCFinder.py)
  - [`getjswords.py`](xlrsec/getjswords.py)
  - [`dnswfilter.py`](xlrsec/dnswfilter.py)

### 🔧 Utility Scripts

- **JSON and Data Processing**
  - [`tojson.py`](xlrsec/tojson.py)
  - [`pyText2pdf.py`](xlrsec/pyText2pdf.py)

- **Miscellaneous Tools**
  - [`bugmenot.py`](xlrsec/bugmenot.py)
  - [`favihash.py`](xlrsec/favihash.py)
  - [`shodanfy.py`](xlrsec/shodanfy.py)
  - [`jefst.py`](xlrsec/jefst.py)
  - [`wbk.go`](xlrsec/wbk.go)
  - [`waybackurls.py`](xlrsec/waybackurls.py)
  - [`waybackrobots.py`](xlrsec/waybackrobots.py)
  - [`swfpfinder.sh`](xlrsec/swfpfinder.sh)
  - [`webscreenshot.py`](xlrsec/webscreenshot.py)
  - [`webscreenshot.js`](xlrsec/webscreenshot.js)
  - [`strtool.py`](xlrsec/strtool.py)
  - [`nmap-bootstrap.xsl`](xlrsec/nmap-bootstrap.xsl)

### 🔧 Scripting and Automation

- **Shell Scripts**
  - [`aron.go`](xlrsec/aron.go)
  - [`slack.sh`](xlrsec/slack.sh)
  - [`zap-scan.py`](xlrsec/zap-scan.py)

### 📝 Reporting Tools

- [`report.py`](xlrsec/report.py)
- [`samldecoder.py`](xlrsec/samldecoder.py)
- [`samrdump.py`](xlrsec/samrdump.py)



## 📁 Repository Structure

The repository contains the following directories and scripts:

### 🔍 Reconnaissance Tools

#### **Domain and Subdomain Discovery**
- [`altdns.py`](xlrsec/altdns.py) - DNS recon tool for discovering subdomains.
- [`github-subdomains.py`](xlrsec/github-subdomains.py) - Extract subdomains from GitHub.
- [`availableForPurchase.py`](xlrsec/availableForPurchase.py) - Check domains available for purchase.

#### **Cloud Services Enumeration**
- [`awsgen.py`](xlrsec/awsgen.py) - Generate AWS credentials for testing.
- [`awsgen.sh`](xlrsec/awsgen.sh) - Shell script for AWS credential generation.
- [`gctexposer.py`](xlrsec/gctexposer.py) - Expose GCP services for enumeration.

#### **Web Asset Discovery**
- [`collector.py`](xlrsec/collector.py) - Collect URLs and web assets.
- [`getPaths.py`](xlrsec/getPaths.py) - Extract paths from web servers.
- [`find-all-links.py`](xlrsec/find-all-links.py) - Scrape and list all links from a website.

---

### 🔐 Security Testing Tools

#### **Command Injection**
- [`protoscanner.py`](xlrsec/protoscanner.py) - Scan for command injection vulnerabilities.
- [`smbrute.py`](xlrsec/smbrute.py) - Brute force SMB credentials.

#### **Cross-Site Scripting (XSS)**
- [`jsalert.py`](xlrsec/jsalert.py) - Detect XSS vulnerabilities using alert payloads.
- [`jsmonitor.py`](xlrsec/jsmonitor.py) - Monitor JavaScript files for changes.
- [`jsbeautify.py`](xlrsec/jsbeautify.py) - Beautify and analyze JavaScript code.
- [`dynamicjs.py`](xlrsec/dynamicjs.py) - Dynamic JavaScript analysis tool.

#### **Server-Side Request Forgery (SSRF)**
- [`ssrf.py`](xlrsec/ssrf.py) - Detect SSRF vulnerabilities in web applications.

#### **Regular Expression Denial of Service (ReDoS)**
- [`checkReDOS.py`](xlrsec/checkReDOS.py) - Detect vulnerabilities related to ReDoS.

#### **Content Security Policy (CSP)**
- [`csp-host-checker.py`](xlrsec/csp-host-checker.py) - Analyze and validate CSP headers.

#### **Other Injection Attacks**
- [`paramsCFinder.py`](xlrsec/paramsCFinder.py) - Find and analyze URL parameters.
- [`getjswords.py`](xlrsec/getjswords.py) - Extract sensitive words from JavaScript files.
- [`dnswfilter.py`](xlrsec/dnswfilter.py) - Filter and analyze DNS data.

---

### 🔧 Utility Scripts

#### **JSON and Data Processing**
- [`tojson.py`](xlrsec/tojson.py) - Convert data to JSON format.
- [`pyText2pdf.py`](xlrsec/pyText2pdf.py) - Convert text files to PDF documents.

#### **Miscellaneous Tools**
- [`bugmenot.py`](xlrsec/bugmenot.py) - Scrape and use BugMeNot credentials.
- [`favihash.py`](xlrsec/favihash.py) - Generate favicon hashes for reconnaissance.
- [`shodanfy.py`](xlrsec/shodanfy.py) - Automate searches on Shodan.
- [`jefst.py`](xlrsec/jefst.py) - JavaScript extraction and analysis tool.
- [`wbk.go`](xlrsec/wbk.go) - Go-based tool for extracting Wayback Machine URLs.
- [`waybackurls.py`](xlrsec/waybackurls.py) - Extract URLs from the Wayback Machine.
- [`waybackrobots.py`](xlrsec/waybackrobots.py) - Fetch and analyze robots.txt files from the Wayback Machine.
- [`swfpfinder.sh`](xlrsec/swfpfinder.sh) - Locate and analyze SWF files.
- [`webscreenshot.py`](xlrsec/webscreenshot.py) - Take screenshots of web pages using Python.
- [`webscreenshot.js`](xlrsec/webscreenshot.js) - JavaScript-based web screenshot utility.
- [`strtool.py`](xlrsec/strtool.py) - String manipulation and analysis tool.
- [`nmap-bootstrap.xsl`](xlrsec/nmap-bootstrap.xsl) - Nmap to HTML converter with Bootstrap styling.

---

### 🔧 Scripting and Automation

#### **Shell Scripts**
- [`aron.go`](xlrsec/aron.go) - Go-based automation script.
- [`slack.sh`](xlrsec/slack.sh) - Send messages to Slack channels.
- [`zap-scan.py`](xlrsec/zap-scan.py) - Automate OWASP ZAP scans using Python.

---

### 📝 Reporting Tools

- [`report.py`](xlrsec/report.py) - Generate security reports in a structured format.
- [`samldecoder.py`](xlrsec/samldecoder.py) - Decode and analyze SAML tokens.
- [`samrdump.py`](xlrsec/samrdump.py) - Extract information from SAMR services.


