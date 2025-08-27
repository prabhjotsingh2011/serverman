# serverman 🖥️

A simple CLI tool to manage and connect to multiple SSH servers (AWS, VPS, etc.) with short aliases.

## 🚀 Installation

### 1. Install dependencies
`serverman` needs `jq` (for JSON parsing) and optionally `sshpass` (for password-based logins).  

**Debian/Ubuntu**
```bash
sudo apt-get update
sudo apt-get install -y jq sshpass
Run this one-liner:

```bash
curl -fsSL https://raw.githubusercontent.com/prabhjotsingh2011/serverman/main/serverman -o /usr/local/bin/serverman
chmod +x /usr/local/bin/serverman
