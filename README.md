# WebSocket Notification System

A real-time notification system built using **Spring Boot** and **WebSockets** with **STOMP protocol**. The application enables server-to-client push notifications and demonstrates live message delivery in a web UI.

---

## 🚀 Tech Stack

* **Spring Boot**
* **WebSocket (STOMP)**
* **Spring Web**
* **Thymeleaf**
* **SockJS**

---

## ✨ Features

* Real-time notifications using WebSockets
* STOMP-based messaging (`/topic`, `/app`)
* Server-side message broadcasting
* Simple UI using Thymeleaf
* Auto-reconnect support via SockJS

---

## 📂 Project Flow

* Client connects to WebSocket endpoint
* Subscribes to a notification topic
* Server pushes notifications instantly to connected clients

---

## ▶️ Run the Application

```bash
mvn spring-boot:run
```

Open in browser:

```
http://localhost:8080
```

---

## 🔌 WebSocket Endpoints

* **WebSocket Endpoint:** `/ws`
* **App Destination Prefix:** `/app`
* **Topic:** `/topic/notifications`

---

## 📌 Use Case

* System alerts
* Live notifications
* Real-time dashboards
* Chat / event updates

---


