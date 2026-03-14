# AI-Powered Support Automation Platform (SaaS)

> Multi-tenant, AI-driven customer support automation platform integrating LLM-powered responses with scalable backend APIs.

## Overview

Designed and built a multi-tenant AI-driven customer support automation platform that integrates LLM-powered responses with scalable backend APIs. The platform allows companies to automatically answer customer queries, summarize tickets, and route issues to the correct department.

## Tech Stack

- **Backend:** Python (FastAPI) with async request processing
- **Database:** PostgreSQL + Redis (high-throughput caching)
- **AI/ML:** Retrieval-Augmented Generation (RAG) pipelines with open-source LLMs
- **Infrastructure:** Docker, Kubernetes on AWS EKS
- **CI/CD:** GitHub Actions
- **Message Queue:** RabbitMQ
- **Observability:** Prometheus + Grafana, ELK Stack

## Architecture

```
[API Gateway] --> [FastAPI Microservices] --> [RAG Pipeline]
                        |                          |
                   [PostgreSQL]              [LLM Engine]
                        |                          |
                    [Redis Cache]         [Knowledge Base]
                        |
              [RabbitMQ Queue] --> [Background Workers]
```

## Key Features

- Multi-tenant SaaS architecture supporting 500+ organizations
- RAG-based intelligent response generation
- Automated ticket routing and classification
- Rate-limited API gateway with tenant isolation
- Real-time monitoring and alerting

## Impact & Metrics

| Metric | Value |
|--------|-------|
| Automated queries/day | 50,000+ |
| Manual workload reduction | ~60% |
| Avg response latency | <180 ms |
| Organizations supported | 500+ |

## Skills & Technologies

`FastAPI` `Microservices Architecture` `PostgreSQL` `Docker & Kubernetes` `AI/LLM Integration` `RabbitMQ` `Redis` `AWS EKS` `GitHub Actions` `Prometheus`

## Author

**Swati Kanta Mishra**  
Senior Backend Engineer | Python (FastAPI, Django) | DevOps | Cloud (AWS/GCP)  
[LinkedIn](https://www.linkedin.com/in/swatikantamishra/)
