# ⚡ Zepto FMCG Ads Monetization & In-App Placement Simulator

A high-impact, single-file interactive web prototype designed for **Zepto’s Retail Media Network**. Built to target the high-frequency **Summer FMCG Surge** (beverages, ice creams, hydration, and impulse snacks), this platform bridges brand growth objectives with real-time quick-commerce user intent.

---

## 📌 Table of Contents
- [Executive Overview](#-executive-overview)
- [Key Features](#-key-features)
  - [1. FMCG Merchant Self-Serve Dashboard](#1-fmcg-merchant-self-serve-dashboard)
  - [2. Live Zepto Consumer App Simulator](#2-live-zepto-consumer-app-simulator)
- [Architecture & Tech Stack](#-architecture--tech-stack)
- [Quick Start & Local Setup](#-quick-start--local-setup)
- [Deployment Guide](#-deployment-guide)
- [Product Requirement Document (PRD)](#-product-requirement-document-prd)
- [Author & Contact](#-author--contact)

---

## 🎯 Executive Overview

In quick commerce (10-minute delivery), gross margins on low-ticket orders remain tight. **In-App Retail Media Monetization** acts as the primary engine for high-margin revenue. 

This prototype solves three core operational challenges:
1. **Self-Serve Speed:** Eliminates manual offline campaign onboarding for FMCG brand partners (e.g., Sleepy Owl, Amul, Epigamia, Coca-Cola).
2. **High-Intent Touchpoint Monetization:** Moves beyond standard banners to capture high-intent moments (Sponsored Search, Cart Upsells, and Checkout Drawer Takeovers).
3. **Real-Time ROAS Attribution:** Provides FMCG brand managers with instant visibility into impressions, clicks, conversion rates, and Return on Ad Spend (ROAS).

---

## ✨ Key Features

### 1. FMCG Merchant Self-Serve Dashboard
* **Real-time Analytics:** Visual performance metrics using Chart.js displaying Impression vs. Conversion trends and Placement Breakdown.
* **Dynamic Campaign Creator:** Modal form with CPC/CPM bidding, keyword targeting, start/end dates, and real-time reach estimators.
* **Active Campaign Management:** Status toggles, budget trackers, and live keyword bid adjustments.

### 2. Live Zepto Consumer App Simulator
* **Side-by-Side Mobile Frame:** Interactive mobile interface styled with Zepto's signature design tokens (`#8B2FC9`, `#E60067`, `#12091F`).
* **Instant Keyword Search:** Real-time search engine simulation (try searching `"coffee"`, `"milk"`, or `"snack"`) that dynamically renders active sponsored products.
* **High-Intent Touchpoint Toggles:**
  * 🔍 **Sponsored Search Results:** Top-ranked paid placements with subtle `"Sponsored"` badges.
  * 🛒 **Cart Upsell Carousel:** Contextual cross-sell recommendations inside the slide-over cart drawer.
  * 💳 **Checkout Takeover Banner:** High-impact brand banners rendered at final order confirmation.
* **Interactive Cart Engine:** Real-time cart state management, running total calculations, and item additions.

---

## 🛠️ Architecture & Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend Framework** | HTML5, Modern CSS3 (CSS Grid & Flexbox) |
| **Design System** | Zepto Brand Tokens (`#8B2FC9`, `#E60067`, `#12091F`) + Inter Font |
| **Data Visualization** | [Chart.js v4.x](https://www.chartjs.org/) |
| **Icons** | FontAwesome 6.4 |
| **State Synchronization** | JavaScript ES6+ Event Engine (Zero external JS library dependencies) |

---

## 🚀 Quick Start & Local Setup

Since this application is built as an all-in-one lightweight single-file prototype, no complex build tools or `npm install` steps are required!

