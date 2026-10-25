# 🦉 OProxy

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OProxy** — Check and analyse proxy servers: anonymity, GeoIP, speed rating and multi-source fetch

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OProxy is a proxy intelligence framework. It validates single or bulk proxies, fetches free proxies from built-in sources, and classifies each by anonymity level, GeoIP location and speed. Results can be filtered and exported in multiple formats.

---

## ✨ Features

- Single and bulk proxy liveness checking
- Fetches proxies from built-in sources
- Anonymity detection and GeoIP lookup, each optionally disabled
- Speed rating with threaded checking and configurable timeouts
- Custom liveness test URL and listing of built-in sources
- Multi-format export to a chosen output directory

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OProxy --check 1.2.3.4:8080
./OProxy --bulk proxies.txt --threads 50
./OProxy --fetch --no-geo
./OProxy --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
