# 📊 CMS Monitoring Stack with Prometheus & Grafana

This project sets up a complete monitoring environment using **Docker Compose**, including **Joomla CMS** instances with both **MySQL** and **PostgreSQL** support, **Prometheus** for metric collection, **Grafana** for visualization, and related exporters.

---

## 🧱 Stack Components

* **Joomla**: Two separate CMS instances

  * One with **MySQL**
  * One with **PostgreSQL**

* **MySQL & PostgreSQL**: Database services

* **Prometheus**: Metrics collection

* **Grafana**: Metrics visualization

* **mysqld\_exporter & postgres\_exporter**: Exporters for database metrics

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/ysbiyiklioglu/docker-prometheus-grafana-cms.git
cd docker-prometheus-grafana-cms

```

Start the services:

```bash
docker-compose up -d
```

---

## 🌐 Access Web Interfaces

* Joomla (MySQL): [http://localhost:8081](http://localhost:8081)
* Joomla (PostgreSQL): [http://localhost:8082](http://localhost:8082)
* Prometheus: [http://localhost:9090](http://localhost:9090)
* Grafana: [http://localhost:3000](http://localhost:3000)

---

## 📊 Grafana Dashboard

You can visualize **MySQL** and **PostgreSQL** metrics directly in Grafana.
**Default credentials:**

* **Username:** `admin`
* **Password:** `admin`
