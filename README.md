# 🚀 CryptoPulse Pro

[![API Providers](https://img.shields.io/badge/API-CoinGecko-green)](https://www.coingecko.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Stack](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-blue)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**CryptoPulse Pro** is an advanced, real-time cryptocurrency analytics dashboard. It combines live market data with local-first portfolio management and browser-level price alerts to provide a professional trading environment directly in the browser.



---
<div align="center">
  <a href="https://amazeabhi.github.io/CRYPTO-DASHBROAD/">
    <img src="https://img.shields.io/badge/LAUNCH_DASHBOARD-00d2ff?style=for-the-badge&logo=rocket&logoColor=white" width="400" alt="Launch Project">
  </a>

  <p><b>Click the button above to view the live market data dashboard!</b></p>
</div>

---

## 🌟 Features

- **📊 Live Analytics:** High-fidelity 7-day price charts for 100+ assets powered by `Chart.js`.
- **💰 Portfolio Tracker:** Manage your holdings with automated value calculations and persistent storage via `LocalStorage`.
- **🔔 Notification Engine:** Real-time price monitoring that triggers native browser alerts when targets are hit.
- **⚡ Infinite Ticker:** A high-performance marquee showing real-time price fluctuations.
- **🔍 Instant Filter:** Search through the global market cap leaders with zero latency.
- **🎨 Glassmorphism UI:** A sleek, animated interface with a responsive "Developer-First" aesthetic.

---

## 🛠️ Technical Overview

### Architecture
The application follows a **Vanilla Single Page Application (SPA)** architecture. It avoids heavy frameworks to maximize performance and minimize bundle size.



- **Data Source:** `CoinGecko V3 API`
- **Security:** API Key authentication via custom headers.
- **Persistence:** State is maintained across sessions using the `Web Storage API`.
- **Notifications:** Integrated with the `Notifications API` for background alerts.

---

## 🚀 Getting Started

### Prerequisites
* A valid CoinGecko API Key.
* A modern web browser (Chrome, Firefox, Brave, or Edge).

### Installation

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/cryptopulse-pro.git](https://github.com/your-username/cryptopulse-pro.git)
   cd cryptopulse-pro
