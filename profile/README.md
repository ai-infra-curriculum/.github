# AI Infrastructure Engineering Curriculum

---

## ⚠️ AI-Generated Content Disclaimer

> **Important Notice**: The content in this organization's repositories has been generated with AI assistance and is currently undergoing human review and verification. While we strive for accuracy, **the content may contain errors, inaccuracies, or outdated information**.
>
> **Status**: 🔄 Human review and runtime validation in progress
>
> Please use this content as a learning resource with appropriate caution. We recommend:
> - Cross-referencing with official documentation
> - Testing all code examples in a safe environment
> - Reporting any errors or inaccuracies via GitHub issues or discussions
>
> We appreciate your understanding as we continue improving content quality and accuracy.

---

> A comprehensive, hands-on learning path for AI Infrastructure Engineers at all levels - from entry-level to principal roles.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/orgs/ai-infra-curriculum/discussions)
[![Repositories: 27](https://img.shields.io/badge/repositories-27-blue.svg)](https://github.com/orgs/ai-infra-curriculum/repositories)

## 🎯 Overview

This curriculum provides production-focused training for AI Infrastructure Engineers, covering everything from foundational Python and Kubernetes to distributed training, LLM infrastructure, MLOps, platform engineering, security, and enterprise architecture.

The organization is now in a different phase than it was in late 2025: the repo surface is largely in place, and the main work is now **depth, validation, and human review** rather than simply standing up missing repositories.

**Total Content:**
- 🏢 **27 Organization Repositories** (24 curriculum + 3 support)
- 📚 **12 Learning Tracks** (Junior → Principal levels)
- ✅ **12 Solutions Repositories**
- 🎓 **525+ Hands-On Exercises**
- 🚀 **45+ Real-World Projects**
- ⏱️ **6,000+ Hours** of learning material

## ✨ What's New

**Recent Org Updates (May 2026):**
- 🛡️ **Security Track Completed (May 26, 2026)** - All 12 security-learning modules now published (foundations → zero-trust → cryptography → network → secrets → adversarial ML → compliance → runtime → policy → supply chain → SecOps → capstone), ~335 hours, ~105K words of curriculum
- 📚 **SOLUTION.md Sweep** - 15 new design-rationale docs across all 12 solutions repos (project-level `SOLUTION.md` files plus track-level `SOLUTION_OVERVIEW.md` for module-only repos)
- 🔄 **Full Curriculum Refresh (May 23, 2026)** - 21 repos updated, 40+ commits, 350+ new exercises, and 50+ new modules
- 🗺️ **[Curriculum Cross-Reference](https://github.com/ai-infra-curriculum/.github/blob/main/CURRICULUM_CROSS_REFERENCE.md)** - role and skill progression mapping across tracks
- 📈 **[Career Progression Guide](https://github.com/ai-infra-curriculum/.github/blob/main/CAREER_PROGRESSION.md)** - career ladder from junior through principal architect
- 📝 **Engineer Answer Keys** - 248 quiz questions organized across the 10 engineer modules
- 🧱 **Advanced and Leadership Tracks Published** - specialization, senior, architect, and leadership tiers now have live curriculum structure

---

## 🗺️ Learning Paths

```text
Entry Level (0-2 years)
    ↓
Junior Engineer → Engineer
    ↓
Intermediate (2-4 years)
    ↓
┌─────────────────────┬──────────────────────┬─────────────────────────┐
│                     │                      │                         │
MLOps Engineer        ML Platform Engineer   Performance Engineer      Security Engineer
│                     │                      │                         │
└─────────────────────┴──────────────────────┴─────────────────────────┘
    ↓
Advanced (4-6 years)
    ↓
Senior Engineer ────────────→ Architect
    ↓                             ↓
Leadership (6-8 years)      Advanced Arch (8-10 years)
    ↓                             ↓
Team Lead ───────────────→ Senior Architect
    ↓                             ↓
Principal Level (8-15+ years)
    ↓                             ↓
Principal Engineer ──────→ Principal Architect
```

---

## 📚 All Learning Tracks

### 🟢 Entry Level (0-2 years)

<table>
<tr>
<td width="50%">

#### [Junior Engineer](https://github.com/ai-infra-curriculum/ai-infra-junior-engineer-learning)
**Time:** 440 hours
**Status:** ✅ Complete

**What You'll Learn:**
- Python & ML basics
- Linux & Docker fundamentals
- Kubernetes introduction
- Cloud platforms (AWS/GCP/Azure)
- Basic monitoring & APIs

**Projects:** 5 capstone projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-junior-engineer-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-junior-engineer-solutions)**

</td>
<td width="50%">

#### [Engineer](https://github.com/ai-infra-curriculum/ai-infra-engineer-learning)
**Time:** 440 hours
**Status:** ✅ Complete

**What You'll Learn:**
- Production ML systems
- Distributed training
- GPU computing & optimization
- Advanced Kubernetes
- MLOps pipelines
- LLM infrastructure (vLLM, RAG)
- IaC (Terraform, Pulumi)

**Projects:** 3 production systems

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-engineer-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-engineer-solutions)**

</td>
</tr>
</table>

---

### 🔵 Intermediate Level (2-4 years)

<table>
<tr>
<td width="50%">

#### [MLOps Engineer](https://github.com/ai-infra-curriculum/ai-infra-mlops-learning)
**Time:** 580 hours
**Status:** 🟡 Published (10 modules, 5 projects; review ongoing)

**What You'll Learn:**
- CI/CD for ML models
- Model registry & versioning
- Feature stores
- Experiment tracking
- Model monitoring & drift detection
- A/B testing infrastructure

**Projects:** 5 hands-on projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-mlops-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-mlops-solutions)**

</td>
<td width="50%">

#### [ML Platform Engineer](https://github.com/ai-infra-curriculum/ai-infra-ml-platform-learning)
**Time:** 600-700 hours
**Status:** 🟡 Published (9 modules live; module-first today)

**What You'll Learn:**
- Platform architecture design
- Multi-tenancy & isolation
- Model serving at scale
- Platform APIs & SDKs
- Resource management & quotas
- Developer experience

**Projects:** Modules are live; project layer still needs more build-out

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-ml-platform-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-ml-platform-solutions)**

</td>
</tr>
<tr>
<td width="50%">

#### [Performance Engineer](https://github.com/ai-infra-curriculum/ai-infra-performance-learning)
**Time:** 200-250 hours
**Status:** 🟡 Published (8 modules + 3 projects)

**What You'll Learn:**
- GPU utilization optimization
- Inference latency reduction
- Training efficiency
- Cost optimization
- Profiling (Nsight, PyTorch Profiler)

**Projects:** 3 optimization-focused projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-performance-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-performance-solutions)**

</td>
<td width="50%">

#### [Security Engineer](https://github.com/ai-infra-curriculum/ai-infra-security-learning)
**Time:** 335 hours (12 modules)
**Status:** ✅ Complete (12 modules + 5 projects + capstone)

**What You'll Learn:**
- ML infrastructure security foundations + OWASP ML Top 10
- Zero-trust architecture (SPIFFE, mTLS, microsegmentation)
- Cryptography (KMS, Cosign, hash chains)
- Network security + secrets management
- Adversarial ML (FGSM/PGD/DP-SGD/LLM prompt injection)
- Compliance (GDPR, HIPAA, SOC 2, EU AI Act)
- Runtime security (Falco, eBPF) + policy as code (OPA, Kyverno)
- Supply chain security (SLSA, SBOM, attestations)
- Security operations (SIEM, MITRE ATLAS, IR procedures)
- Capstone synthesis (NorthBridge Health scenario)

**Projects:** 5 implementations + capstone portfolio

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-security-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-security-solutions)**

</td>
</tr>
</table>

---

### 🟣 Advanced Level (4-6 years)

<table>
<tr>
<td width="50%">

#### [Senior Engineer](https://github.com/ai-infra-curriculum/ai-infra-senior-engineer-learning)
**Time:** 400-500 hours
**Status:** 🟡 Published (10 modules + 4 projects)

**What You'll Learn:**
- Advanced Kubernetes (operators, CRDs)
- Distributed training at scale
- GPU & CUDA optimization
- Multi-cloud architecture
- Advanced MLOps
- SRE & observability
- Security & compliance

**Projects:** 4 capstone projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-senior-engineer-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-senior-engineer-solutions)**

</td>
<td width="50%">

#### [Architect](https://github.com/ai-infra-curriculum/ai-infra-architect-learning)
**Time:** 600 hours
**Status:** 🟡 Published (10 modules + 5 projects)

**What You'll Learn:**
- Enterprise architecture for ML
- Multi-cloud & hybrid strategies
- Security & compliance architecture
- Cost optimization & FinOps
- HA & disaster recovery
- LLM & RAG platform design

**Projects:** 5 architecture projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-architect-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-architect-solutions)**

</td>
</tr>
</table>

---

### 🔴 Leadership Level (6-10 years)

<table>
<tr>
<td width="50%">

#### [Team Lead](https://github.com/ai-infra-curriculum/ai-infra-team-lead-learning)
**Time:** 500 hours
**Status:** 🟡 Strategic track live (5 modules + 5 projects)

**What You'll Learn:**
- Technical strategy & roadmaps
- Team building & hiring
- Architecture decision records
- Incident management
- Performance management
- Stakeholder communication

**Projects:** 5 leadership projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-team-lead-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-team-lead-solutions)**

</td>
<td width="50%">

#### [Senior Architect](https://github.com/ai-infra-curriculum/ai-infra-senior-architect-learning)
**Time:** 420 hours
**Status:** 🟡 Strategic modules live (10 modules; project layer still shallow)

**What You'll Learn:**
- Cross-org architecture alignment
- Enterprise-wide standards
- Multi-year technology roadmaps
- Executive communication
- Large-scale transformations

**Projects:** 1 live project scaffold today; more depth still needed

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-senior-architect-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-senior-architect-solutions)**

</td>
</tr>
</table>

---

### ⭐ Principal Level (8-15+ years)

<table>
<tr>
<td width="50%">

#### [Principal Engineer](https://github.com/ai-infra-curriculum/ai-infra-principal-engineer-learning)
**Time:** 680 hours
**Status:** 🟡 Strategic track live (5 modules + 5 projects)

**What You'll Learn:**
- Technical excellence & deep expertise
- Solving unprecedented challenges
- Distributed systems at extreme scale
- Performance optimization
- Novel infrastructure solutions
- Technical mentorship

**Projects:** 5 high-impact projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-principal-engineer-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-principal-engineer-solutions)**

</td>
<td width="50%">

#### [Principal Architect](https://github.com/ai-infra-curriculum/ai-infra-principal-architect-learning)
**Time:** 520 hours
**Status:** 🟡 Strategic track live (5 modules + 5 projects)

**What You'll Learn:**
- Company-wide technical strategy
- Multi-year roadmaps
- Executive-level communication
- Technology evaluation & selection
- Architecture governance
- Organizational transformation

**Projects:** 5 strategic projects

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-principal-architect-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-principal-architect-solutions)**

</td>
</tr>
</table>

---

## 📈 Repository Status

| Track | Status | Current Coverage | Notes |
|-------|--------|------------------|-------|
| Junior Engineer | ✅ Complete | 10 modules, 5 projects | Best starting point for new learners |
| Engineer | ✅ Complete | 10 modules, 3 projects, 119 solved exercises | Strongest hands-on core track |
| MLOps | 🟡 Published | 10 modules, 5 projects, 50 exercises | Validation and review ongoing |
| ML Platform | 🟡 Published | 9 modules, 45 exercises | Module-first today; projects need more build-out |
| Performance | 🟡 Published | 8 modules, 3 projects, 40 exercises | Good depth in core modules |
| Security | ✅ Complete | 12 modules, 5 projects, 60+ exercises, capstone | Full track with NorthBridge Health capstone synthesis |
| Senior Engineer | 🟡 Published | 10 modules, 4 projects, 50 exercises | Needs continued depth passes |
| Architect | 🟡 Published | 10 modules, 5 projects, 50 exercises | Structurally strong, still maturing |
| Senior Architect | 🟡 Strategic Live | 10 modules, 50 exercises | Project layer is still shallow |
| Team Lead | 🟡 Strategic Live | 5 modules, 5 projects, 25 exercises | Leadership scaffolds are live |
| Principal Engineer | 🟡 Strategic Live | 5 modules, 5 projects, 25 exercises | Strategic scaffolds are live |
| Principal Architect | 🟡 Strategic Live | 5 modules, 5 projects, 25 exercises | Strategic scaffolds are live |

---

## 🚩 Missing / Incomplete Content

These are the clearest gaps still visible at the org level and should be treated as active follow-up work:

- **ML Platform Engineer**: `9` modules are live, but the current repo snapshot still needs stronger project population.
- **Senior Architect**: `10` strategic modules are live, but only `1` project scaffold is currently checked in.
- **Leadership and principal tracks**: Team Lead, Principal Engineer, and Principal Architect are live structurally, but still need deeper lecture content and stronger artifact depth.
- **Senior Engineer learning**: 10 modules + 4 projects + 36 exercises live, but module-level `quiz.md` files are still missing in some modules.
- **Engineer learning**: 10 modules + 3 projects + 181 exercises + 113 solved exercises live; some modules still need filled-out `lecture.md` / `resources.md`.
- **Runtime validation**: Several Docker/Kubernetes/cloud-heavy repos still need fuller execution validation beyond static checks and structure checks.
- **Human review**: AI-assisted material across the org still needs ongoing factual review, correction, and link cleanup. The Security track in particular went through a deliberate ML-domain pass during the May 2026 build.

---

## 🚀 Quick Start

### 1. Choose Your Track
Select based on your current experience level and career direction.

### 2. Clone the Repository
```bash
# Example: Junior Engineer track
git clone https://github.com/ai-infra-curriculum/ai-infra-junior-engineer-learning.git
cd ai-infra-junior-engineer-learning
```

### 3. Start Learning
```bash
# Read the curriculum
cat README.md

# Start with Module 001
cd lessons/mod-001-python-fundamentals
cat README.md
```

### 4. Complete Exercises
Work through the hands-on exercises in each module.

### 5. Check Solutions
Use the companion solutions repository for comparison and reference.

---

## 🛠️ Technologies Covered

**Languages:** Python, Bash, HCL (Terraform), YAML
**ML Frameworks:** PyTorch, TensorFlow, Scikit-learn
**Orchestration:** Kubernetes, Helm, ArgoCD, FluxCD
**Cloud:** AWS, GCP, Azure
**Containers:** Docker, containerd
**MLOps:** MLflow, Kubeflow, DVC, Feast
**Monitoring:** Prometheus, Grafana, Loki, Jaeger
**IaC:** Terraform, Pulumi
**CI/CD:** GitHub Actions, GitLab CI
**LLMs:** vLLM, Llama, Mistral, RAG systems
**GPU:** CUDA, NCCL, TensorRT

---

## 🎓 Key Features

### Production-Focused
- Working code in core engineering, security, and solutions repos
- Metrics-driven project and exercise design
- Solution repos plus strategic templates where code is not the main deliverable
- Best practices and anti-patterns

### Comprehensive
- 525+ hands-on exercises
- 45+ real-world projects
- Full learning/solutions repo pairs
- Cross-references, quizzes, and answer keys

### Progressive
- Start with fundamentals
- Build to production systems
- Specialize across MLOps, platform, performance, and security
- Advance into architecture, leadership, and principal-level strategy

### Supported
- Org-wide structural refresh completed in May 2026
- Human review and validation are still ongoing
- Cross-reference and answer-key maintenance are active
- Feedback is welcome through Issues and Discussions

---

## 🤝 Contributing

We welcome contributions across the organization.

**Ways to contribute:**
- Fix broken links, stale references, or inaccurate explanations
- Add depth to thin modules, projects, or strategic artifacts
- Improve validation for runnable exercises and projects
- Report issues or suggest improvements via [GitHub Discussions](https://github.com/orgs/ai-infra-curriculum/discussions)
- Follow the `CONTRIBUTING.md` in the specific repository you want to improve

---

## 📜 License

Most curriculum repositories are MIT-licensed. See the target repository's `LICENSE` file for the authoritative terms.

---

## 📞 Support

- **Issues:** Use the relevant repository's GitHub Issues
- **Discussions:** Use [organization discussions](https://github.com/orgs/ai-infra-curriculum/discussions)
- **Docs:** See [Career Progression](https://github.com/ai-infra-curriculum/.github/blob/main/CAREER_PROGRESSION.md) and [Curriculum Cross-Reference](https://github.com/ai-infra-curriculum/.github/blob/main/CURRICULUM_CROSS_REFERENCE.md)

---

## 🗺️ Roadmap

**Current Status (May 2026):**
- ✅ All `27` org repositories are live
- ✅ The May 23, 2026 chain pass refreshed `21` repos
- ✅ Junior, Engineer, and **Security** tracks are now fully-developed entry-to-specialization paths
- ✅ All 12 solutions repos now have `SOLUTION.md` (per-project) or `SOLUTION_OVERVIEW.md` (per-track) design-rationale docs
- 🟡 Specialization and senior tracks are published and usable
- 🟡 Leadership and principal tracks are structurally live but still need depth
- 🟡 ML Platform Engineer needs project-layer build-out
- 🟡 Senior Architect needs deeper project artifacts

**Current Focus (2026):**
- Human review and factual verification of AI-assisted content
- Runtime validation for code-heavy projects and labs
- Deeper lecture and artifact development for leadership-tier tracks
- ML Platform and Senior Architect project layer
- Cross-reference, navigation, and link cleanup across the org

---

## 🌟 Featured Highlights

### Real-World Impact
- Reduce infrastructure costs by 30-50%
- Improve GPU utilization from low baseline usage to production efficiency
- Cut deployment time from days to hours
- Scale from a first model service to multi-team platform thinking

### Industry-Relevant
- Covers real production concerns across serving, MLOps, platform, security, and architecture
- Includes working code, solution repos, and strategic planning artifacts
- Refreshed through the May 2026 org-wide update pass
- Aligned with role progression from junior to principal

### Career Advancement
- Clear progression path from Junior to Principal
- Multiple specialization tracks
- Leadership development included
- Portfolio-ready projects and artifacts

---

**Start your AI Infrastructure Engineering journey today!** 🚀

[Choose Your Track](#-all-learning-tracks) | [Quick Start](#-quick-start) | [Contributing](#-contributing)

---

**Maintained by:** AI Infrastructure Curriculum Project
**Last Updated:** May 26, 2026
**Total Repositories:** 27 org-wide (24 curriculum + 3 support)
