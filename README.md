<!--
**jeonck/jeonck** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## ✨ Hey! Nice to see you.
Welcome to my page👋, I'm CK.

### 🌐 Portfolio : **[jeonck.metacog.co.kr](https://jeonck.metacog.co.kr/)**
Platform engineering and cloud infrastructure, 12+ years across telecom, government, and enterprise.
Selected work, the platforms I run in public, and a [resume (PDF)](https://jeonck.metacog.co.kr/CK-Jeon-Resume.pdf).
Based in Austin, TX.

## 📘 Book : [Reliability at Scale](https://www.amazon.com/dp/B0HLBNJM6T)
**Advanced SRE for Staff Engineers** (2026, 354 pages). Built on questions carried through 16 years of running mission-critical telecom platforms.

Most serious reliability problems do not come from missing tools. They come from broken feedback loops.
- **Technical loops** grow an outage and hold it in place : retry storms that backoff cannot fix, outages that outlive their trigger.
- **Organizational loops** make it happen again : error budgets that do not bind, postmortems that close every action item and change nothing.

Fourteen chapters covering blast radius (cells, shuffle sharding), telemetry cost and gray failure, capacity by queueing theory, safe config delivery, incident command, and a side-by-side reading of 16 public postmortems.

## 🌱 Interests  
- K8s  
  - System Implementation, AKS usecase  
- Web Service  
  - Frontend, Backend  
- Artificial Intelligence  
  - Agentic AI, Agent AI Security, LLM, GPTs, Open AI API
  - AI using know-how & Productivity : [SKILL](https://skill.metacog.co.kr/)
  - Video Generation  
    - [Programmatic video generation using Remotion](https://skill.metacog.co.kr/s/code-explainer-video/)  

## 🔭 Careers    
- Project Management : Metaverse, Endpoint Security Platform, LBS, IoT
  - Confluence, Jira, Slack 
- Platform Engineering
  - System Implementation(K8s) : Digital twin data platform, Persona AI platform, Metaverse Platform
  - Infrastructure : on-premise server, K8s(air-gapped), AKS/Azure, AWS, Terraform
  - CI/CD automation : GitLab, ArgoCD, Nexus, Gitea, Bitbucket, Github Actions, Jenkins
  - AI platform : LLM API deployment, Containerized workloads, Jupyter, qdrant, langflow, langfuse 
  - Data platform : GPU Server, LLM deployment, mysql, redis, posgresql, qdrant, kafka, minIO, pinot, ceph
  - Observability : opensearch, prometheus, grafana, EFK, Datadog 
- Development
  - Python Frontend(streamlit), Python Backend(FastAPI), Spring boot, MVC
  - Svelte
- Service Launching : Metaverse(ifland studio), International Roaming(Baro Roaming), Short Message Service

## 🛠️ Platforms I run in public
- [DevOps Professional Playbook](https://devops.metacog.co.kr/) : 13-competency evidence framework mapped to DORA metrics
- [Framework Thinking](https://fw-thinking.metacog.co.kr/) : structured IT knowledge system for practitioners
- [Cybersecurity Knowledge Base](https://cybersecurity.metacog.co.kr/) : security templates and concept reference across 11 domains
- [CuraDevOps](https://curadevops.metacog.co.kr/) / [CuraSec](https://curasec.metacog.co.kr/) : daily DevOps and security intelligence with per-role verdicts
- [Release Board](https://rel-mgmt.metacog.co.kr/) : Go / NoGo verdicts across tracked DevOps products
- [Handson](https://handson.metacog.co.kr/) : install manuals, work procedures, troubleshooting guides
- [Claude Skill Hub](https://skill.metacog.co.kr/) : installable agent skills for site builders, content pipelines, dev tooling

## 🧪 Hands-on labs
Labs I run and write up at [handson.metacog.co.kr](https://handson.metacog.co.kr/), 58 verified since August. The six below ran on real systems, not simulations: a real macOS machine, or real AWS infrastructure built with Terraform. These are lab results, not production claims.

| Lab | Result | Ran on |
|---|---|---|
| [Three-node Kubernetes with kubeadm](https://handson.metacog.co.kr/#/note/01-install~onprem-3node-kubeadm-ubuntu) | Three Ready nodes and every pod Running, yet every calico-node sat at 0/1. Two blocked ports were the cause | AWS, built with Terraform ([lab20](https://github.com/jeonck/terraform-aws-lab/tree/main/lab20-onprem-k8s-verify)) |
| [GitOps delivery, GitLab CI to Argo CD](https://handson.metacog.co.kr/#/note/01-install~gitlab-ci-argocd-fastapi-onprem) | The pipeline holds no kubeconfig, and the deploy check is the running pod's image digest | AWS, built with Terraform ([lab21](https://github.com/jeonck/terraform-aws-lab/tree/main/lab21-gitlab-argocd-verify)) |
| [Terraform remote state locking](https://handson.metacog.co.kr/#/note/02-runbook~terraform-remote-backend-lock-import) | On S3 the lock is one conditional PUT. Garage ignores it, so `use_lockfile` never refuses anyone | macOS |
| [SLO burn-rate alerting](https://handson.metacog.co.kr/#/note/01-install~slo-error-budget-burn-rate) | 50% injected errors paged in two minutes, and a healthy service recorded no SLI until `or vector(0)` | macOS |
| [Container image size](https://handson.metacog.co.kr/#/note/01-install~container-image-size-and-what-breaks) | 1.03 GB down to 8.37 MB (123x), and the smallest image silently lost HTTPS and timezones | macOS |
| [Proxmox on rented bare metal](https://handson.metacog.co.kr/#/note/01-install~proxmox-on-ec2-bare-metal) | 42 minutes and $0.29, and the snapshot loop reported plausible timings while doing nothing | AWS, built with Terraform |

## 📜 Credentials & Patents
- **[Professional Engineer in Information Technology (기술사)](https://encykorea.aks.ac.kr/Article/E0008307)** : Korean national license. Holders are formally commissioned as evaluation committee members on government and public-sector technology projects.
- **[Principal Information Systems Auditor (수석감리사)](https://auditor.nia.or.kr/front/main/main.do)** : Korean national license. Only Principal-level auditors may lead national information system audit programs, a standing conferred by the Professional Engineer license.
- AWS Certified Solutions Architect / CCNP / RHCSA / ISTQB

**10 Korean patents, 7 as sole inventor.** Four selected:
- [KR20230013443A](https://patents.google.com/patent/KR20230013443A/en) : Intelligent Endpoint Security Management (2023, co-inventor)
- [KR20230018724A](https://patents.google.com/patent/KR20230018724A/en) : Automated Security Information Categorization (2023, co-inventor)
- [KR20220035711A](https://patents.google.com/patent/KR20220035711A) : Organizational Chart Automation for Security (2022, co-inventor)
- [KR101567993B1](https://patents.google.com/patent/KR101567993B1/en) : Application Service Quality Indicator System (2015, sole inventor)

## ⚡ Community Activities  
- [DEVOCEAN](https://devocean.sk.com/) Master  
  
## 📫 Contacts   
- [Portfolio](https://jeonck.metacog.co.kr/)  
- [LinkedIn](https://www.linkedin.com/in/metacog/)  

## 🔭 My latest posts
- [Public Blog](https://jeonck.github.io/us-start/blog)
- [Personal Blog](https://insight.metacog.co.kr/)
