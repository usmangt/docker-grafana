# Docker Logs Visualization with Grafana, Loki and Promtail


The aim of this workshop is to provide a hands-on experience with Grafana and how to use along with Loki and Promtail. The environment is Docker based.

## Prerequisites

- Docker
- Docker Compose
- Git

## Running the Demo

### Step 1: Clone the repository

```bash
git clone https://github.com/usmangt/docker-grafana.git
```

### Step 2: Deploy the monitoring stack

```bash
cd docker-grafana
docker compose up -d
```

### Step 3: Access Grafana Web UI

Open your browser and go to `http://YOUR-IP:3000`. This should show you the Web UI. 

Login as `admin` for both username and password.

### Step 4: Bringing down the deployment

```bash
docker compose down
```
