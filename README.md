# Campus AI Curriculum Task Force Research

**University of Illinois at Urbana-Champaign**
**Research Period**: November 2025
**Task Force Chairs**: Derek Hoiem (Grainger Engineering), Shaowen Wang (LAS)

> **⚠️ Methodological Note**: This is an **experiment in AI-assisted research with human steering**. The research employs coordinated AI agents (powered by [Claude Flow](https://github.com/ruvnet/claude-flow)) under human orchestration to achieve breadth and speed without sacrificing rigor. All findings are evidence-based, transparently sourced, and validated by human expertise.

---

## Overview

This repository contains comprehensive research and recommendations for the [University of Illinois Campus AI Curriculum Task Force](https://provost.illinois.edu/about/committees/education-2/campus-ai-curriculum-task-force/), charged by Provost John Coleman to develop a campus-wide AI education strategy.

### Deliverables

- **December 19, 2025**: Short summary update to Provost
- **January 19, 2026**: Full written report with implementation plan

---

## Key Documents

### 🎯 [**TASK-FORCE-SYNTHESIS.md**](research/TASK-FORCE-SYNTHESIS.md)
**Primary deliverable** - Comprehensive 35-page synthesis addressing all six Provost charges with evidence-based recommendations, financial analysis, and implementation roadmap.

**Key Recommendations**:
1. **AI Minor**: 18-credit dual-track program (Technical/Applications), launch Fall 2026
2. **X+AI Degrees**: 30-credit AI core, multi-college governance, launch Fall 2027
3. **AI Certificate**: 12-credit stackable credential
4. **Scalable Delivery**: Hybrid model leveraging UIUC's online infrastructure
5. **Graduate Transfer**: Direct articulation with MS programs
6. **Ethics Integration**: Hybrid approach (standalone + embedded modules)

### 🔬 [**RESEARCH-METHODOLOGY-ARTICLE.md**](RESEARCH-METHODOLOGY-ARTICLE.md)
**Process transparency** - Detailed explanation of our AI-assisted swarm research methodology, quality assurance measures, and how we ensured rigor while achieving speed. Essential reading for stakeholders interested in understanding how this research was conducted.

**Key Points**:
- 6 specialized AI agents working in parallel
- 200+ sources with validation protocols
- Human orchestration and validation at every stage
- Evidence-based recommendations traced to sources
- Transparent, verifiable, and reproducible methodology

---

## Research Domains

Our research was conducted using a **coordinated swarm of 6 specialized agents** (see [detailed agent documentation](agents/)), each focusing on a critical domain:

### 📊 Agent Alpha: Institutional Context
**File**: [`research/institutional/uiuc-ai-landscape.md`](research/institutional/uiuc-ai-landscape.md)

**Key Findings**:
- UIUC ranks **Top 5** nationally in AI with **$270M** in funding since 2019
- **14 CS+X programs** (1,098 students) - proven interdisciplinary model
- **4 X+DS programs** (850 students) - accessible data science pathways
- World-class AI infrastructure: DeltaAI, IBM-Illinois ($200M), C3.ai DTI

**Lessons Learned**: 9+ years of CS+X data provides blueprint for AI minor governance

---

### 👥 Agent Beta: Task Force Member Profiling
**File**: [`research/members/task-force-profiles.md`](research/members/task-force-profiles.md)

**Key Findings**:
- **6 technical AI experts**: Hoiem (computer vision), Wang (spatial AI), Lourentzou (multimodal learning)
- **5 curriculum/pedagogy specialists**: Lewis (equity), Magee (generative AI in education), Brantner (portfolio strategy)
- **Gies Business School strength**: Brantner + Brown bring stackable credentials expertise, scalability experience

**Strategic Insights**: Task force composition ensures balance between technical rigor, pedagogical soundness, and equity focus

---

### 🏛️ Agent Gamma: Peer University Programs
**File**: [`research/peer-programs/comparative-analysis.md`](research/peer-programs/comparative-analysis.md)

**Universities Analyzed**: MIT, Stanford, Carnegie Mellon, UC Berkeley, Georgia Tech, Michigan, Purdue, UW-Madison, Northwestern, Ohio State, Penn State, Minnesota

**Key Findings**:
- **7 of 12** universities offer AI minors (launched 2024-2025)
- **Georgia Tech**: Pioneered dual-track model (Engineering/Liberal Arts)
- **Northwestern**: 146 students in first year (rapid growth)
- **Penn State**: Stackable credentials (certificate → minor → MS)
- **Credit range**: 15-26 credits (5-7 courses)
- **All exclude CS majors** from minors

**Best Practice**: Dual-track design accommodates both technical depth and applications focus

---

### 📚 Agent Delta: Curriculum & Pedagogy
**File**: [`research/curriculum/pedagogy-framework.md`](research/curriculum/pedagogy-framework.md)

**Key Findings**:
- **CS2023 Guidelines**: First-ever ACM + IEEE-CS + AAAI collaboration (endorsed Jan-Feb 2024)
- **Three-tier learning outcomes**: Foundational (all students), Intermediate (AI minor), Advanced (X+AI degrees)
- **Four prerequisite pathways**: Minimal, low-code/no-code, mathematics-first, flexible entry
- **Evidence-based pedagogy**: Project-based learning shows 37% increase in interdisciplinary outcomes
- **MOOC evolution**: Massive AI-empowered Courses (MAIC) for scalability

**Framework**: Comprehensive assessment tools, UDL principles, AI-enabled instruction

---

### ⚖️ Agent Epsilon: Ethics & Society Integration
**File**: [`research/ethics/responsible-ai-framework.md`](research/ethics/responsible-ai-framework.md)

**Key Findings**:
- **Hybrid approach** shows strongest outcomes: Standalone course + embedded modules
- **Stanford HAI**, **MIT Media Lab**, **Harvard Embedded EthiCS** provide models
- **UNESCO AI Competency Framework** (193 member states)
- **Industry frameworks**: Microsoft (6 principles), Google AI Principles, IBM Fairness 360

**Core Topics**: Algorithmic bias, privacy, explainability, accountability, environmental sustainability (300K kg CO2 per large model), economic inequality

**Assessment**: AI Ethical Reflection Scale (AIERS) - validated with 730 students

---

### 💼 Agent Zeta: Administrative & Financial Models
**File**: [`research/administration/governance-financial-models.md`](research/administration/governance-financial-models.md)

**Key Findings**:
- **Recommended structure**: Provost coordination with distributed delivery (like X+DS)
- **Financial projections**: $430K-$750K Year 1 → Revenue neutral by Year 3-4
- **Resource needs**: 2.0 FTE (Y1) → 5.0 FTE (Y5) faculty; 1.75 FTE (Y1) → 4.5 FTE (Y5) staff
- **Enrollment targets**: 150 (Y1) → 400-600 (Y5)
- **Revenue model**: 90% to teaching departments, 10% to Provost coordination

**Case Studies**: UIUC CS+X/X+DS, MIT, Stanford HAI, CMU, Big Ten multi-college programs

---

## Provost's Six Charges

### 1. Campus-Wide Undergraduate AI Minor ✅
**Recommendation**: 18-credit dual-track program
- **Track 1 (Technical)**: For STEM students, technical depth
- **Track 2 (Applications)**: For non-STEM, accessible prerequisites
- **Housing**: Provost coordination, distributed delivery
- **Launch**: Fall 2026 (pilot with 50-75 students)
- **Cost**: $430K-$750K Year 1

### 2. X+AI Blended Degree Model ✅
**Recommendation**: 30-credit AI core + domain expertise
- **AI Core**: Foundation (12 cr), Advanced (9 cr), Ethics (3 cr), Capstone (6 cr)
- **Differs from CS+X**: Less CS depth, more domain depth
- **Differs from X+DS**: AI algorithms vs. data analysis focus
- **Governance**: Multi-college with Provost coordination
- **Pilots (Fall 2027)**: Business+AI, Agriculture+AI, iSchool+AI

### 3. Stackable AI Certificate ✅
**Recommendation**: 12-credit certificate
- **Stackability**: Certificate (12 cr) → Minor (18 cr) → X+AI Degree (30 cr AI core)
- **Target**: Exploratory undergrads, career professionals, cross-college students
- **Delivery**: Hybrid (online + optional in-person)

### 4. Scalable Delivery Model ✅
**Recommendation**: Hybrid model leveraging UIUC's MCS-DS experience
- **In-person**: Labs, team projects, ethics discussions
- **Online**: Lectures (pre-recorded), coding exercises (auto-graded), async discussions
- **Infrastructure**: Cloud computing, GPU access, Jupyter notebooks
- **Faculty development**: Summer 2026 intensive

### 5. Graduate Education Transfer ✅
**Recommendation**: Direct articulation pathways
- **AI Minor → MS in CS (AI Specialization)**: 6-9 credits count, 4+1 program possible
- **X+AI → Domain MS**: AI core provides foundation
- **New MS in AI**: 32 credits, domain specializations
- **PhD pathways**: Interdisciplinary dual-title PhDs

### 6. Ethics & Social Responsibility ✅
**Recommendation**: Hybrid integration model
- **Standalone course**: 3-credit "AI Ethics and Society" (required for all)
- **Embedded modules**: Throughout technical curriculum (ML, NLP, Vision, Robotics)
- **Interdisciplinary electives**: AI & Law, AI & Policy, AI & Social Justice
- **Partnerships**: Philosophy, Law, Sociology, Environmental Sciences, Gies

---

## Implementation Timeline

| Date | Milestone |
|------|-----------|
| **Dec 19, 2025** | Short summary to Provost |
| **Jan 19, 2026** | Full written report |
| **Feb 2026** | Steering committee formed |
| **March 2026** | Program director hired |
| **Summer 2026** | Faculty development intensive |
| **Fall 2026** | AI Minor & Certificate pilot (75-115 students) |
| **Fall 2027** | X+AI degrees launch (3 programs) |
| **Fall 2028** | Financial sustainability achieved |
| **Spring 2029** | First X+AI graduates |

---

## Financial Summary

### 5-Year Projections

| Year | Students | Total Cost | Revenue | Net |
|------|----------|------------|---------|-----|
| 1 (2026-27) | 115 | $430K | $180K | -$250K |
| 2 (2027-28) | 225 | $625K | $360K | -$265K |
| 3 (2028-29) | 350 | $825K | $630K | -$195K |
| 4 (2029-30) | 450 | $975K | $900K | -$75K |
| 5 (2030-31) | 550 | $1,025K | $1,100K | +$75K |

**Cumulative Investment**: $1.03M over 5 years
**Break-Even**: Year 5 (potentially Year 4 with strong enrollment)
**Long-Term**: Revenue positive Year 6+

---

## Repository Structure

```
ai-taskforce/
├── README.md (this file)
├── RESEARCH-METHODOLOGY-ARTICLE.md (methodology transparency)
├── PROVOST-CHARGE.md (official task force charge)
├── session.txt (original web session transcript)
├── agents/ 🤖 AGENT DOCUMENTATION
│   ├── agent-alpha-institutional.md
│   ├── agent-beta-stakeholders.md
│   ├── agent-gamma-peer-analysis.md
│   ├── agent-delta-curriculum.md
│   ├── agent-epsilon-ethics.md
│   └── agent-zeta-administration.md
├── research/
│   ├── TASK-FORCE-SYNTHESIS.md ⭐ PRIMARY DELIVERABLE
│   ├── institutional/
│   │   └── uiuc-ai-landscape.md (Agent Alpha output)
│   ├── members/
│   │   └── task-force-profiles.md (Agent Beta output)
│   ├── peer-programs/
│   │   └── comparative-analysis.md (Agent Gamma output)
│   ├── curriculum/
│   │   └── pedagogy-framework.md (Agent Delta output)
│   ├── ethics/
│   │   └── responsible-ai-framework.md (Agent Epsilon output)
│   └── administration/
│       └── governance-financial-models.md (Agent Zeta output)
```

---

## Task Force Members

### Co-Chairs
- **Derek Hoiem** - Professor, Grainger College of Engineering
- **Shaowen Wang** - Associate Dean, College of Liberal Arts & Sciences

### Members
1. Brandon Batzloff - Interim Associate Dean, School of Information Sciences
2. Amanda Brantner - Senior Director, Gies College of Business
3. Nerissa Brown - Executive Associate Dean, Gies College of Business
4. Elhan Ersoz - Clinical Assistant Professor, ACES
5. Colleen Lewis - Associate Director, Grainger Engineering
6. Ismini Lourentzou - Assistant Professor, School of Information Sciences
7. Liam Magee - Professor, College of Education
8. Luc Paquette - Associate Professor, College of Education
9. John Reid - Executive Director, Center for Digital Agriculture
10. Kevin Scharp - Professor, College of Liberal Arts and Sciences
11. David Ward - Associate Professor, University Library

### Ex Officio
- Wojtek Chodzko-Zajko - Vice Provost for Graduate Education
- Ingrid Fulmer - Advisor for Strategic Initiatives, Office of the Provost
- Kevin Jackson - Vice Provost for Undergraduate Education

---

## Research Methodology

### Swarm Research Architecture

**This is an experiment in AI-assisted research with human steering.** We used a **hierarchical swarm** of 6 specialized research agents (powered by [Claude Flow](https://github.com/ruvnet/claude-flow)) working in parallel under human orchestration:

1. **Agent Alpha** - Institutional context (UIUC AI landscape, existing programs)
2. **Agent Beta** - Stakeholder analysis (task force member profiling)
3. **Agent Gamma** - Competitive analysis (12 peer universities)
4. **Agent Delta** - Curriculum design (learning outcomes, pedagogy)
5. **Agent Epsilon** - Ethics integration (responsible AI frameworks)
6. **Agent Zeta** - Administration (governance, financial models)

**Human Role**: Research design, agent orchestration, synthesis validation, strategic framing
**AI Role**: Parallel research execution, source gathering, evidence compilation, structured analysis

**Total Research**: 200+ sources across six domains
**Synthesis**: Integrated findings addressing all six Provost charges
**Duration**: Parallel execution over 1 day (Nov 23, 2025)

**Credits**: AI agent infrastructure provided by [Claude Flow](https://github.com/ruvnet/claude-flow)

---

## Key Insights

### 🎯 UIUC's Competitive Advantage
- **Proven models**: 14 CS+X programs (9+ years), 4 X+DS programs (2 years)
- **Infrastructure**: $270M in AI funding, DeltaAI, IBM-Illinois, C3.ai DTI
- **Faculty expertise**: World-class researchers across CS, ECE, Statistics, iSchool
- **Online experience**: Successful MCS-DS program demonstrates scalability

### 🚀 Opportunity for National Leadership
- Most peer universities launched AI minors in 2024-2025 (very recent)
- X+AI blended degrees barely exist (Bowling Green first in Fall 2025)
- UIUC can lead with dual-track model + stackable credentials + proven governance

### ⚖️ Risk of Inaction
- Students graduate without AI skills → job market disadvantage
- Peer universities establish leadership while UIUC lags
- Industry partnerships look elsewhere for AI talent
- UIUC's innovation reputation diminishes

---

## Contact

**Research Team**: Campus AI Curriculum Task Force Research Swarm
**Date**: November 2025
**Repository**: https://github.com/vishalsachdev/ai-taskforce

---

## License

Research conducted for the University of Illinois at Urbana-Champaign Campus AI Curriculum Task Force.

---

**"The time to act is now. UIUC has the expertise, resources, and institutional capacity to lead the nation in AI education."**
