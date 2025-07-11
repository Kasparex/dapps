---
icon: bullseye-arrow
---

# Quickstart



### 🧭 Documentation Structure v1

#### 1. 🏠 Welcome

* **Introduction to Kasparex Docs**
* Vision & Mission
* How to Use This Documentation

#### 2. 🚀 Getting Started

* What is Kasparex?
* Core Concepts: KRC-20, dApps, Smart Contracts, NFTs
* Supported Wallets
* How to Connect Your Wallet

***

#### 3. 🧱 Kasparex Architecture

* Kasparex Global UI (kasparex-style.css)
* Modular System Overview (kasparex-modules.js)
* Init Scripts (kasparex-init.js)
* Embeddable Widget System
* Server Setup (server.js explained)

***

#### 4. ⚙️ Developer Setup

* Local Development Guide
* File Structure Overview
* Hosting dApps via GitHub + Velo (Wix)
* Embedding on Third-Party Sites
* Deployment Checklist

***

#### 5. 🧩 Core Modules

* Wallet Module
* Theme Switcher
* Token Selector
* Fee Handler
* Guide Popup
* Dashboard Modal
* Code Copy / Embed Generator
* Common UI Utilities

***

#### 6. 🎨 Global UI Kit

* Buttons, Pills, Tags, Inputs
* Panels, Cards, Tables
* Alerts (Light + Dark)
* Loaders & Progress Bars
* Nav Pills, Tabs
* Modal Styling
* Responsive Layout Guide

***

#### 7. 📄 Templates & Snippets

* `dapp-template.html` Walkthrough
* `kasparex-ui-showcase.html` Showcase Reference
* Quick Embed HTML Example
* Sample dApp Layout

***

#### 8. 📦 dApp Templates

Each dApp has its own page under this section.

**Template Format for Each dApp:**

## 📦 \[dApp Name]

### ✅ What It Does

Short summary of the purpose and utility of the dApp.

### ⚙️ How It Works

Explain:

* Smart contract logic (if any)
* JS behavior
* Wallet interactions
* Fee handling logic (if applicable)

### 📦 Files Used

* HTML: `...`
* Modules: `...`
* Smart contract (optional): `...`

### 🎁 Benefits

Why it's useful for users and token projects.

### 🔧 Customization

How to modify UI, add supported tokens, adjust fees, etc.

### 🔗 Embed Example

```html
<iframe src="..." width="..." height="..." />
```

### 🔧 What’s Inside:

* `public/index.html` – Fully styled embeddable dApp widget
* `contracts/main.contract.kas` – Kaspa smart contract logic
* `docs/integration.md` – Steps to list your dApp
* `preview.png` – Banner image for listing

### 🚀 How to Use:

1. Customize the UI in `index.html`
2. Write or edit your Kaspa smart contract in `/contracts`
3. Test it in your Kasparex Dev Group (see `/docs`)
4. Submit using the `/submit-dapp` panel on Kasparex

### 💬 Support

Join the [Kasparex Dev Group](https://kasparex.com/groups/dev-tools) to get help or feedback.

### 📜 License

MIT – build freely and submit to Kasparex with your own branding. 🎛️ 2. Preview Dashboard Card for Kasparex dApp Listings (App Store–style display card, clean and embeddable)

💻 Embed-Ready HTML Code: html Copy Edit

![dApp preview](\[PreviewImageURL])

#### 🧩 \[dAppName]

\[Short one-line description of the dApp]

\#Kaspa #KRC20 #Utility

[🌐 Visit Dev Group](\[DevGroupLink]/) [👁️ Preview Widget](\[WidgetPreviewURL]/)

🔁 Replace placeholders: \[dAppName] – your app name

\[Short one-line description of the dApp] – a short use-case

\[PreviewImageURL] – link to banner/screenshot

\[DevGroupLink] – your Dev Group URL

\[WidgetPreviewURL] – preview page or working demo

You can embed multiple of these cards in a responsive flex layout on /explore-dapps.
