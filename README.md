# 🟢 Ad Allowlist

> A privacy-conscious allowlist to support ethical and non-intrusive advertising on the open web.

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)
![Built With](https://img.shields.io/badge/Built%20With-Markdown-blue)

---

## 🌟 Overview

The **Ad Allowlist** is a curated list of ad domains that support:

This project enables ad-blocking users to selectively support responsible ads without compromising their values or user experience.

---

## 📋 Features

- ✅ Curated and manually reviewed domain list
- 🔍 Focus on non-tracking, contextual, and ethical ad networks
- 💡 Easy integration with uBlock Origin, Pi-hole, AdGuard, etc.
- 🛡️ Minimal impact on page load and privacy

---

## 📦 Supported Ad Networks (Examples)

| Provider        | Type             | Notes                                     |
|-----------------|------------------|-------------------------------------------|
| Carbon Ads      | Contextual       | Clean, minimal, and privacy-respecting    |
| EthicalAds      | Developer Focus  | Open source and GDPR-compliant            |
| BuySellAds      | Banner/Text Ads  | Used by tech blogs and indie developers   |

> 📝 Full list in [`allowlist.txt`](./allowlist.txt)

---

## 🚀 Getting Started

### With uBlock Origin

1. Go to **Dashboard > Filter Lists > Custom**.
2. Paste the raw URL of `allowlist.txt`.
3. Click **Apply Changes**.

### With Pi-hole

1. Add the raw URL to your Pi-hole’s adlists.
2. Update gravity:  
   ```bash
   pihole -g
