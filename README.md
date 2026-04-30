<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&multiline=true&width=750&height=90&lines=Hey!+I'm+Yash+Kumar+%F0%9F%91%8B;Backend+Engineer+in+the+Making+%E2%9A%99%EF%B8%8F;I+Build+Systems%2C+Not+Just+Code+%F0%9F%94%A5)](https://git.io/typing-svg)

![Visitor Count](https://komarev.com/ghpvc/?username=iamyashkumar&label=Profile+Views&color=22D3EE&style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/iamyashkumar?style=for-the-badge&color=6366f1&label=Followers)

</div>

---

## 🧠 Who Am I?

```java
public class YashKumar {

    String name        = "Yash Kumar";
    String college     = "IEC College of Engineering & Technology, AKTU";
    String degree      = "B.Tech Information Technology (2023 - 2027)";
    String year        = "3rd Year";
    String location    = "Greater Noida, Uttar Pradesh, India";

    String[] building  = {
        "Distributed Task Scheduler — 3-node cluster, Redlock, ZooKeeper, 500+ jobs/sec",
        "Smart Classroom Assistant — ESP32 IoT system with health & energy monitoring"
    };

    String[] learning  = {
        "Distributed Systems", "Apache Kafka", "ZooKeeper",
        "Docker", "Spring Cloud", "System Design"
    };

    String achievement = "Robocon 2025 National Qualifier — Hardware & Firmware Lead";
    String target      = "Backend Developer Internship at a Product-Based Company";

    String mindset     = "If I can't explain how it works internally, I haven't learned it yet.";
}
```

---

## ⚙️ What I'm Engineering Right Now

### ⚡ Distributed Task Scheduler *(Major Project — In Progress)*

> *A production-grade distributed scheduler — zero duplicate execution, sub-5s failover, 500+ jobs/sec*

```
Client Request
      ↓
Spring Boot REST API  →  JWT Auth (Spring Security)
      ↓
Quartz JDBC Clustering  →  Shared MySQL (3-node Docker cluster)
      ↓
Redlock Algorithm  →  5 Redis Nodes (Majority Quorum Voting)
      ↓           (Zero duplicate execution even with 2 node failures)
ZooKeeper Leader Election  →  Apache Curator Ephemeral znodes
      ↓           (Sub-5-second failover on node crash)
Retry: Exponential Backoff (2^n sec)  →  Dead Letter Queue (Redis Lists)
      ↓
Micrometer + Prometheus  →  Grafana Dashboards
      ↓          (5+ custom metrics: jobs_executed_total, job_duration, etc.)
Docker Compose  →  Prometheus + Grafana + 5 Redis + MySQL + 3 Scheduler nodes
```

**Stack:** Java · Spring Boot · Quartz · Redis · ZooKeeper · Docker · Prometheus · Grafana · MySQL · JWT

![Status](https://img.shields.io/badge/Status-In%20Progress-22D3EE?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Major%20Project-6366f1?style=for-the-badge)
![Throughput](https://img.shields.io/badge/Throughput-500%2B%20jobs%2Fsec-green?style=for-the-badge)

**Key highlights:**
- 🔒 **Redlock** — 5-node Redis distributed locking with majority quorum voting
- 🗂️ **ZooKeeper** — Leader election via ephemeral sequential znodes (Apache Curator)
- 🔁 **DLQ** — Exponential backoff retry + `/admin/dlq` REST endpoint for manual replay
- 📊 **Full Observability** — Micrometer + Prometheus + Grafana with 5+ custom metrics
- 🐳 **One-command setup** — Everything runs via Docker Compose

---

### 🏫 Smart Classroom Assistant — Energy & Health Monitoring *(Solo IoT Project — Completed)*

> *A solo-built embedded IoT system that monitors health, controls appliances, and alerts anomalies in real-time*

```
ESP32 (WiFi-enabled MCU)
      ↓
MAX30102 (Heart Rate / SpO2)   DHT11 (Temp / Humidity)   PIR (Occupancy)
      ↓                               ↓                         ↓
  Health Alerts               Environment Logging         Occupancy Detection
  (Buzzer + LEDs)                     ↓                         ↓
                              Cloud (WiFi Uplink)    Relay Module → Fan / Light Control
```

**Stack:** ESP32 · Embedded C · MAX30102 · DHT11 · PIR Sensor · Relay Module · Arduino IDE · Cloud

![Status](https://img.shields.io/badge/Status-Completed-10b981?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-IoT%20Project-F59E0B?style=for-the-badge)

---

### 🏀 Basketball Playing Robot — Robocon 2025 *(Team Project — National Qualifier)*

> *Hardware & Firmware Lead — solely responsible for all electrical, firmware & wireless systems*

```
ESP32 (WiFi/Bluetooth Transmitter)  ←→  Arduino Mega (Receiver Robot)
                ↓
         Arduino Uno (Sub-controller)
                ↓
BTS7960 / L298N Motor Drivers  →  High-Torque Precision Motor Control
                ↓
Embedded C Firmware  →  Real-time Manual Control + Wireless Comm
```

**Stack:** ESP32 · Arduino Uno · Arduino Mega · BTS7960/L298N · Embedded C · Arduino IDE

![Status](https://img.shields.io/badge/Status-Completed-10b981?style=for-the-badge)
![Achievement](https://img.shields.io/badge/Robocon%202025-National%20Qualifier-gold?style=for-the-badge)

---

## 🛠️ My Tech Arsenal

### Core Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Backend & Distributed Systems
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=for-the-badge&logo=fastapi&logoColor=white)

### Databases & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps & Observability
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

### IoT & Embedded
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

---

## 🏆 Achievements

| 🥇 Achievement | 📋 Details |
|---|---|
| **Robocon 2025 National Qualifier** | ABU Robocon 2025 (Theme: Basketball Robot) — Cleared 2 preliminary rounds to reach the national level |
| **Hardware & Firmware Lead** | Solely handled all electrical design, circuit integration, motor drivers & wireless firmware for the Robocon robot |

---

## 📊 GitHub Stats

<div align="center">

![Yash's GitHub Stats](https://github-readme-stats.vercel.app/api?username=iamyashkumar&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=iamyashkumar&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=iamyashkumar&theme=tokyonight&hide_border=true)

</div>

---

## 📈 My Backend Journey

```
2023  →  Started B.Tech IT @ IEC | Java fundamentals + OOP deep dive
2024  →  Spring Boot + REST APIs + MySQL + PostgreSQL
2025  →  Microservices + Kafka + Docker + System Design
         Robocon 2025 — Hardware & Firmware Lead → National Qualifier 🏆
2026  →  Distributed Task Scheduler (Redlock + ZooKeeper + Quartz + Prometheus)
         Smart Classroom IoT Assistant (ESP32 + Sensors + Cloud)
2027  →  Target: Backend Developer at a Top Product Company 🎯
```

---

## 💡 What Drives Me

```
I don't stop at making things work.
I want to know:
   → WHY use Redlock over a single Redis lock?
   → WHAT happens when 2 out of 5 Redis nodes fail during lock acquisition?
   → HOW does ZooKeeper guarantee leader uniqueness with ephemeral znodes?
   → WHERE is the bottleneck when 500+ jobs/sec hit the scheduler cluster?

That's the engineer I'm becoming.
```

---

## 🌐 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/iamyashkumar)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/iamyashkumar)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yashkumarkanha@gmail.com)

</div>

---

<div align="center">

### ⚡ Engineering Principle

*"Understand the internals. Build the fundamentals. Scale the system."*

**Currently:** Building a production-grade Distributed Task Scheduler with Redlock, ZooKeeper leader election, and full Prometheus observability — mastering distributed systems from the ground up.

---

⭐ **Star my repos if you find them useful — it keeps me going!** ⭐

![Wave](https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg)

</div>
