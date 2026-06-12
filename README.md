<div align="center">

# 🔧 System Engineering & DevOps — The Whiteboard Years

**Design before you deploy: web infrastructure, drawn and defended.**

[![DevOps](https://img.shields.io/badge/DevOps-Design-3E4B5B?style=for-the-badge&logo=linux&logoColor=white)](#)
[![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com)
[![Holberton](https://img.shields.io/badge/Holberton-Foundations-E44D26?style=for-the-badge)](https://www.holbertonschool.com)

</div>

---

## 🧭 About this repository

Some projects teach you to run infrastructure; this one teaches you to
**design** it. The `web_infrastructure_design` project is pure
architecture: whiteboard a web stack, label every component, and honestly
audit every failure mode — then scale it.

**Task 0** draws the *simple web stack*: one server carrying DNS, nginx,
the application, files and MySQL — with every single point of failure
named. **Task 1** redraws it distributed: three servers, a load balancer,
redundant app and database tiers, firewalls and HTTPS at the edge — with a
written justification for every addition.

## 📚 The project

| Project | What it covers |
|---|---|
| [`web_infrastructure_design/`](web_infrastructure_design/README.md) | One-server LAMP → load-balanced cluster: designs, diagrams, trade-offs |

## 🛠️ Environment

- A text answer + a diagram (`.png`) per design
- Every component labeled: SPOFs, traffic flow, failure modes

## 🚀 Read the designs

```bash
git clone https://github.com/Abdullayews/holbertonschool-system_engineering-devops.git
cat holbertonschool-system_engineering-devops/web_infrastructure_design/0-simple_web_stack
```


## 👤 Author

**Muhəmməd Abdullayev** — Computer Engineering student · Qarabağ University & Holberton School

<p>
<a href="https://github.com/Abdullayews"><img src="https://img.shields.io/badge/GitHub-@Abdullayews-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://t.me/arasss08"><img src="https://img.shields.io/badge/Telegram-@arasss08-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
<a href="mailto:08abdullayevv@gmail.com"><img src="https://img.shields.io/badge/Email-08abdullayevv@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

> 🇦🇿 Part of my Holberton School journey — Foundations & Specializations, one repo at a time.

