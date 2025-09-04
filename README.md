# DevOps Roadmap 2025 — Zero to Hero (Free Resources & Real Projects)

> A structured, beginner-friendly path from absolute zero to advanced DevOps, with weekly phases, learning goals, hands-on tasks, milestones, and curated free resources.

![Cover](https://media.licdn.com/dms/image/v2/D5612AQHYBOw7kXszEg/article-cover_image-shrink_720_1280/B56ZhfRRZ2H0AI-/0/1753945023519?e=1759968000&v=beta&t=z-CidgussMYcajzqfW_UbcJHRE89ljl1Vnno1cQBm38)

---

## Table of Contents
- [Who This Is For](#who-this-is-for)
- [How to Use This Roadmap](#how-to-use-this-roadmap)
- [Phases (Week-by-Week)](#phases-week-by-week)
  - [Phase 1: Foundations (Weeks 1–4)](#phase-1-foundations-weeks-1-4)
  - [Phase 2: Git & Collaboration (Weeks 5–6)](#phase-2-git--collaboration-weeks-5-6)
  - [Phase 3: Programming for DevOps (Weeks 7–8)](#phase-3-programming-for-devops-weeks-7-8)
  - [Phase 4: CI/CD (Weeks 9–12)](#phase-4-cicd-weeks-9-12)
  - [Phase 5: Containers & Docker (Weeks 13–15)](#phase-5-containers--docker-weeks-13-15)
  - [Phase 6: IaC with Terraform & Ansible (Weeks 16–19)](#phase-6-iac-with-terraform--ansible-weeks-16-19)
  - [Phase 7: Kubernetes (Weeks 20–24)](#phase-7-kubernetes-weeks-20-24)
  - [Phase 8: Monitoring, Logging & Security (Weeks 25–28)](#phase-8-monitoring-logging--security-weeks-25-28)
  - [Phase 9: Cloud & DevOps on AWS (Weeks 29–36)](#phase-9-cloud--devops-on-aws-weeks-29-36)
- [Bonus: Real Projects & Certifications (Weeks 37–48)](#bonus-real-projects--certifications-weeks-37-48)
- [GitHub Resource Links (Curated)](#github-resource-links-curated)
- [Final Milestone](#final-milestone)
- [Next Steps](#next-steps)
- [Attribution](#attribution)

---

## Who This Is For
- Students and freshers breaking into DevOps  
- Developers, SysAdmins, and IT pros upskilling to DevOps  
- Anyone who wants a **clear, no-fluff path** with **free** resources and **real projects**

---

## How to Use This Roadmap
1. **Go phase by phase**, week by week.  
2. **Do every practice task** — build muscle memory.  
3. **Track milestones** to know when to move forward.  
4. **Ship small projects** along the way and collect them in a portfolio repo.

> Tip: Create a `progress.md` in your repo and tick off tasks as you complete them.

---

## Phases (Week-by-Week)

### Phase 1: Foundations (Weeks 1–4)
**Goal:** Understand DevOps, SDLC, and get comfortable in Linux.

**Learn**
- What is DevOps? SDLC & CI/CD basics  
- Software development basics (versioning, releases, bug tracking)  
- Linux fundamentals & shell scripting  
- Networking basics (DNS, HTTP, ports, IPs)

**Practice**
- Set up a Linux VM or use [WSL](https://learn.microsoft.com/en-us/windows/wsl/)  
- Use `ls`, `grep`, `awk`, `sed`, `ssh`, `curl`, etc.  
- Write shell scripts (e.g., folder backup)

**Milestone**
- Navigate Linux confidently and write basic shell scripts  
- Explain DevOps and CI/CD at a high level

**Free Resources**
- https://learn.microsoft.com/en-us/devops/  
- https://ubuntu.com/tutorials/command-line-for-beginners#1-overview  
- https://skillsforall.com/course/networking-basics  
- https://ryanstutorials.net/bash-scripting-tutorial/

---

### Phase 2: Git & Collaboration (Weeks 5–6)
**Goal:** Master Git & GitHub.

**Learn**
- Git basics (clone/commit/push/pull/branch/merge)  
- GitHub workflows (PRs, forks, Actions)  
- Intro to GitOps principles

**Practice**
- Create a repo, branch strategy, merge via PR  
- Resolve merge conflicts  
- Add a simple CI workflow with GitHub Actions (lint/test)

**Milestone**
- Confident Git & GitHub usage with branching strategies  
- Auto lint/test via GitHub Actions

**Free Resources**
- https://git-scm.com/book/en/v2  
- https://lab.github.com/  
- https://education.github.com/git-cheat-sheet-education.pdf

---

### Phase 3: Programming for DevOps (Weeks 7–8)
**Goal:** Automate tasks with Python and work with configs/APIs.

**Learn**
- Python basics for automation  
- JSON, YAML, APIs, parsing  
- CLI tools: `curl`, `jq`, `httpie`

**Practice**
- Python script to call an API and process results  
- Parse YAML config from Python

**Milestone**
- Automate file & API tasks with Python  
- Confident writing YAML for tools (e.g., GitHub Actions)

**Free Resources**
- https://automatetheboringstuff.com/  
- Python for DevOps (YouTube series)  
- JSON & YAML crash course (YouTube)

---

### Phase 4: CI/CD (Weeks 9–12)
**Goal:** Build & run pipelines.

**Learn**
- Jenkins fundamentals  
- Advanced GitHub Actions  
- CI/CD stages: build → test → deploy

**Practice**
- Install Jenkins locally (or use playgrounds)  
- Build a CI pipeline that builds, tests, and packages your app

**Milestone**
- Working CI pipeline on Jenkins/GitHub Actions  
- Understand end-to-end CI/CD flow

**Free Resources**
- https://www.jenkins.io/doc/  
- https://docs.github.com/en/actions  
- https://cloud.google.com/learn/what-is-ci-cd

---

### Phase 5: Containers & Docker (Weeks 13–15)
**Goal:** Containerize apps and manage multi-container environments.

**Learn**
- Docker concepts: images, containers, networks, volumes  
- Dockerfile & multi-stage builds  
- Docker Compose for local orchestration

**Practice**
- Containerize a Flask or Node.js app  
- Use Compose for app + DB

**Milestone**
- Write Dockerfiles and build/run images  
- Understand image layers & multi-stage builds

**Free Resources**
- https://training.play-with-docker.com/  
- https://docs.docker.com/get-started/  
- FreeCodeCamp Docker full course (YouTube)

---

### Phase 6: IaC with Terraform & Ansible (Weeks 16–19)
**Goal:** Provision and configure infra automatically.

**Learn**
- IaC overview  
- Terraform: providers, resources, variables, state  
- Ansible: playbooks, inventories, roles

**Practice**
- Provision EC2 with Terraform  
- Configure EC2 with Ansible (install Apache, deploy sample app)

**Milestone**
- Deploy infra with Terraform  
- Configure servers with Ansible playbooks

**Free Resources**
- https://developer.hashicorp.com/terraform/tutorials  
- https://docs.ansible.com/ansible/latest/getting_started/index.html  
- FreeCodeCamp Ansible + Terraform (YouTube)

---

### Phase 7: Kubernetes (Weeks 20–24)
**Goal:** Orchestrate containerized applications.

**Learn**
- K8s architecture (pods, deployments, services)  
- `kubectl` essentials  
- YAML manifests & controllers  
- Local clusters: Minikube / kind

**Practice**
- Deploy your Dockerized app to local K8s  
- Use ConfigMaps, Secrets, Services

**Milestone**
- Deploy and scale apps in K8s  
- Troubleshoot pods and understand core resources

**Free Resources**
- https://kubernetes.io/docs/  
- KodeKloud K8s labs  
- FreeCodeCamp K8s full course (YouTube)

---

### Phase 8: Monitoring, Logging & Security (Weeks 25–28)
**Goal:** Get visibility and bake in security.

**Learn**
- Prometheus + Grafana basics  
- ELK Stack (Elasticsearch, Logstash, Kibana)  
- DevSecOps 101 (vulnerabilities, secret scanning)

**Practice**
- Instrument app with Prometheus & visualize in Grafana  
- Send logs to ELK  
- Scan images with Trivy or Snyk

**Milestone**
- Basic observability stack running  
- Apply container/security scanning in CI

**Free Resources**
- https://prometheus.io/docs/introduction/overview/  
- https://www.elastic.co/what-is/elk-stack  
- https://owasp.org/www-project-top-ten/

---

### Phase 9: Cloud & DevOps on AWS (Weeks 29–36)
**Goal:** Apply everything in the cloud.

**Learn**
- AWS fundamentals: EC2, S3, IAM, VPC, CloudWatch  
- DevOps services: CodePipeline, CodeDeploy, CodeBuild

**Practice**
- Host a static site on S3  
- Deploy to EC2 via CI/CD integrated with GitHub

**Milestone**
- Launch & manage AWS resources  
- Cloud CI/CD fully integrated

**Free Resources**
- https://aws.amazon.com/free/  
- AWS DevOps Learning Plan  
- https://docs.aws.amazon.com/

---

## Bonus: Real Projects & Certifications (Weeks 37–48)

**Build Projects**
- Full-stack app with CI/CD + Docker + Terraform on AWS  
- Your **DevOps portfolio repo** (collect all projects/pipelines)  
- Contribute to DevOps open-source tools

**Certifications (Optional)**
- **AWS Certified DevOps Engineer**  
- **Docker Certified Associate**  
- **Certified Kubernetes Administrator (CKA)**

---

## GitHub Resource Links (Curated)

**Phase 1 — Linux & Shell**
- **Awesome Shell** — https://github.com/alebcay/awesome-shell  
- **Shell Scripting Tutorial Repo** — https://github.com/sohomghosh/Unix-Linux-Shell-Scripting

**Phase 2 — Git & GitHub**
- **Git-it** — https://github.com/jlord/git-it-electron  
- **GitHub Training Kit** — https://github.com/github/training-kit

**Phase 3 — Python for DevOps**
- **Python DevOps Examples** — https://github.com/roxsross/Python-DevOps  
- **Automate the Boring Stuff (code)** — https://github.com/asweigart/automateboringstuff

**Phase 4 — CI/CD**
- **Jenkins Pipeline Examples** — https://github.com/jenkinsci/pipeline-examples  
- **GitHub Actions Starter Workflows** — https://github.com/actions/starter-workflows

**Phase 5 — Docker & Containers**
- **Docker Labs** — https://github.com/docker/labs  
- **Docker Curriculum** — https://github.com/prakhar1989/docker-curriculum

**Phase 6 — Terraform & Ansible**
- **Terraform Guides** — https://github.com/hashicorp/terraform-guides  
- **Ansible Examples** — https://github.com/ansible/ansible-examples

**Phase 7 — Kubernetes**
- **Kubernetes the Hard Way** — https://github.com/kelseyhightower/kubernetes-the-hard-way  
- **Awesome Kubernetes** — https://github.com/ramitsurana/awesome-kubernetes

**Phase 8 — Monitoring & Security**
- **Prometheus Example Setups** — https://github.com/prometheus/prometheus/tree/main/documentation/examples  
- **OWASP Docker Security Cheatsheet** — https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Docker_Security_Cheat_Sheet.md  
- **Trivy** — https://github.com/aquasecurity/trivy

**Phase 9 — DevOps on Cloud**
- **AWS DevOps Essentials** — https://github.com/aws-samples/aws-devops-essential  
- **AWS CloudFormation Templates** — https://github.com/awslabs/aws-cloudformation-templates

---

## Final Milestone
- ✅ 2+ real-world projects shipped  
- ✅ Confident with Docker, K8s, IaC, CI/CD in cloud pipelines  
- ✅ Portfolio ready for interviews & freelance/job applications

---

## Next Steps
- 🔖 Bookmark this roadmap & review weekly  
- 🛠️ Start your first mini-project today  
- 💬 Share with fellow learners and grow together  
- 📥 Need help? Open an issue or discussion in your repo

---

## Attribution
Based on: **“DevOps Roadmap 2025: Zero to Hero Guide for Beginners to Advanced with Free Resources & Real Projects”**
