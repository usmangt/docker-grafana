# Docker Logs Visualization with Grafana, Loki and Promtail

This repository contains the minimal code to deploy Grafana with Loki and Promtail to visualize log files. The environment is **Docker** based.

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

## Beginngers Guide - Migrating from exisitng Promtail configuraiton (for Grafana Loki) to Grafana Alloy

The Grafana Promtail is now End-of-Life (EOL) as stated on the [Grafana Labs official page](https://grafana.com/docs/loki/latest/send-data/promtail/) and Grafana Alloy is the new Agent for Grafana Loki.

Here are some useful links as how to get started by understanding the fundamentals and then successfully migrate your existing Promtail configuration files to Grafana Alloy.

### Link to Documentation

Here is the link to the documentation that explains in more details:

### Link to Video

Check out the video, where I have also explained this in a video tutorial that covers everything from basic steps to advanced troubleshooting

<div align="center">
  <a href="https://www.youtube.com/watch?v=mRaun_Q96FI"><img src="https://img.youtube.com/vi/mRaun_Q96FI/0.jpg" alt="Docker Tutorial - Gettting started with Grafnaa Alloy | Grafana Loki (Promtail) Migration guide."></a>
</div>

### For New users

💡If you are new to Docker, Grafana and Linux and interested in learning from scratch to build the right foundation, then here are the links to the complete tutorials:

- ➡️ [How to install Linux on a virtual machine](https://www.youtube.com/watch?v=-VAITfYziBM)
- ➡️ [How to install Docker on Linux (or on a virtual machine)](https://www.youtube.com/watch?v=LsBzyvCFmkQ)
- ➡️ [Understanding and Using Grafana on Docker](https://www.youtube.com/watch?v=wL1mUDYgDK4)
