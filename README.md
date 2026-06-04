<div align="center">

# Krishna Gove

### Senior Cloud & AI Engineer · Munich, Germany 🇩🇪

*Building production-grade AI systems, LLM platforms, and cloud-native infrastructure at enterprise scale*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/krishna-reddy-327463222)
[![GitHub followers](https://img.shields.io/github/followers/Krishna89287?style=flat-square&color=green)](https://github.com/Krishna89287)
[![AWS](https://img.shields.io/badge/AWS-Solutions_Architect-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://github.com/Krishna89287)
[![ML](https://img.shields.io/badge/AWS-ML_Specialty-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://github.com/Krishna89287)
[![Databricks](https://img.shields.io/badge/Databricks-ML_Professional-FF3621?style=flat-square&logo=databricks&logoColor=white)](https://github.com/Krishna89287)

</div>

---

## About Me

I am based in Munich, Germany, pursuing my Master's in Business Analytics and Data Science while building a career at the intersection of cloud infrastructure and artificial intelligence.

I have spent the last 10+ years designing and operating systems that actually matter in production. Not toy projects. Not demos. Real platforms handling real workloads at Audi AG, IABG, Infineon Technologies, Thomson Reuters, and IBM.

Right now I am working at **Audi AG** as part of the AIDA AI project within the VW Group, where I build LLM-powered backend services, implement EU AI Act compliance infrastructure including C2PA metadata signing and content provenance, and run Black Duck security scanning across AI pipelines on AWS Lambda. When you are shipping AI systems inside one of the world's largest automotive groups, the bar for reliability, security, and compliance is not optional it is the job.

Before Audi, I spent a year at **IABG** a German defence and aerospace company building production APIs and data pipelines for safety-critical systems. That experience taught me what it really means to engineer for reliability when failure is not an option.

I care deeply about the full stack of what it takes to ship great AI from the Terraform module that provisions the infrastructure, to the LangGraph agent that orchestrates the workflow, to the guardrails that make sure the LLM does not hallucinate in production.

Outside of work I spend my mornings at the gym, I love cooking Indian food in Munich, and I try to travel across Europe whenever I can.

---

## What I Build

### Large Language Models and Generative AI
I build production LLM systems not just API wrappers. RAG pipelines with proper chunking strategies to minimise hallucinations. Multi-agent systems using LangGraph and Model Context Protocol where agents actually complete tasks rather than loop forever. Evaluation frameworks that measure what matters faithfulness, relevance, groundedness. Fine-tuning pipelines on domain-specific data. I work with OpenAI, Anthropic Claude, and open-source models depending on what the use case actually needs.

### MLOps and AI Infrastructure
Training a model is 10% of the work. Getting it to production reliably is the other 90%. I build end-to-end MLOps pipelines experiment tracking with MLflow, model versioning and registry, automated retraining triggers, drift detection, and Kubernetes-based serving with HPA auto-scaling. If a model degrades in production at 2 AM, my observability stack catches it before the business does.

### Kubernetes and Cloud Platforms
I run Kubernetes in production not just locally. EKS and AKS clusters with stateful workloads including databases and Kafka brokers. Multi-cluster management with Rancher and vCluster. GitOps deployments with ArgoCD and Helm. I have managed cluster upgrades, node group replacements, and service mesh configurations with Istio without taking down production. AWS is my strongest cloud EKS, Lambda, S3, CDK, EventBridge, RDS. I also work extensively on Azure and GCP.

### EU AI Act and Responsible AI
I implemented C2PA content provenance signing for AI-generated assets at Audi AG one of the first production implementations of this standard within the VW Group. I understand what BaFin, MaRisk, DORA, and the EU AI Act actually require at the engineering level, not just the compliance level. Responsible AI is not a checkbox for me it is part of the architecture.

---

## Tech Stack

**LLMs and AI**
Python · LangChain · LangGraph · RAG Pipelines · Vector Databases · FAISS · Pinecone · Prompt Engineering · LLM Fine-tuning · LLM Evaluation · Hallucination Detection · MCP · OpenAI API · Anthropic Claude API · Hugging Face · C2PA

**MLOps and Data**
MLflow · Databricks · Apache Kafka · Apache Spark · PySpark · Feature Stores · Model Registry · Drift Detection · A/B Testing · Evidently AI · Prometheus · Grafana

**Cloud and Infrastructure**
AWS (EKS · Lambda · S3 · CDK · RDS · EventBridge · SageMaker · MSK) · Azure (AKS · AI Foundry · Azure OpenAI · DevOps) · GCP (GKE · BigQuery · Cloud Run) · Terraform · Ansible · Pulumi

**Kubernetes and Platform Engineering**
Kubernetes · EKS · AKS · GKE · Helm · ArgoCD · GitOps · Rancher · vCluster · Istio · Cert-manager · KEDA · HPA · Multi-cluster Operations · Stateful Workloads

**Backend and APIs**
Python · FastAPI · REST APIs · GraphQL · Pydantic · PostgreSQL · Redis · MongoDB · Docker · Microservices Architecture

**Security and Compliance**
EU AI Act · C2PA · GDPR · DORA · BaFin · DevSecOps · RBAC · Black Duck · Vulnerability Scanning · Data Sovereignty

---

## Featured Projects

**[AI Agent Framework](https://github.com/Krishna89287/ai-agent-framework)**
Production multi-agent orchestration using LangGraph and Model Context Protocol. Implements ReAct and self-reflection patterns. Includes tool registry, conversation memory management, and supervisor routing. Built for enterprise use cases where agents need to complete complex multi-step tasks reliably.

**[MLOps Pipeline](https://github.com/Krishna89287/mlops-pipeline)**
End-to-end ML pipeline from training to production monitoring. MLflow experiment tracking, model registry, FastAPI serving with Prometheus metrics, Kubernetes HPA auto-scaling, and statistical drift detection using KS test and PSI. Deployed on AWS EKS.

**[Kubernetes AI Platform](https://github.com/Krishna89287/kubernetes-ai-platform)**
Enterprise Kubernetes platform for AI and ML workloads. Terraform-provisioned EKS with GPU node groups for training. Helm charts with Prometheus and Grafana. ArgoCD GitOps workflows. Multi-cluster management patterns for stateful workloads.

**[LLM Evaluation and Guardrails](https://github.com/Krishna89287/llm-evaluation-guardrails)**
Production guardrails framework for responsible LLM deployment. Multi-strategy hallucination detection. EU AI Act risk categorisation engine covering prohibited use cases through to high-risk and limited-risk domains. GDPR compliance checks built in.

**[Cloud Infrastructure Automation](https://github.com/Krishna89287/cloud-infrastructure-automation)**
Multi-cloud infrastructure as code for AWS and GCP. Security-hardened S3 with KMS encryption and public access controls. Lambda for serverless ML inference. Automated cost optimisation scripts. Terraform with remote state and multi-region DR setup.

**[RAG LLM Toolkit](https://github.com/Krishna89287/rag-llm-toolkit)**
Collection of production RAG patterns, chunking strategies, retrieval optimisation techniques, and LLM evaluation scripts. Daily updates with new AI and ML techniques.

---

## Certifications

AWS Certified Solutions Architect - Associate · AWS Certified Machine Learning Specialty MLS-C01 · Databricks Certified Machine Learning Professional · Red Hat Certified Engineer RHCE · Red Hat Certified System Administrator RHCSA

---

## Currently

Working at **Audi AG** on the AIDA project LLM infrastructure, EU AI Act compliance, and AI security pipelines within the VW Group.

Completing **M.Sc. Business Analytics and Data Science** at EU Business School Munich. CGPA 3.8 out of 4.0.

Open to **Senior Cloud Engineer, AI Engineer, MLOps Engineer, or DevOps Engineer** roles in Germany and Europe from July 2026.

---

<div align="center">

*Munich, Germany · krishnagove88@gmail.com · Available July 2026*

</div>
