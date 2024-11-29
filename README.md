# XSS Automation Tool for 'Alert' HTB

Automates XSS for `alert.htb`. Steps:
1. Uploads a malicious file.
2. Extracts share link.
3. Sends link to exploit endpoint.
4. Captures data via HTTP listener.

## Features
- XSS payload delivery.
- Share link extraction.
- Data capture via HTTP server.

## Requirements
- Python 3.x
- Modules: `requests`, `http.server`, `socketserver`, `threading`, `sys`, `re`

## Installation
```bash
git clone https://github.com/yourusername/alert-htb-xss-tool.git
cd alert-htb-xss-tool
```

## Usage
**Important: Edit `LHOST` to your IP. **

Run with target file:
```bash
python3 exp.py <file_path>
```
Example:
```bash
python3 exp.py /etc/passwd
```

## Notes
- For educational use only. Test responsibly.

## Disclaimer
No warranty. Use at your own risk.

