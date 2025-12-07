

# **Qubic Live Analytics Dashboard**

Production ready real time analytics platform for the Qubic blockchain

**Features • Demo • Installation • EasyConnect • Dashboard**



## 🎯 Overview

Qubic Live Analytics Dashboard is a real time web based monitoring platform built for the Qubic ecosystem. It provides a clear live view of token prices, recent on chain transactions, and whale movements using EasyConnect automation and Google Sheets as the data layer.

The goal of this project is to make Qubic blockchain activity easy to understand for traders, communities, and builders through a clean and visual dashboard without requiring complex tools.



## ✅ Key Highlights

✅ Live Token Prices – Real time tracking of selected Qubic tokens
✅ Recent Transactions – Continuous feed of latest on chain activity
✅ Whale Tracker – Dedicated section for large transfers
✅ EasyConnect Integration – Automated workflows using Make Zapier and n8n
✅ No Backend Required – Powered by Google Sheets as a live data source
✅ Responsive UI – Works on desktop, tablet, and mobile


## ✨ Features

### 📊 Core Dashboard

* Live price table for selected Qubic tokens
* Recent transaction feed with time, token, amount, from and to wallets
* Whale transaction table showing only large transfers above a set threshold
* Network snapshot cards for quick statistics
* Last refresh indicator for live activity

### 🔔 Monitoring & Insights

* Live market movement awareness
* Whale activity detection
* Large transfer visibility for community and traders
* Simple readable wallet address formatting

### ⚙ Automation & Data Flow

* EasyConnect workflows for:

  * Token price updates
  * Transaction event tracking
  * Whale transaction filtering
* Automatic sync to Google Sheets
* Instant reflection on website without server code



## 🏗️ Architecture

```
┌──────────────────────────────────────────────┐
│            Frontend (HTML, CSS, JS)          │
│   Live Prices │ Transactions │ Whale Data   │
└──────────────────────────────────────────────┘
                           ↓
┌──────────────────────────────────────────────┐
│            Google Sheets (Data Layer)        │
│ Prices │ Recent Transactions │ Whale Data   │
└──────────────────────────────────────────────┘
                           ↓
┌──────────────────────────────────────────────┐
│         EasyConnect Automation Engine        │
│   Price Feed │ Tx Events │ Whale Filters    │
└──────────────────────────────────────────────┘
                           ↓
┌──────────────────────────────────────────────┐
│                Qubic Blockchain              │
│        Market Data │ On Chain Activity      │
└──────────────────────────────────────────────┘
```



## 🛠️ Tech Stack

* Blockchain: Qubic Network
* Automation: EasyConnect
* Data Storage: Google Sheets
* Frontend: HTML, CSS, JavaScript
* Hosting: GitHub Pages or any static host



## 📦 Quick Start

```bash
# Clone the repository
git clone <your-repository-url>

# Open the project folder
cd qubic-live-analytics

# Open the dashboard
Open index.html in your browser
```

### Enable Live Data

1. Create three Google Sheet tabs:

   * Token_Prices
   * Recent_Transactions
   * Whale_Transactions

2. Connect EasyConnect:

   * Map Qubic price events to Token_Prices
   * Map Qubic transactions to Recent_Transactions
   * Add filter for whale threshold and map to Whale_Transactions

3. Embed your Google Sheet tabs into the website using iframe or dynamic JS.


## 🚀 Key Features Implemented

### 1. Live Price Monitoring

✅ Token wise real time price display
✅ 24 hour change indicator
✅ Automatic refresh from EasyConnect feed

### 2. Recent Transaction Feed

✅ Live transfer tracking
✅ Wallet summary formatting
✅ High activity monitoring

### 3. Whale Tracking System

✅ Large transfer filtering
✅ Dedicated whale table
✅ Threshold based detection

### 4. Automated Data Sync

✅ EasyConnect price sync
✅ EasyConnect transaction sync
✅ Google Sheets based storage



## 🎮 Demo Mode

* Static sample data for UI testing
* Live layout preview for judges
* Easy switch to real data by embedding live sheets



## 🔄 EasyConnect Automation

Pre configured workflows include:

* Token price feed to Google Sheets
* Transaction tracking to Google Sheets
* Whale transaction filtering and routing
* Hourly analytics sync (optional)



## 🚢 Deployment

```bash
# Using GitHub Pages
Upload index.html to repository
Enable GitHub Pages from settings

# Using any static host
Upload project files and deploy
```



## 👥 Team

* **Rohan** – Team Lead
* **Yash** – Team Member
* **Rushi** – Team Member


## 🤝 Contributing

Contributions, UI improvements, and automation suggestions are welcome. Please follow clean coding standards and update documentation when required.

## 📝 License

MIT License – Open source and free to use for learning and hackathon purposes.

