<div align="center">

# Sumit Kumar

**DevOps & Cloud Engineering | CI/CD | AWS | Docker | Kubernetes**

Final-year B.Tech CSE student at NIST University, seeking DevOps, Cloud and DevSecOps internships and fresher roles.

<a href="https://www.linkedin.com/in/sumitsmk/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"></a>
<a href="https://smk233.github.io/myportfolio"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=googlechrome&logoColor=00E5FF" alt="Portfolio"></a>
<a href="https://github.com/smk233"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

</div>

---

## About

I build and deploy containerised applications and CI pipelines, mostly with Docker, Jenkins and AWS. My projects cover the path from source code to a running server: image builds, reverse proxying, security scanning and automated delivery. I am strengthening my Kubernetes, Terraform and Linux skills.

---

## Featured Projects

| Project | What it demonstrates | Stack |
|---|---|---|
| [**TravelTales India**](https://github.com/smk233/traveltales-india) | Jenkins CI pipeline for a MERN travel blogging app: Trivy filesystem scan, SonarQube analysis with quality gate, Docker image build and push to Docker Hub, then CD job trigger | Jenkins, Docker, Docker Hub, Trivy, SonarQube, Node.js, React |
| [**Django Notes App: DevOps Deployment**](https://github.com/smk233/django-notes-app-devops) | Multi-container deployment on AWS EC2 with Nginx as reverse proxy in front of Gunicorn/Django and a MySQL database. Based on an open-source app by Shubham Londhe; the DevOps layer is my work | Docker, Docker Compose, Nginx, Gunicorn, MySQL, AWS EC2, Ubuntu |
| [**Personal Portfolio**](https://github.com/smk233/myportfolio) | Static site built with HTML, CSS and JavaScript, deployed through a GitHub Actions workflow (`CONFIRM`: S3 deployment) | HTML, CSS, JavaScript, GitHub Actions |

### TravelTales CI pipeline (from the repo's `Jenkinsfile`)

```mermaid
flowchart LR
    A[Git checkout] --> B[Trivy scan]
    B --> C[SonarQube analysis]
    C --> D[Quality gate]
    D --> E[Docker build]
    E --> F[Push to Docker Hub]
    F --> G[Trigger CD job]
```

---

## Tech Stack

**Used in my projects**

![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=2496ED)
![Jenkins](https://img.shields.io/badge/Jenkins-0D1117?style=for-the-badge&logo=jenkins&logoColor=D24939)
![AWS](https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Nginx](https://img.shields.io/badge/Nginx-0D1117?style=for-the-badge&logo=nginx&logoColor=009639)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=FCC624)
![Git](https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=2088FF)
![MySQL](https://img.shields.io/badge/MySQL-0D1117?style=for-the-badge&logo=mysql&logoColor=4479A1)
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=3776AB)
![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

**Currently learning**

![Kubernetes](https://img.shields.io/badge/Kubernetes-0D1117?style=for-the-badge&logo=kubernetes&logoColor=326CE5)
![Terraform](https://img.shields.io/badge/Terraform-0D1117?style=for-the-badge&logo=terraform&logoColor=844FBA)
![Java](https://img.shields.io/badge/Java-0D1117?style=for-the-badge&logo=openjdk&logoColor=ED8B00)

---

## CI/CD and DevSecOps Tooling

| Tool | Where I used it |
|---|---|
| Jenkins (declarative pipeline, shared library) | TravelTales India |
| Trivy | TravelTales India: filesystem scan stage |
| SonarQube | TravelTales India: analysis and quality gate |
| Docker Hub | TravelTales India: image registry |
| Docker Compose + Nginx | Django Notes App |
| GitHub Actions | Personal Portfolio |

---

## CSE Fundamentals

Linux (Ubuntu) administration, Git and GitHub workflows, networking basics, Java, data structures and algorithms, backend development.

---

## Currently Learning

- Kubernetes: deploying and operating workloads on a cluster
- Terraform: infrastructure as code for AWS
- Deeper AWS and Linux administration
- Java, DSA and backend development

---

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=smk233&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub stats">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=smk233&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top languages">

</div>

---

<div align="center">

Open to DevOps, Cloud and DevSecOps internships and fresher roles.
The best way to reach me is [LinkedIn](https://www.linkedin.com/in/sumitsmk/).

</div>
