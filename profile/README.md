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
- 🧹 **Placeholder Cleanup Pass (May 26, 2026)** - 4 stale `PLACEHOLDER - Content Coming Soon` README banners replaced with accurate content (principal-architect-solutions, principal-engineer-solutions, team-lead-solutions, security-solutions — all repos have real content but the original scaffolding banners were never removed). Stripped "Coming Soon" Slack/Twitter/Newsletter/Website links across engineer + mlops + ml-platform learning repos. Removed 5 stale "lecture materials in development" notices from junior-engineer modules whose content has been live for weeks. Completed the mod-103 GPU-docker lecture exercise. 11 of 25 repos now show 0 placeholder markers (up from 4).
- 🎯 **Capstone Projects Completed (May 26, 2026)** - 11 new project specs added: 5 ML Platform capstones (platform-core, feature-store, workflow-orchestration, model-registry, developer-portal — 355 hours total) + 5 Senior Architect strategic capstones (project-402 through project-406 — 285 hours total). Both tracks now structurally complete at the project layer.
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

**Coverage:** 67 hands-on exercises across 10 modules, 5 capstone projects, 53 reference solutions

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

**Coverage:** 181 hands-on exercises across 10 modules, 3 production-system projects, 122 reference solutions

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

**Coverage:** 50 hands-on exercises across 10 modules, 5 capstone projects, 55 reference solutions

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

**Coverage:** 45 hands-on exercises across 9 modules, 45 reference solutions; project layer still needs more build-out

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

**Coverage:** 41 hands-on exercises across 8 modules, 3 optimization-focused projects, 40 reference solutions (with autograders)

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

**Coverage:** 61 hands-on exercises across 12 modules, 5 project implementations + capstone synthesis (NorthBridge Health), 5 project-level reference solutions

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

**Coverage:** 36 hands-on exercises across 10 modules, 4 capstone projects, 54 reference solutions

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

**Coverage:** 50 hands-on exercises across 10 modules, 5 architecture projects, 55 reference solutions

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

**Coverage:** 25 hands-on exercises across 5 modules, 5 leadership projects, 25 reference solutions

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

**Coverage:** 45 hands-on exercises across 10 modules, 51 reference solutions; 1 live project scaffold today (more depth still needed)

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

**Coverage:** 25 hands-on exercises across 5 modules, 5 high-impact projects, 25 reference solutions

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

**Coverage:** 25 hands-on exercises across 5 modules, 5 strategic projects, 25 reference solutions

**[📘 Learning](https://github.com/ai-infra-curriculum/ai-infra-principal-architect-learning) | [✅ Solutions](https://github.com/ai-infra-curriculum/ai-infra-principal-architect-solutions)**

</td>
</tr>
</table>

---

## 📈 Repository Status

| Track | Status | Current Coverage | Notes |
|-------|--------|------------------|-------|
| Junior Engineer | ✅ Complete | 10 modules, 5 projects, 67 exercises, 53 reference solutions | Best starting point for new learners |
| Engineer | ✅ Complete | 10 modules, 3 projects, 181 exercises, 122 reference solutions | Strongest hands-on core track |
| MLOps | 🟡 Published | 10 modules, 5 projects, 50 exercises, 55 reference solutions | Validation and review ongoing |
| ML Platform | 🟡 Published | 9 modules, 45 exercises, 45 reference solutions | Module-first today; projects need more build-out |
| Performance | 🟡 Published | 8 modules, 3 projects, 41 exercises, 40 reference solutions | Good depth in core modules |
| Security | ✅ Complete | 12 modules, 5 projects + capstone, 61 exercises | Full track with NorthBridge Health capstone synthesis |
| Senior Engineer | 🟡 Published | 10 modules, 4 projects, 36 exercises, 54 reference solutions | Needs continued depth passes |
| Architect | 🟡 Published | 10 modules, 5 projects, 50 exercises, 55 reference solutions | Structurally strong, still maturing |
| Senior Architect | 🟡 Strategic Live | 10 modules, 1 project, 45 exercises, 51 reference solutions | Project layer is still shallow |
| Team Lead | 🟡 Strategic Live | 5 modules, 5 projects, 25 exercises, 25 reference solutions | Leadership scaffolds are live |
| Principal Engineer | 🟡 Strategic Live | 5 modules, 5 projects, 25 exercises, 25 reference solutions | Strategic scaffolds are live |
| Principal Architect | 🟡 Strategic Live | 5 modules, 5 projects, 25 exercises, 25 reference solutions | Strategic scaffolds are live |

---

## 🚩 Outstanding Work

The audits in `_meta/QUALITY_REPORT.md` and `_meta/EXERCISE_SOLUTION_PARITY.md` (both regenerated 2026-05-26) surface the following concrete gaps. Every module *exists* in the planned modules' directory; every learning exercise has a corresponding solution where one is expected. The remaining work is filling in specific files and project specs.

### Missing module pieces (per-file)

✅ **All resolved in the May 26, 2026 pass.** The audit-flagged missing files have been added:

- **Junior Engineer Learning**: 7 new `resources.md` files added (mod-001, 003, 004, 005, 007, 008, 010).
- **Engineer Learning**: `resources.md` added to mod-101-foundations.
- **Senior Engineer Learning**: 10 `quiz.md` files relocated from `exercises/quiz.md` to module root via `git mv` (history preserved).
- **Senior Architect Learning**: mod-401-enterprise-ai-strategy's empty `lecture-notes/` now contains `01-overview.md` matching the peer-module pattern.

Track scores improved correspondingly: Junior 59 → 76, Senior Engineer 51 → 75, Senior Architect 66 → 77, Engineer 55 → 79 (the audit script was updated on May 26, 2026 to recognize the engineer-track numbered-lecture convention — no more false positives).

### Missing projects (planned but not built)

✅ **All resolved in the May 26, 2026 pass.**

**ML Platform Engineer** — all 5 planned capstone projects now live with the full 4-file scaffold (README + architecture + requirements + STEP_BY_STEP):
- ✅ `project-01-platform-core` (80h) — Self-Service ML Platform Core
- ✅ `project-02-feature-store` (70h) — Enterprise Feature Store
- ✅ `project-03-workflow-orchestration` (75h) — ML Workflow Orchestration Engine
- ✅ `project-04-model-registry` (70h) — Model Management System
- ✅ `project-05-developer-portal` (60h) — Developer Portal & SDK

**Senior Architect** — all 6 planned capstones now live (single-README strategic-deliverable format):
- ✅ `project-401-ai-transformation-strategy` (60h)
- ✅ `project-402-global-ai-platform-architecture` (70h)
- ✅ `project-403-responsible-ai-framework` (60h)
- ✅ `project-404-innovation-program-design` (50h)
- ✅ `project-405-industry-thought-leadership` (50h)
- ✅ `project-406-enterprise-governance-model` (55h)

### Curriculum-design gaps (not "missing files" but areas needing depth)

- **Leadership and principal tracks** (Team Lead, Principal Engineer, Principal Architect): Each has the full 5-module / 5-project / 25-exercise scaffold checked in, but lecture content depth is shallower than the Engineer / MLOps / Security tracks. The strategic content is appropriate to the tier; the per-module lecture depth is the next iteration.
- **ML Platform Engineer**: 9 deep modules + 45 hands-on exercises + 5 capstone projects (added May 26, 2026). Track structurally complete.
- **Senior Engineer**: Lab structure is now 5 labs per module after the May 2026 parity pass; the labs themselves are senior-scale framings pointing back to the engineer-track for implementation depth — fuller standalone lab content is the natural next iteration.
- **Engineer Solutions implementation depth**: `ai-infra-engineer-solutions` modules `mod-102` through `mod-110` contain ~114 Python files (out of 348 total) that are scaffolded but unimplemented (class/function stubs with `# TODO: Implement`). The lecture content, exercise specs, and SOLUTION.md write-ups are in place; what's missing is the runnable reference code for each exercise. This is a curriculum-development task at multi-session scale and is the largest remaining content gap in the org.

### By-design "gaps" — not actually missing

- **Security Engineer**: The parity audit lists 61 "missing solutions" for security-learning. These are **design-based exercises** (write a threat model, produce a DPIA, conduct a tabletop). They are answered by *rubrics* and the 5 project-level `SOLUTION.md` files in `ai-infra-security-solutions`, not by per-exercise reference code. The discrepancy is structural, not a content gap.

### Cross-cutting work

- **Runtime validation**: Several Docker / Kubernetes / cloud-heavy repos still need fuller execution validation beyond static structure checks.
- **Human review**: AI-assisted material across the org still needs ongoing factual review, correction, and link cleanup. The Security track went through a deliberate ML-domain pass during the May 2026 build; others would benefit from a similar pass.
- **Audit-script heuristics**: ✅ Resolved May 26, 2026 — `_meta/scripts/audit_curriculum_quality.py` now (1) recognizes the engineer-track numbered-lecture convention via a `^\d+-.+\.md$` regex check, (2) skips markdown code-block content (no longer flags `grep -r "TODO"` examples or gRPC `Stub` API names), and (3) carries a ~70-entry false-positive phrase list distinguishing teaching scaffolds (`**TODO:** Complete this Dockerfile`, "stubs with educational TODO comments", template `| CISO | TBD |` rows) from actual unfinished work. Sampled-marker count dropped from 294 → 182 across the May 26 passes.

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
