# Kafka with UI using Docker Compose

This project sets up a simple **Apache Kafka** environment using **Docker Compose**, including:

- **Zookeeper**
- **Kafka Broker** (via Bitnami image)
- **Kafka UI** (via Provectus Kafka UI)

## 🧩 Services Overview

| Service     | Port | Description                                  |
|-------------|------|----------------------------------------------|
| Zookeeper   | 2181 | Required for Kafka coordination              |
| Kafka       | 9092 | Kafka broker for publishing/subscribing data |
| Kafka UI    | 8080 | Web interface to interact with Kafka         |

---
