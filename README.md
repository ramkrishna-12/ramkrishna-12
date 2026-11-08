<div align="center">

<p align="center">
  <a href="https://github.com/ramkrishna-12">
    <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=2ea043&fontSize=54&height=90&width=762&text=Hello!%20I'm%20Ramkrishna" alt="Hello! I&#39;m Ramkrishna" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Caveat&weight=600&size=26&pause=1000&color=3fb950&center=true&vCenter=true&width=900&height=44&lines=Cloud%20Engineer%20%7C%20AWS%20%7C%20Infrastructure-as-Code%20(Terraform)%20%7C;DevOps%20%7C%20Python%20%7C%20Scalable%20Systems%20%7CDevOpsAI%20%26%20Machine%20Learning%20Associate" alt="Typing headlines" />
</p>

### Cloud & DevOps / Infrastructure Engineer · Kolkata, India

I build and ship cloud infrastructure on AWS: automated, observable, and zero-downtime where it counts.

[![Portfolio](https://img.shields.io/badge/Portfolio-ramkrishna--12.github.io-0A66C2?style=for-the-badge&logo=githubpages&logoColor=white)](https://ramkrishna-12.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramkrishna-roy-barman-48391b16a/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)]

</div>

---

## 🧭 About

- ☁️ ~2 years of production experience in Cloud & DevOps, most recently as a **Cloud & Infrastructure Engineer at Stylopay (FinTech)**
- 🧪 Came into infra from **ML / Data Science** (Digi Samurai LLP), where I also taught Python, Django and ML to college students
- 🎓 B.Tech in Mechanical Engineering · Post Graduate Certificate in Data Science
- ⚛️ Long-standing interest in quantum mechanics, now exploring **quantum cloud computing**
- 📫 Open to Cloud / DevOps / SRE roles, so reach out

## 🔭 What I'm working on now

| | |
|---|---|
| 🤖 **[aws-bedrock](https://github.com/ramkrishna-12/aws-bedrock)** | Running AI models pulled from AWS Bedrock to perform real tasks, and understanding how AI workloads actually run on AWS (ongoing, ~4 months) |
| 🌐 **[Portfolio site](https://ramkrishna-12.github.io/portfolio/)** | Static site on GitHub Pages with an inquiry chat grounded in my own portfolio data |
| ⚛️ **Quantum cloud computing** | Learning and planning phase |

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,terraform,githubactions,jenkins,docker,kubernetes,linux,python,django,fastapi,prometheus,grafana,elasticsearch,git" alt="Tech stack" />
</p>

| Area | Tools |
|---|---|
| **Cloud** | AWS (EC2, ECS/Fargate, EKS, Lambda, API Gateway, ALB, Route 53, ACM, S3, RDS, IAM) |
| **IaC & CI/CD** | Terraform, GitHub Actions (OIDC), Jenkins |
| **Containers** | Docker, Docker Swarm, ECS, EKS |
| **Observability** | CloudWatch, ELK, Prometheus, Grafana |
| **Scripting & ML** | Python, Bash, Pandas, MLflow, FastAPI |
| **OS** | Linux |

## 🚀 Featured projects

### 🤖 [aws-bedrock](https://github.com/ramkrishna-12/aws-bedrock)
Anthropic models served through AWS Bedrock performing tasks, built to understand how AI models run inside AWS. *(Ongoing)*

### 🔐 [file-upload-validation](https://github.com/ramkrishna-12/file-upload-validation): Secure file upload pipeline
Defence in depth for untrusted uploads:
- **A** filename validation → **B** magic-byte content validation → **C** AV / malware scan → **D** static analysis for scripts and macros (PDF JavaScript/OpenAction, VBA, SVG/HTML XSS)
- Quarantine flow, API Gateway abstraction for downloads, IAM least privilege with audit logging, checksum-based integrity verification

### 🧠 [Ml_Flow-Pipeline](https://github.com/ramkrishna-12/Ml_Flow-Pipeline): Fraud-detector MLOps on AWS ECS
- Data (S3/parquet) → validate → train sweep (MLflow nested runs) → quality gate → register → challenger vs champion; promotion = moving the `@champion` alias
- **CI:** lint, tests, pipeline smoke, Docker build, `terraform fmt/validate` · **CD:** train → build image → approval → ECS rolling deploy → smoke test
- **Serving:** Client → ALB → ECS Fargate API loading `models:/fraud-detector@champion` from an MLflow service on ECS, backed by RDS Postgres and S3 artifacts

### 📦 [shipment_error](https://github.com/ramkrishna-12/shipment_error): E-commerce ETL pipeline
Production-style ETL on messy shipment/order CSVs with Python, Pandas, Docker and GitHub Actions: cleaning, standardisation, dedup, multi-table merge, revenue calculation, shipment aggregation, automated workflow runs.

## 💼 Experience highlight

### Zero-downtime multi-region Blue-Green migration @ Stylopay
- Migrated a FinTech platform's microservices infrastructure to a new multi-region setup with **no downtime**
- Validated against QA APIs first, then cut over to prod APIs, running a **60/40 blue/green traffic split for the first week** with the old infra kept as a fallback
- Scope covered ~12 EC2 hosts running 3-4 microservices each, 10-12 Lambda-backed APIs behind API Gateway, Docker Swarm managers, and frontend hosts, fronted by **ALB, Route 53 and ACM**

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats-five-sigma-99.vercel.app/api?username=ramkrishna-12&show_icons=true&theme=tokyonight&title_color=2ea043&icon_color=2ea043&hide_border=true&bg_color=00000000&count_private=true" alt="stats" />
  <img height="165" src="https://github-readme-stats-five-sigma-99.vercel.app/api/top-langs/?username=ramkrishna-12&layout=compact&theme=tokyonight&title_color=2ea043&icon_color=2ea043&hide_border=true&bg_color=00000000&langs_count=8" alt="top langs" />
</p>

### 📈 Contribution Graph

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph-gold-gamma.vercel.app/graph?username=ramkrishna-12&bg_color=00000000&color=2ea043&line=2ea043&point=c9d1d9&area=true&hide_border=true" alt="activity graph" />
</p>
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ramkrishna-12&show_icons=true&theme=transparent&hide_border=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramkrishna-12&layout=compact&theme=transparent&hide_border=true" alt="Top languages" />
</p>

## 📫 Let's connect
<p align="center"> <img height="170" src="https://github-readme-stats.vercel.app/api?username=ramkrishna-12&show_icons=true&theme=transparent&hide_border=true" alt="GitHub stats" /> <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramkrishna-12&layout=compact&theme=transparent&hide_border=true" alt="Top languages" /> </p>

- 🌐 Portfolio: [ramkrishna-12.github.io/portfolio](https://ramkrishna-12.github.io/portfolio/)
- 💼 LinkedIn: [Ramkrishna](https://www.linkedin.com/in/ramkrishna-roy-barman-48391b16a/)


<div align="center">

*Ask me about: AWS · Terraform · CI/CD · Blue-Green deployments · MLOps*

</div>
