<div align="center">

# 📐 Web infrastructure design

**Whiteboard first, servers second: from one lonely LAMP box to a load-balanced cluster.**

[![DevOps](https://img.shields.io/badge/DevOps-Design-3E4B5B?style=flat-square&logo=linux&logoColor=white)](#)
[![Holberton](https://img.shields.io/badge/Holberton-Foundations-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this project

This project is pure architecture: no code to run, only systems to *design*
and defend. Task 0 draws the **simple web stack** — one server carrying
DNS, nginx, the application, files and MySQL all by itself, and honestly
labeling every single point of failure.

Task 1 scales it out into a **distributed infrastructure** — three servers,
a load balancer splitting traffic, redundant application and database
nodes — and then documents exactly what was added and why: SPOFs
eliminated, clusters for the data tier, and the reasons a firewall and
HTTPS live at the edge.

## 🎯 Concepts covered

- DNS, A records, and what `www` actually points to
- The LAMP stack on a single server — and its SPOFs
- Load balancers: algorithms and health checks
- Web / app / database tier separation
- High availability — clusters and redundancy
- Security at the edge: firewalls, HTTPS, no root logins

## 📂 Files

| File | What it does |
|---|---|
| [`0-simple_web_stack`](https://github.com/Abdullayews/holbertonschool-system_engineering-devops/tree/main/web_infrastructure_design/0-simple_web_stack) | Task 0 — the single-server stack, component by component |
| [`0-simple_web_stack.png`](https://github.com/Abdullayews/holbertonschool-system_engineering-devops/tree/main/web_infrastructure_design/0-simple_web_stack.png) | Diagram of the simple web stack |
| [`1-distributed_web_infrastructure`](https://github.com/Abdullayews/holbertonschool-system_engineering-devops/tree/main/web_infrastructure_design/1-distributed_web_infrastructure) | Task 1 — the distributed, load-balanced redesign |
| [`1-distributed_web_infrastructure.png`](https://github.com/Abdullayews/holbertonschool-system_engineering-devops/tree/main/web_infrastructure_design/1-distributed_web_infrastructure.png) | Diagram of the distributed infrastructure |

## ⚙️ Requirements

- 📝 Each design: a text answer + a diagram (`.png`)
- 🏷️ Every component labeled — SPOFs, traffic flow, failure modes

## 🚀 Try it yourself

```bash
cat 0-simple_web_stack     # one server, honestly audited
cat 1-distributed_web_infrastructure   # three servers, load-balanced
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-system_engineering-devops](../README.md)**
