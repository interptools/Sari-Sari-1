# Sari-Sari-1 POS

> Point of Sale system built with **Arroyo POS Engine** (MyStore POS)

## 🌐 Live App

**https://interptools.github.io/sari-sari-1/**

## 📱 Install as App

1. Open **https://interptools.github.io/sari-sari-1/** in Chrome (Android) or Safari (iPhone)
2. Tap **⋮ menu** → **Add to Home Screen**
3. Tap **Add** — your POS opens full screen like a native app

## 🔑 Sign in

Staff accounts were configured when this build was generated. PINs are
stored hashed and are **not** listed here on purpose — this repository is
public, and anything written in it can be read by anyone.

> On first launch the app will prompt the manager to set fresh PINs.
> Do that before taking any real money.

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The POS application |
| `manifest.json` | PWA manifest (fullscreen, icon, name) |
| `sw.js` | Service worker (offline + installable) — **not in this ZIP**, see Step B in the deployer's own instructions to add it by hand |
| `dashboard/index.html` | Owner Dashboard — see below |
| `icon-192.png` | App icon 192×192 |
| `icon-512.png` | App icon 512×512 |

## ⚡ Built with

[Arroyo POS Engine](https://github.com/reymar-arroyo) — MyStore POS Deployer

---
*Generated October 13, 2026*

## Connect this till to sync

1. Open the app, go to **Settings → Multi-terminal sync**.
2. Tap **Register this terminal** and enter an email, a password you choose, and the setup code from the SQL setup step.
3. Already registered a login for this store before? Use **Sign in** instead, with that same email and password.


## Owner Dashboard

Open **https://interptools.github.io/sari-sari-1/dashboard/** and sign in — the login from the Owner login section in the builder was already created by the SQL file, so there's nothing to register.
