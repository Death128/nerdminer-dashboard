🎰 NerdMiner Lottery Dashboard
<p align="center"> <img src="https://raw.githubusercontent.com/Death128/nerdminer-dashboard/main/assets/banner.png" width="800"/> </p> <p align="center"> <strong>A modern Bitcoin solo mining dashboard for NerdMiner & hobby miners.</strong> </p> <p align="center"> <img src="https://img.shields.io/github/license/Death128/nerdminer-dashboard?style=for-the-badge"> <img src="https://img.shields.io/github/stars/Death128/nerdminer-dashboard?style=for-the-badge"> <img src="https://img.shields.io/github/last-commit/Death128/nerdminer-dashboard?style=for-the-badge"> <img src="https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge"> <img src="https://img.shields.io/badge/frontend-vanilla%20JS-blue?style=for-the-badge"> </p>


✨ Overview
NerdMiner Lottery Dashboard is a lightweight, client-side Bitcoin monitoring interface built for solo mining enthusiasts using public-pool.io.

It provides real-time wallet statistics, network data, stability metrics, and clean hash visualization — all without requiring a backend server.

🔒 No private keys 🌐 Fully front-end 📊 Real-time wallet monitoring

🚀 Features 📊 Wallet Monitoring

● Total wallet hashrate
● Active worker detection
● Best share difficulty tracking
● Stability percentage calculation
● Average hash per active worker

🌍 Network Data

● Current block height
● Network difficulty (compact + full format)
● Live BTC price (CoinGecko API)

📈 Visualization

● Real-time hashrate chart (Chart.js)
● Auto-refresh system
● CSV export of stats
● Smooth UI transitions

🎨 Interface

● Modern dark theme
● Animated mesh background
● Optional rain effect
● Sidebar navigation
● Responsive layout

📦 Deployment GitHub Pages (Recommended)

Push repository to GitHub.
Go to:
Settings → Pages
Under Source:
Select Deploy from branch
Choose main
Select /root
Save.
Your dashboard will be available at:
https://yourusername.github.io/repository-name/ 🔧 Local Hosting (Optional) cd dashboard-folder python3 -m http.server 8080
Access via:
http://YOUR-IP:8080 🧠 How It Works
User enters a Bitcoin wallet address.
Dashboard queries public-pool.io API.
Network difficulty and block data are fetched.
Hashrate is calculated from worker stats.
Chart updates in real time.
Stability is computed from active vs total workers.
All processing occurs client-side.
No backend. No database. No authentication.

🔐 Security
● Read-only wallet monitoring.
● No private key storage.
● Uses public APIs only.
● Safe for public GitHub Pages deployment.

🧩 Built With
● TailwindCSS
● Chart.js
● Vanilla JavaScript
● Canvas API animations
