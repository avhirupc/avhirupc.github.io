---
layout: about
permalink: /
title: <strong>Avhirup</strong> Chakraborty
description: Senior ML Platform & Infrastructure Engineer at Amazon Music, Berlin

profile:
  align: right
  image: avhirup.jpg

news: true
social: true
---

I'm a senior software engineer at **Amazon Music** in Berlin. My work sits at the intersection of **ML infrastructure** and **distributed systems** — building the foundational platforms that 10+ ML and data science teams depend on to ship models and features to production. Over the past four years, I've built and operated the Feature Store platform that powers personalization for millions of customers across five global regions — and increasingly moved into ML-native work like evaluation frameworks, vector serving, and model deployment infrastructure.

At Amazon, I've:

- Built and operated the **ML feature store** serving real-time features to all personalization models, and built batch feature processing pipelines and streaming ingestion (SQS & Redis) reducing feature data reflection from 24h to 2min. Resolved hot-key distribution and replication lag at scale. My work was [featured in the AWS ElastiCache blog](https://aws.amazon.com/blogs/database/build-an-ultra-low-latency-online-feature-store-for-real-time-inferencing-using-amazon-elasticache-for-redis/).
- Designed multi-petabyte storage tiering for feature data: Online (hot (Redis cluster) →warm (DynamoDB))and Offline (S3) – optimizing for read latency, write throughput, cost, and data durability. Built internal SQL-based data access tooling for ad-hoc querying across storage layers.
- Built a **FAISS-based embedding serving platform** for embedding lookups at sub-10ms latency.
- Designed the **Isolated Multi-Tenant architecture** that turned a single service into a multi-tenant self-service platform for 30+ teams with independent scaling and fault isolation
- Led **FinOps** cutting infrastructure costs by 48% YOY via compression, storage tiering (Redis → DynamoDB → S3), and anomaly detection across 30+ metrics
- Reduced **p99 latency by 70%** (50ms → 11ms) through profiling and optimizing Redis, DynamoDB, and network I/O
- Built load testing and Gameday infrastructure for **5x TPS growth**, established observability with canary deployments and automated alerting
- Mentored 4+ engineers, helped promote 2 to next level

Before Amazon, I built **NLP-powered search systems** at [Embibe](https://www.embibe.com/) (Jio Platform) handling over a million queries a day — including intent detection, entity recognition, and question recommendation using BERT embeddings over 1.5M items. Earlier, at [Arya.ai](https://arya.ai/), I built ML models for insurance claim automation that reduced turnaround from four days to 30 seconds, saving $40,000/month.

I've also spent time in research — working with [Dr. Anurag Mittal](https://www.cse.iitm.ac.in/~amittal/) at **IIT Madras** on generative models for image inpainting, and at **Caterpillar** on OCR and text-to-image generation.

I care about building systems that are simple, reliable, and cost-efficient. I believe the best ML platforms are the ones that get out of the way — letting data scientists focus on models while the infrastructure handles the rest.

### What I work with

- **Languages:** Python, Java, TypeScript, SQL
- **ML & Data:** Feature Stores, Real-time ML Serving, PyTorch, TensorFlow, FAISS, SageMaker, Spark, Airflow
- **Infrastructure:** AWS (ECS, ElastiCache, DynamoDB, SQS, S3), Docker, CDK, CI/CD
- **Practices:** Distributed systems design, observability, cost optimization, A/B testing, mentoring

### Let's connect

I'm always open to conversations about ML infrastructure, platform engineering, and distributed systems. Feel free to reach out via [email](mailto:avhirupchakraborty@gmail.com) or [LinkedIn](https://www.linkedin.com/in/avhirup-chakraborty/).
