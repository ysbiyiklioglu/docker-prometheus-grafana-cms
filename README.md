📊 CMS Monitoring Stack with Prometheus & Grafana
This project sets up a complete monitoring environment using Docker Compose, including Joomla CMS instances with both MySQL and PostgreSQL support, Prometheus for metric collection, Grafana for visualization, and related exporters.

🧱 Stack Components
Joomla: Two separate CMS instances (one with MySQL, one with PostgreSQL)

MySQL & PostgreSQL: Database services

Prometheus: Metrics collection

Grafana: Metrics visualization

mysqld_exporter & postgres_exporter: Exporters for database metrics

🚀 Getting Started
Clone the repository:

bash
Kopyala
Düzenle
git clone https://github.com/your-username/cms-monitoring-stack.git
cd cms-monitoring-stack
Start the services:

bash
Kopyala
Düzenle
docker-compose up -d
Access the web interfaces:

Joomla (MySQL): http://localhost:8081

Joomla (PostgreSQL): http://localhost:8082

Prometheus: http://localhost:9090

Grafana: http://localhost:3000

📈 Grafana Dashboard
You can visualize MySQL and PostgreSQL metrics directly in Grafana.
Default credentials: admin / admin
