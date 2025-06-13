# 📈 Real-Time Stock Market Tracker using Django, Channels, Celery & Redis

A web application that displays real-time stock price updates using **Django**, **Django Channels**, **WebSockets**, **Celery**, and **Redis**—with a responsive frontend built using **HTML/CSS** and **JavaScript**.

---

## 🚀 Features

- 🔄 **Real-time stock price updates** via WebSockets (no page refresh)
- 🧠 **Asynchronous background data fetching** using Celery and Redis
- 💾 **Session-based stock selection** (no login required)
- 🎯 Users can select multiple stocks to monitor
- 📱 **Responsive UI** with interactive elements and dynamic updates
- 🛠️ Scalable architecture using decoupled components (backend tasks + live frontend)


![pic_1](https://github.com/user-attachments/assets/ea3cb702-1d80-4d98-ba57-56baf17055f7)
![pic_2](https://github.com/user-attachments/assets/31af63ee-3b3d-47a3-a38f-90e9b22838bc)
![pic_3](https://github.com/user-attachments/assets/73214434-3b37-4f46-b19c-dc8427debcb9)



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
