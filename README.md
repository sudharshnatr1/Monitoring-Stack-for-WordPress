# 📊 Docker-Based Monitoring Stack for WordPress & Linux Servers

This script sets up a powerful, containerized monitoring stack for your WordPress server (or any Linux server). It includes Prometheus, Grafana, Loki, Promtail, and Jaeger using Docker Compose – all configured to work out-of-the-box.

Perfect for gaining visibility into your system performance, logs, and distributed traces.

---

## ⚙️ What's Included?

| Tool        | Purpose                          | Port     |
|-------------|----------------------------------|----------|
| Prometheus  | Metrics collection               | `9090`   |
| Grafana     | Data visualization dashboard     | `3000`   |
| Loki        | Log aggregation                  | `3100`   |
| Promtail    | Log shipping to Loki             |  ` - `   |
| Jaeger      | Distributed tracing              | `16686`  |

---

## 🚀 How to Use

### 🛠 Prerequisites

- Ubuntu/Debian system
- Root or sudo privileges
- Docker & Docker Compose (installed automatically by the script)

---

### 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sudharshnatr1/Monitoring-Stack-for-WordPress.git
   cd monitoring-stack
   ```
2. Run the script
   ```bash
   ./setup.sh
   ```
     or
   ```bash
    sudo bash setup.sh
   ```

---

### 🌐 Access Your Monitoring Stack
After the script runs, access each service via your browser:

Prometheus: http://<server-ip>:9090

Grafana: http://<server-ip>:3000
Default login: admin / admin

Loki API: http://<server-ip>:3100

Jaeger UI: http://<server-ip>:16686


---
### 📜 License
MIT License

---

### 🙌 Credits
Prometheus
Grafana
Loki
Jaeger
Docker
