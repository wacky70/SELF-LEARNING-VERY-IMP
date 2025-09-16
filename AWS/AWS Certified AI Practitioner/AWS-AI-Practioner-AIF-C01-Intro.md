# AWS CLOUD AI PRACTITIONER

## Study Structure Overview
This repository is organized into individual domain folders for comprehensive study preparation:

### 📁 Domain Folders
1. **[Domain-1-Fundamentals-of-AI-ML/](./Domain-1-Fundamentals-of-AI-ML/)** - Fundamentals of AI and ML
2. **[Domain-2-Fundamentals-of-Generative-AI/](./Domain-2-Fundamentals-of-Generative-AI/)** - Fundamentals of Generative AI
3. **[Domain-3-Applications-of-Foundation-Models/](./Domain-3-Applications-of-Foundation-Models/)** - Applications of Foundation Models
4. **[Domain-4-Guidelines-for-Responsible-AI/](./Domain-4-Guidelines-for-Responsible-AI/)** - Guidelines for Responsible AI
5. **[Domain-5-Security-Compliance-Governance/](./Domain-5-Security-Compliance-Governance/)** - Security, Compliance, and Governance for AI Solutions

---

## Quick Reference

### Exam Domains and Weightings
- **Domain 1**: Fundamentals of AI and ML (20%)
- **Domain 2**: Fundamentals of Generative AI (24%)
- **Domain 3**: Applications of Foundation Models (28%)
- **Domain 4**: Guidelines for Responsible AI (14%)
- **Domain 5**: Security, Compliance, and Governance (14%)

## Table of Contents
1. [Domain 1: Fundamentals of AI and ML](#domain-1-fundamentals-of-ai-and-ml)
2. [Domain 2: Fundamentals of Generative AI](#domain-2-fundamentals-of-generative-ai)
3. [Domain 3: Applications of Foundation Models](#domain-3-applications-of-foundation-models)
4. [Domain 4: Guidelines for Responsible AI](#domain-4-guidelines-for-responsible-ai)
5. [Domain 5: Security, Compliance, and Governance for AI Solutions](#domain-5-security-compliance-and-governance-for-ai-solutions)

---

## Domain 1: Fundamentals of AI and ML

### Task Statement 1.1: Explain basic AI concepts and terminologies
- Define basic AI terms (AI, ML, deep learning, neural networks, computer vision, NLP, model, algorithm, training/inferencing, bias, fairness, fit, LLM)
- Similarities and differences between AI, ML, and deep learning
- Types of inferencing (batch, real-time)
- Types of data in AI models (labelled/unlabelled, tabular, time-series, image, text, structured/unstructured)
- Supervised, unsupervised, and reinforcement learning

### Task Statement 1.2: Identify practical use cases for AI
- Applications where AI/ML provide value (decision making, scalability, automation)
- When AI/ML is not appropriate (cost-benefit, specific outcomes)
- Selecting ML techniques (regression, classification, clustering)
- Real-world AI applications (computer vision, NLP, speech recognition, recommendation, fraud detection, forecasting)
- AWS managed AI/ML services (SageMaker, Transcribe, Translate, Comprehend, Lex, Polly)

### Task Statement 1.3: Describe the ML development lifecycle
- ML pipeline components (data collection, EDA, pre-processing, feature engineering, training, tuning, evaluation, deployment, monitoring)
- Sources of ML models (open-source, custom)
- Using models in production (managed API, self-hosted API)
- AWS services for ML pipeline (SageMaker, Data Wrangler, Feature Store, Model Monitor)
- MLOps concepts (experimentation, repeatability, scalability, technical debt, production readiness, monitoring, re-training)
- Model performance metrics (accuracy, AUC, F1) and business metrics (cost/user, dev costs, feedback, ROI)

---

## Domain 2: Fundamentals of Generative AI

### Task Statement 2.1: Explain basic concepts of generative AI
- Foundational concepts (tokens, chunking, embeddings, vectors, prompt engineering, transformer LLMs, foundation models, multi-modal, diffusion models)
- Use cases (image/video/audio generation, summarization, chatbots, translation, code generation, customer service, search, recommendation)
- Foundation model lifecycle (data/model selection, pre-training, fine-tuning, evaluation, deployment, feedback)

### Task Statement 2.2: Capabilities and limitations of generative AI
- Advantages (adaptability, responsiveness, simplicity)
- Disadvantages (hallucinations, interpretability, inaccuracy, nondeterminism)
- Factors for model selection (type, performance, capabilities, constraints, compliance)
- Business value/metrics (cross-domain, efficiency, conversion, revenue/user, accuracy, CLV)

### Task Statement 2.3: AWS infrastructure for generative AI
- AWS services/features (SageMaker JumpStart, Bedrock, PartyRock, Q)
- Advantages of AWS generative AI (accessibility, efficiency, cost, speed, business objectives)
- AWS infrastructure benefits (security, compliance, responsibility, safety)
- Cost trade-offs (responsiveness, availability, redundancy, performance, regional, token pricing, throughput, custom models)

---

## Domain 3: Applications of Foundation Models

### Task Statement 3.1: Design considerations for foundation model applications
- Criteria for pre-trained models (cost, modality, latency, multi-lingual, size, complexity, customization, input/output length)
- Inference parameters (temperature, input/output length)
- Retrieval Augmented Generation (RAG) and business applications (Bedrock, knowledge base)
- AWS services for embeddings/vector databases (OpenSearch, Aurora, Neptune, DocumentDB, RDS for PostgreSQL)
- Cost trade-offs for customization (pre-training, fine-tuning, in-context, RAG)
- Role of agents (Agents for Bedrock)

### Task Statement 3.2: Prompt engineering techniques
- Concepts/constructs (context, instruction, negative prompts, latent space)
- Techniques (chain-of-thought, zero-shot, single-shot, few-shot, templates)
- Benefits/best practices (quality, experimentation, guardrails, discovery, specificity, concision, multiple comments)
- Risks/limitations (exposure, poisoning, hijacking, jailbreaking)

### Task Statement 3.3: Training and fine-tuning foundation models
- Key elements (pre-training, fine-tuning, continuous pre-training)
- Fine-tuning methods (instruction tuning, domain adaptation, transfer learning, continuous pre-training)
- Data preparation (curation, governance, size, labelling, representativeness, RLHF)

### Task Statement 3.4: Evaluating foundation model performance
- Evaluation approaches (human, benchmarks)
- Metrics (ROUGE, BLEU, BERT Score)
- Meeting business objectives (productivity, engagement, task engineering)

---

## Domain 4: Guidelines for Responsible AI

### Task Statement 4.1: Responsible AI development
- Features (bias, fairness, inclusivity, robustness, safety, veracity)
- Tools (Guardrails for Bedrock)
- Responsible model selection (environmental, sustainability)
- Legal risks (IP, bias, trust, end user risk, hallucinations)
- Dataset characteristics (inclusivity, diversity, curation, balance)
- Effects of bias/variance (demographics, inaccuracy, over/underfitting)
- Tools for bias/trust/truth (label analysis, audits, subgroup analysis, SageMaker Clarify, Model Monitor, Augmented AI)

### Task Statement 4.2: Transparent and explainable models
- Transparent/explainable vs. non-transparent models
- Tools (SageMaker Model Cards, open-source, data, licensing)
- Safety vs. transparency trade-offs (interpretability, performance)
- Human-centred design principles

---

## Domain 5: Security, Compliance, and Governance for AI Solutions

### Task Statement 5.1: Securing AI systems
- AWS services/features (IAM, encryption, Macie, PrivateLink, shared responsibility)
- Source citation/data origins (lineage, cataloguing, Model Cards)
- Secure data engineering (quality, privacy, access control, integrity)
- Security/privacy considerations (app security, threat detection, vulnerability, infrastructure, prompt injection, encryption)

### Task Statement 5.2: Governance and compliance regulations
- Compliance standards (ISO, SOC, accountability laws)
- AWS services/features (Config, Inspector, Audit Manager, Artifact, CloudTrail, Trusted Advisor)
- Data governance strategies (lifecycles, logging, residency, monitoring, retention)
- Governance protocols (policies, review cadence/strategies, frameworks, transparency, training)
