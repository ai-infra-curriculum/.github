# Curriculum Cross-Reference Guide

**AI Infrastructure Engineering Learning Paths**

This document maps the relationships between Junior Engineer and Engineer track curricula, helping learners understand progression paths and prerequisite relationships.

## Quick Navigation

- [Track Comparison](#track-comparison)
- [Module Mapping](#module-mapping)
- [Skill Progression](#skill-progression)
- [Learning Paths](#learning-paths)
- [Time Estimates](#time-estimates)

---

## Track Comparison

### Junior Engineer Track
**Target Audience**: Entry-level engineers, bootcamp graduates, career changers

**Duration**: 300-400 hours (3-6 months full-time)

**Focus**: Foundational skills for supporting AI/ML infrastructure

**Outcome**: Ready for Junior AI Infrastructure Engineer roles

### Engineer Track
**Target Audience**: Engineers with 1-2 years experience, Junior track graduates

**Duration**: 400-500 hours (4-7 months full-time)

**Focus**: Production ML systems, advanced orchestration, optimization

**Outcome**: Ready for mid-level AI Infrastructure Engineer roles

---

## Module Mapping

This table shows how Junior modules map to Engineer modules and indicates progression paths.

| Junior Module | Junior Topics | Engineer Module | Engineer Topics | Progression Type |
|---------------|--------------|-----------------|-----------------|------------------|
| **Mod 001: Python Fundamentals** | Basic Python, OOP, testing | **Mod 101: Foundations** | Advanced Python, async, ML frameworks | **Deepening** |
| **Mod 002: Linux Essentials** | Basic commands, shell scripting | *Integrated throughout* | Advanced scripting, system tuning | **Continuous** |
| **Mod 003: Git Version Control** | Basic Git, branches, PRs | *Integrated in MLOps* | Advanced workflows, CI/CD | **Applied** |
| **Mod 004: ML Basics** | PyTorch/TF inference, model formats | **Mod 101: Foundations** | Training, optimization, distributed | **Deepening** |
| **Mod 005: Docker Containers** | Dockerfile, compose, basics | **Mod 103: Containerization** | Multi-stage, optimization, registries | **Deepening** |
| **Mod 006: Kubernetes Intro** | Pods, Services, Deployments | **Mod 104: Kubernetes** | StatefulSets, Operators, production | **Deepening** |
| **Mod 007: APIs & Web Services** | Flask, REST basics | **Mod 101: Foundations** | FastAPI, async, production APIs | **Deepening** |
| **Mod 008: Databases & SQL** | PostgreSQL basics, queries | *Integrated throughout* | Advanced queries, replication, tuning | **Applied** |
| **Mod 009: Monitoring Basics** | Prometheus, Grafana basics | **Mod 108: Monitoring** | Advanced observability, tracing, SLOs | **Deepening** |
| **Mod 010: Cloud Platforms** | AWS basics, EC2, S3, IAM | **Mod 102: Cloud Computing** | Multi-cloud, cost optimization, managed ML | **Deepening** |
| *Not covered* | — | **Mod 105: Data Pipelines** | Airflow, streaming, ETL | **New** |
| *Not covered* | — | **Mod 106: MLOps** | CI/CD for ML, experiment tracking | **New** |
| *Not covered* | — | **Mod 107: GPU Computing** | CUDA, multi-GPU, optimization | **New** |
| *Not covered* | — | **Mod 109: Infrastructure as Code** | Advanced Terraform, modules | **New** |
| *Not covered* | — | **Mod 110: LLM Infrastructure** | vLLM, RAG, serving optimization | **New** |

### Progression Types Explained

- **Deepening**: Engineer module significantly expands Junior topics
- **Applied**: Skill used in Engineer track but not dedicated module
- **Continuous**: Topic integrated across multiple Engineer modules
- **New**: Entirely new topic not covered in Junior track

---

## Skill Progression Matrix

### Technical Skills

| Skill Area | Junior Level | Engineer Level |
|------------|--------------|----------------|
| **Python** | Basic syntax, OOP, testing | Async, decorators, metaprogramming, performance |
| **Containers** | Dockerfile, docker-compose | Multi-stage builds, optimization, security scanning |
| **Kubernetes** | Deploy apps, basic troubleshooting | Production clusters, operators, auto-scaling |
| **Cloud** | Use AWS services via console | Multi-cloud, IaC, cost optimization, FinOps |
| **Monitoring** | Set up dashboards, basic queries | SLIs/SLOs, distributed tracing, advanced PromQL |
| **ML Systems** | Run inference, understand models | Train at scale, distributed training, optimization |
| **Networking** | Basic concepts, security groups | VPCs, service mesh, load balancing strategies |
| **CI/CD** | Basic GitHub Actions | MLOps pipelines, model deployment automation |
| **Databases** | CRUD operations, basic queries | Replication, sharding, performance tuning |
| **IaC** | Basic Terraform | Modules, remote state, multi-environment |

### Soft Skills

| Skill Area | Junior Level | Engineer Level |
|------------|--------------|----------------|
| **Problem Solving** | Debug with guidance | Independent troubleshooting |
| **System Design** | Understand existing systems | Design simple systems |
| **Communication** | Document work clearly | Present technical decisions |
| **Collaboration** | Work on assigned tasks | Lead small initiatives |
| **Project Management** | Complete tasks on time | Manage small projects |

---

## Module-by-Module Progression

### Foundation Skills (Common Prerequisites)

Before starting either track, ensure you have:
- Basic programming knowledge (any language)
- Command-line comfort
- Basic understanding of how computers work
- High school level math

### Junior → Engineer Detailed Progression

#### Path 1: ML Infrastructure Focus

```
Junior Mod 001-004 (Python + ML Basics)
         ↓
Engineer Mod 101 (Foundations)
         ↓
Junior Mod 005-006 (Containers + K8s)
         ↓
Engineer Mod 103-104 (Advanced Containers + K8s)
         ↓
Engineer Mod 107 (GPU Computing)
         ↓
Engineer Mod 110 (LLM Infrastructure)
```

**Timeline**: 6-9 months
**Best for**: ML model deployment focus

#### Path 2: Platform Engineering Focus

```
Junior Mod 001-003 (Python + Linux + Git)
         ↓
Junior Mod 010 (Cloud Platforms)
         ↓
Engineer Mod 102 (Cloud Computing)
         ↓
Engineer Mod 109 (Infrastructure as Code)
         ↓
Junior Mod 005-006 (Containers + K8s)
         ↓
Engineer Mod 103-104 (Advanced Containers + K8s)
```

**Timeline**: 6-9 months
**Best for**: Infrastructure/platform engineering focus

#### Path 3: MLOps Focus

```
Junior Mod 001-004 (Foundations + ML)
         ↓
Engineer Mod 101 (Foundations)
         ↓
Junior Mod 009-010 (Monitoring + Cloud)
         ↓
Engineer Mod 105 (Data Pipelines)
         ↓
Engineer Mod 106 (MLOps)
         ↓
Engineer Mod 108 (Monitoring & Observability)
```

**Timeline**: 6-9 months
**Best for**: MLOps/DevOps for ML focus

#### Path 4: Complete Full-Stack

```
Junior Modules 001-010 (All modules sequentially)
         ↓
Engineer Modules 101-110 (All modules sequentially)
```

**Timeline**: 12-18 months
**Best for**: Comprehensive mastery, career change

---

## Detailed Topic Cross-Reference

### Python Development

| Junior (Mod 001) | Engineer (Mod 101) |
|-----------------|-------------------|
| Variables, data types | Type hints, generics |
| Functions, basic OOP | Decorators, metaclasses |
| File I/O | Async I/O, context managers |
| Basic testing | Pytest fixtures, mocking, property testing |
| Loops, conditionals | Generators, itertools, functools |
| pip, virtualenv | Poetry, uv, dependency management |

**Gap to Bridge**: Async programming, advanced OOP patterns, performance optimization

### Containerization

| Junior (Mod 005) | Engineer (Mod 103) |
|-----------------|-------------------|
| Dockerfile basics | Multi-stage builds |
| COPY, RUN, CMD | ONBUILD, HEALTHCHECK, build optimization |
| docker run, ps, logs | Layer caching strategies |
| Basic networking | Advanced networking modes |
| docker-compose | docker-compose for production |

**Gap to Bridge**: Image optimization, security scanning, production best practices

### Kubernetes

| Junior (Mod 006) | Engineer (Mod 104) |
|-----------------|-------------------|
| Pods, Deployments | StatefulSets, DaemonSets |
| Services (ClusterIP, LoadBalancer) | Ingress controllers, service mesh |
| Basic kubectl | Advanced kubectl, jsonpath |
| ConfigMaps, Secrets | External secrets, sealed secrets |
| — | Operators, CRDs |
| — | Horizontal Pod Autoscaler |
| — | Network policies |
| — | Resource quotas, LimitRanges |

**Gap to Bridge**: Production operations, advanced networking, custom resources

### Cloud Platforms

| Junior (Mod 010) | Engineer (Mod 102) |
|-----------------|-------------------|
| EC2 instances | Auto Scaling Groups |
| S3 basics | S3 lifecycle, versioning, replication |
| RDS setup | Multi-AZ, read replicas, performance |
| VPC basics | VPC peering, Transit Gateway |
| IAM users/policies | Advanced IAM, OIDC, IRSA |
| — | Multi-cloud strategies |
| — | Cost optimization, Reserved Instances |
| — | Managed ML services (SageMaker, Vertex AI) |

**Gap to Bridge**: Advanced networking, cost optimization, multi-cloud architecture

### Monitoring & Observability

| Junior (Mod 009) | Engineer (Mod 108) |
|-----------------|-------------------|
| Prometheus basics | Advanced PromQL, recording rules |
| Grafana dashboards | Dashboard as code, advanced visualizations |
| Log viewing | Structured logging, log aggregation |
| Basic alerts | Alert optimization, alert fatigue prevention |
| — | Distributed tracing (Jaeger, Tempo) |
| — | SLIs, SLOs, SLAs, error budgets |
| — | OpenTelemetry instrumentation |

**Gap to Bridge**: Distributed tracing, SRE practices, advanced alerting

---

## Learning Path Recommendations

### For Junior Track Graduates

After completing the Junior track, you have options:

#### Option A: Direct Progression (Recommended)
- **Start**: Engineer Mod 101 (Foundations)
- **Why**: Smooth progression, builds on Junior knowledge
- **Timeline**: 4-6 months to complete Engineer track

#### Option B: Gain Work Experience First
- **Work**: 6-12 months as Junior AI Infrastructure Engineer
- **Then**: Engineer track
- **Why**: Real-world context enhances learning
- **Timeline**: 12-18 months total (work + study)

#### Option C: Specialize Early
- **Pick**: One Engineer specialization (MLOps, GPU, LLM)
- **Complete**: Relevant Engineer modules only
- **Timeline**: 2-3 months focused study
- **Trade-off**: Deep but narrow expertise

### For Experienced Engineers

If you already have software engineering experience:

#### Skip Junior If:
- ✅ Comfortable with Python (2+ years)
- ✅ Know Docker and Kubernetes basics
- ✅ Used cloud platforms professionally
- ✅ Understand CI/CD and Git workflows

**Start**: Engineer Mod 101

#### Take Junior If:
- ❌ New to Python or ML concepts
- ❌ Limited container/K8s exposure
- ❌ Haven't worked with cloud infrastructure
- ❌ Want comprehensive foundation

---

## Time Estimates by Learning Style

### Full-Time Study (40 hrs/week)

| Track | Duration | Schedule |
|-------|----------|----------|
| Junior only | 2-3 months | Intensive bootcamp-style |
| Engineer only | 3-4 months | With Junior background |
| Both tracks | 5-7 months | Comprehensive full-stack |

### Part-Time Study (10-15 hrs/week)

| Track | Duration | Schedule |
|-------|----------|----------|
| Junior only | 6-9 months | Evening/weekend study |
| Engineer only | 8-10 months | With Junior background |
| Both tracks | 12-18 months | Gradual progression |

### Self-Paced (Variable)

| Track | Range | Notes |
|-------|-------|-------|
| Junior only | 3-12 months | Depends on prior experience |
| Engineer only | 4-12 months | Depends on Junior completion speed |
| Both tracks | 8-24 months | Most flexible, fits around work |

---

## Prerequisites Checklist

### For Junior Track

**Hard Prerequisites**:
- [ ] Basic computer literacy
- [ ] Comfortable with installing software
- [ ] Can use command line for basic tasks
- [ ] High school level math

**Helpful but Optional**:
- [ ] Any programming experience
- [ ] Linux/Unix familiarity
- [ ] Understanding of networking basics

### For Engineer Track

**Hard Prerequisites**:
- [ ] **Completed Junior track** OR equivalent experience
- [ ] Python proficiency (classes, decorators, async)
- [ ] Docker and Kubernetes fundamentals
- [ ] Cloud platform basics (AWS, GCP, or Azure)
- [ ] Git and CI/CD workflows

**Helpful but Optional**:
- [ ] Machine learning theory background
- [ ] Production system experience
- [ ] Computer science degree (or equivalent)

---

## Skill Validation

### After Junior Track, You Should Be Able To:

**Python**
- [ ] Write well-structured Python programs with OOP
- [ ] Create and manage virtual environments
- [ ] Write and run pytest tests
- [ ] Debug Python applications

**Infrastructure**
- [ ] Write Dockerfiles and use docker-compose
- [ ] Deploy applications to Kubernetes
- [ ] Use AWS services (EC2, S3, RDS, IAM)
- [ ] Set up basic monitoring with Prometheus/Grafana

**ML Systems**
- [ ] Run inference with PyTorch/TensorFlow models
- [ ] Understand model formats (ONNX, SavedModel)
- [ ] Deploy ML models as APIs
- [ ] Monitor model performance

### After Engineer Track, You Should Be Able To:

**Advanced Infrastructure**
- [ ] Design and deploy production Kubernetes clusters
- [ ] Implement multi-cloud infrastructure with Terraform
- [ ] Set up distributed training for ML models
- [ ] Optimize infrastructure costs

**MLOps**
- [ ] Build CI/CD pipelines for ML models
- [ ] Implement experiment tracking and model registries
- [ ] Create data pipelines with Airflow
- [ ] Monitor model drift and data quality

**Specialized Skills**
- [ ] Configure and optimize GPU workloads
- [ ] Deploy and optimize LLM inference (vLLM, TGI)
- [ ] Implement advanced monitoring (tracing, SLOs)
- [ ] Design scalable ML infrastructure

---

## Common Questions

### Q: Can I skip the Junior track?

**A**: Only if you have equivalent experience:
- 1-2 years Python development
- Used Docker and Kubernetes professionally
- Worked with cloud platforms (AWS/GCP/Azure)
- Deployed production services

**Test yourself**: Try Engineer Mod 101 exercises. If you struggle, go back to Junior track.

### Q: Which track should I start with?

**A**: Start with Junior if you:
- Are new to software engineering
- Want comprehensive foundations
- Prefer structured learning

**A**: Start with Engineer if you:
- Completed Junior track
- Have 1-2 years software engineering experience
- Want advanced/specialized topics

### Q: Can I take modules out of order?

**A**: Within a track, **follow the sequence**. Each module builds on previous ones.

**Between tracks**, you can mix:
- Complete Junior Mod 001-004, then Engineer Mod 101
- Complete Junior fully, then Engineer selectively

### Q: How long until I'm job-ready?

**A**: Depends on starting point:
- **Complete beginner**: Junior track (3-6 months) + internship/entry role
- **Junior track graduate**: 0-6 months work experience
- **Engineer track graduate**: Ready for mid-level roles

---

## Next Steps

### After Reading This Guide

1. **Assess your current level** using the skill matrices
2. **Choose your starting point** (Junior vs Engineer)
3. **Select a learning path** (full-stack vs specialized)
4. **Set a timeline** based on your availability
5. **Start learning!**

### Resources

- [Junior Engineer README](../learning/ai-infra-junior-engineer-learning/README.md)
- [Engineer README](../learning/ai-infra-engineer-learning/README.md)
- [Version Specifications](./VERSIONS.md)
- [Career Progression Guide](./CAREER_PROGRESSION.md) ← Coming soon

---

**Maintained by**: AI Infrastructure Curriculum Team
**Last Updated**: January 2025
**Questions?**: Open an issue in the relevant repository
