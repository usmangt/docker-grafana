# Docker Logs Visualization with Grafana, Loki and Promtail


This repository contains the mininal code to deploy Grafana with Loki and Promtail to visualize log files. The environment is **Docker** based.

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

# Beginngers Guide - Migrating from exisitng Promtail configuraiton (for Grafana Loki) to Grafana Alloy

The Grafana Promail is now End-of-Life (EOL) as stated on the [Grafnaa Labs official page](https://grafana.com/docs/loki/latest/send-data/promtail/) and Grafana Alloy is the new Agent for Grafana Loki.

Here is are some useful links as how to get started by understanding the fundamentaions and then successfully migrate your exisitng Promtail configuraiton files to Grafnaa Alloy.

## Link to Documentation

Here is the link to the documenation that explains in more details:


##  - Link to Video 🎉

Check out the video, where I have also explained this in a video tutorial that covers everything from basic steps to advanced troubleshooting

<div align="center">
  <a href="https://www.youtube.com/watch?v="><img src="https://img.youtube.com/vi//0.jpg" alt="Docker Tutorial - Gettting started with Grafnaa Alloy | Grafana Loki (Promtail) Migration guide."></a>
</div>


