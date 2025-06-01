# Real-Time-Stock-Market-Price-Checking-App-Built-Using-Django-Celery-Django-Channels-WebSockets.
This Real-Time Stock Market Price Checking App Built Using Django, where user can select the one or multiple stocks from the list and can check their price in Real-time which updates frequently. It Store the User Session ID in the database on temporary basis. Session ids are further used to send data to user.

🚀 Features

- 🔄 **Real-time stock price updates** via WebSockets (no page refresh)
- 🧠 **Asynchronous background data fetching** using Celery and Redis
- 💾 **Session-based stock selection** (no login required)
- 🎯 Users can select multiple stocks to monitor
- 📱 **Responsive UI** with interactive elements and dynamic updates
- 🛠️ Scalable architecture using decoupled components (backend tasks + live frontend)

---

## 🛠️ Tech Stack

- **Backend:** Django, Django Channels, WebSockets
- **Task Queue:** Celery
- **Message Broker:** Redis
- **Frontend:** HTML, CSS, JavaScript
- **Other Tools:** ASGI, Daphne (for production use), SQLite (default DB)

---

## 📦 Installation

> **Note:** These instructions are for **Windows**. Ensure you have Python 3.8+ installed.

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/stockmarket-realtime.git
cd stockmarket-realtime
