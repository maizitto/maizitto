<h1 align="center">Hi, I'm Matteo</h1>
<h3 align="center">Backend and AI Engineer from Italy</h3>

<p align="center">
I build and run production systems: partner integrations, data pipelines and AI agents.<br>
Over ten years of programming, the last two at Vikey, a SaaS platform for property managers, hotels and vacation rentals.
</p>

## What I work on

**Integrations.** 30+ partner APIs in a multi-tenant platform (PMS and OTA systems, Stripe, Zoho CRM, Intercom). Webhook signature checks, event deduplication, idempotent operations, retry with backoff.

**Data.** ETL pipelines, MySQL with Redis caching, BigQuery, and Apache Superset dashboards for operations, sales and campaign metrics.

**AI agents.** RAG, tool calling, MCP servers, model serving with vLLM and Ollama. I care most about the boring parts: measuring if the agent works, and keeping it safe.

**Infrastructure.** GKE on GCP, Docker, Cloud Armor (WAF and DDoS policies), log analysis.

## Things I built at work

Most of my work is in private repositories, so this is the short version.

- **AI support agent.** A RAG agent integrated with Intercom that answers customers and also works as a copilot for the support team. It handles 5,000+ conversations a month, with about half resolved without human intervention. Every conversation gets an outcome tag, so I can see where it fails.
- **Commercial task engine.** Built after the CEO asked to improve how the sales team works. It reads churn and subscription data every morning, creates prioritized tasks in the CRM, and measures which ones turned into new subscriptions. It ran daily for a year.
- **Shared tool layer for agents.** About 31 tools that let AI agents read live account data, with read-only and destructive tools kept separate. Other engineers in my team reused it for a different assistant.

## How I work

- I measure things. If I cannot say how I know it works, it is not finished.
- Safety rules go in code, not in prompts. Access checks run before a tool runs.
- I write down architecture, decisions and the weak points I already know about.

## Languages and tools

<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
<a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>
<a href="https://redis.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/redis/redis-icon.svg" alt="redis" width="40" height="40"/> </a>
<a href="https://cloud.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a>
<a href="https://kubernetes.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a>
<a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a>
<a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a>
<a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a>
</p>

Also: SQLAlchemy, BigQuery, Firestore, Apache Superset, Metabase, Pandas, OpenAI API, vLLM, Ollama, Cloud Armor.

## Outside of code

I run, swim, and played basketball for years. I lived in Paris and Utrecht for a few months each, and I would happily go back.

## Connect with me

<p align="left">
<a href="https://linkedin.com/in/matteo-masitto" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="matteo-masitto" height="30" width="40" /></a>
&nbsp; dev@masitto.it
</p>
