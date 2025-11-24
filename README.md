
# DevOps Observability Toolkit
A complete end-to-end observability stack integrating **Prometheus, Grafana, Loki, Alertmanager, Node Exporter, MySQL Exporter, Redis Exporter, and JVM Metrics**.  
This toolkit demonstrates how to build a **production-grade monitoring system** similar to what I deployed at Tamam Finance.

---

## 🚀 Features
- Full metrics collection for microservices, databases, servers, and containers  
- Centralized log aggregation using Loki  
- Alerting with email/SMS/Webhook  
- Ready-made Grafana dashboards for:
  - Java/Spring Boot services
  - Kubernetes clusters
  - MySQL & Redis performance
  - API latency & throughput
- Docker Compose orchestration  
- Extensible for Kubernetes & cloud-native environments  

---

## 📦 Stack Components
| Component | Purpose |
|----------|---------|
| Prometheus | Metrics scraping & storage |
| Grafana | Dashboards & visualization |
| Loki | Log aggregation |
| Alertmanager | Alerts & notifications |
| Node Exporter | OS-level metrics |
| MySQL/Redis Exporters | Database monitoring |
| JVM Exporter | Java app metrics |

---

## 📁 Project Structure

k8s-monitoring-dashboards/
├── dashboards/
│ ├── cluster-overview.json
│ ├── node-health.json
│ ├── pod-performance.json
│ ├── api-latency.json
│ └── network-traffic.json
└── exporters/


---

## ▶️ Usage
Import any dashboard JSON into Grafana:

**Grafana → Dashboards → Import → Upload JSON**

Ensure the following exporters exist:
- kube-state-metrics
- metrics-server
- node exporter

---

## 📜 License
MIT License

