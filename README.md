#📊 Stock Broker Client Dashboard

A fully interactive frontend-only stock tracking dashboard built using HTML, CSS, Vanilla JavaScript, Chart.js, and jsPDF.
Users can log in with email, subscribe to real-time simulated stock prices, view live charts, generate PDF reports, and maintain subscription history, all stored in localStorage.

⚡ This project requires no backend, making it perfect for demos, portfolios, and GitHub Pages deployment.

#🚀 Features
🔐 Login System

Email-based login validation

User session saved with localStorage

Auto-login support

📈 Real-Time Stock Price Simulation

Live stock price updates every 1 second

Dynamic price color changes (green ↑ / red ↓)

Supports popular stock tickers:

GOOG

TSLA

AMZN

META

NVDA

📊 Interactive Live Charts

Built using Chart.js

Each subscribed stock gets its own chart

Switch between Line Chart and Area Chart

Smooth animations

Max 30 data points shown at a time

🧾 Activity Tracking

Every subscription/unsubscription is logged with:

Timestamp

Action

Stock ticker

Displayed cleanly in an activity feed.

📄 PDF Report Generator

Using jsPDF, users can download:

Logged-in email

Current subscriptions

Full activity history

🗂 LocalStorage User Management

Each user has:

Subscription list

Activity history

Stored locally on the browser — no backend required.

#🖥️ Technologies Used
Technology	Purpose
HTML5	Page structure
CSS3	Modern UI, gradients, glassmorphism
JavaScript	Entire application logic
Chart.js	Dynamic real-time graphs
jsPDF	PDF report downloads
LocalStorage	Simulated user accounts
