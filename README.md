# Decker's Stock Monitor
Simple Stock Performance Monitor with Short-term Projections

A lightweight, console-style web application for tracking top stocks in real-time. Inspired by platforms like Robinhood, but with a sleek, hacker-console aesthetic. Stock Monitor focuses on **clarity, speed, and actionable insights**—not fluff or clickbait.

---

## 🚀 Features

- **Live Stock Data**  
  Pulls in current stock prices, growth percentages, and profit potential.

- **Ranked Leaderboard**  
  Displays stocks in order of best performance, with price and growth trends at a glance.

- **Trend Summaries**  
  Gives contextual notes (e.g., CEO moves, tech adoption, market sentiment). Headlines are clickable, but repeated/noisy ones are filtered out.

- **Interactive UI**  
  Console-inspired layout: dark background, neon-style highlights, monospaced fonts, and clean grid alignment.

- **Profit & Sell Tracking**  
  Each stock includes potential profit calculations and best estimated sell windows (≤3 months).

- **Charts**  
  Each stock has a quick-view mini-chart to visualize recent performance.

- **Fallback State**  
  If no input is provided yet, everything starts from `0` to indicate a clean state.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (with DOM-driven rendering)  
- **Styling**: Dark theme + console aesthetic (tech-green, neon accents)  
- **Data Handling**: JSON objects to simulate or fetch stock data  
- **Favicon**: Finance-themed (e.g., 📈, 💹, or dollar-coin style)  
