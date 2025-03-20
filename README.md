# 📡 Realtime Change Data Capture (CDC) Streaming

This project implements **Change Data Capture (CDC)** to enable real-time data streaming from a relational database to **Apache Kafka**. The pipeline captures inserts, updates, and deletes in the database and streams them to downstream consumers in near real-time. The architecture leverages **Debezium, Kafka Connect, and Schema Registry** for efficient and scalable event-driven data processing.

---

## 🛠 Tech Stack

| Component            | Technology |
|----------------------|------------|
| **Change Data Capture** | Debezium |
| **Streaming Platform** | Apache Kafka |
| **Data Storage** | PostgreSQL / MySQL |
| **Schema Management** | Confluent Schema Registry |
| **Workflow Automation** | Kafka Connect |
| **Event Processing** | Kafka Consumers |

---

## 🔍 Architecture

1. **Data Source (Relational Database)**
   - A **PostgreSQL/MySQL** database where data is continuously updated.

2. **CDC (Change Data Capture)**
   - **Debezium** tracks changes (INSERT, UPDATE, DELETE) in the database.

3. **Data Streaming**
   - **Kafka Connect** streams CDC events to **Kafka topics**.

4. **Schema Management**
   - **Schema Registry** ensures data consistency and evolution.

5. **Event Processing**
   - **Kafka Consumers** process, filter, and transform data in real-time.

---

## 📊 Usage

- The pipeline **monitors database changes** and **streams updates** to Kafka topics.
- **Kafka consumers** can process the data in **real-time** for analytics or application workflows.
- Supports **scalable event-driven architecture** for handling **large data volumes**.

---

## 🎯 Key Learnings

✅ **End-to-End CDC Implementation**  
   - Gained hands-on experience with **Debezium, Kafka, and event-driven architectures**.

✅ **Streaming Database Changes in Real-Time**  
   - Implemented **low-latency data streaming** for scalable analytics and processing.

✅ **Schema Evolution & Data Consistency**  
   - Used **Schema Registry** to manage **versioned data changes**.

✅ **Building a Scalable & Fault-Tolerant Pipeline**  
   - Designed a **resilient system** that can handle **high-velocity data**.

✅ **Workflow Automation with Kafka Connect**  
   - Automated **data ingestion and streaming** without manual intervention.

---

## 🎯 Results

✅ Successfully captured **database changes in real-time** using CDC.  
✅ Enabled **high-performance streaming and analytics** using Kafka.  
✅ Built a **scalable event-driven architecture** for **big data processing**.  

---


