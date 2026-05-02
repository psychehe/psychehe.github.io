---
title: "XPLAIN — Proactive Meeting AI"
excerpt: "A real-time AI-mediated communication system that uses LLM-based cognitive scaffolding to support non-native speakers in online meetings. Selected for Cornell eLab 2024 cohort."
collection: portfolio
---

## XPLAIN — Proactive Meeting AI

XPLAIN is a real-time AI-mediated communication system that leverages LLM-based cognitive scaffolding to mitigate miscommunication in online meetings. Grounded in psycholinguistic theory, XPLAIN targets cognitive bottlenecks—such as semantic prediction failures and temporal pressure—to proactively support non-native speakers during turn-taking.

### The Problem

Non-native speakers face significant cognitive challenges in real-time spoken communication: processing unfamiliar vocabulary under time pressure, predicting upcoming content, and formulating responses—all simultaneously. Existing translation tools are reactive and disrupt conversational flow.

### The Approach

XPLAIN proposes **proactive scaffolds** that intervene at specific speech processing stages, providing context-adaptive support before comprehension breakdowns occur. The research-and-design program centers on:

- **Cognitive bottlenecks as design targets** — framing semantic prediction failure, temporal pressure, and comprehension/production trade-offs as theory-grounded points of intervention
- **Multimodal behavioral signals** (speech disfluency, gaze, mouse click, facial expression) mapped to specific speech-processing stages, used to detect emerging trouble in real time
- **Algorithmic personalization** via latent class analysis to adapt interventions to individual user traits
- A staged build path — Wizard-of-Oz concept validation followed by an engineered real-time evaluation pipeline that instruments live conversation

### Validation

XPLAIN's evaluation is staged across three lab-based Wizard-of-Oz studies and an ongoing pre-registered listener-perception study:

- **Baseline scaffolding study (N = 38)** — evaluated three core scaffolds (lexical clarifications, idea/content suggestions, topic summaries) in dyadic virtual meetings; demonstrated improvements of **30–80% in perceived communicative efficiency**, participation, and inclusivity, moderated by individual differences (short WIP at CSCW 2025; full manuscript in prep)
- **Personalization study (N = 40)** — tested context-adaptive interventions calibrated to user-level cognitive dimensions; companion latent class analysis (n = 29) revealed user heterogeneity across eight thematic domains (CogSci 2026, accepted)
- **Translation study (N = 27)** — examined L1- vs. L2-cued translation scaffolds in real-time turn-taking under domain-specific lexical demand (manuscript in prep)
- **Listener perception (pre-registered, in-field)** — measuring listeners' implicit detection of AI-assisted speech, acoustic cue attribution, and the moderating effect of prior AI-knowledge
- **100+ customer-discovery interviews** with target users (knowledge workers, multilingual students)
- Event-centered **GLMMs** and **latent transition models** for evaluating intervention effects and interaction-state shifts

### Prototype & Evaluation Infrastructure

XPLAIN's research and product roadmap is staged around two complementary phases — **concept validation** through Wizard-of-Oz, followed by an **engineered real-time evaluation pipeline** that instruments live conversation for naturalistic usability testing.

- **Phase 1 — Wizard-of-Oz concept validation** — three lab-based studies (baseline N=38, personalization N=40, translation N=27) in which a confederate simulated the AI agent's anticipatory cues, rephrasing, and timing adjustments, used to validate intervention *type*, *timing*, and *individual fit* before engineering investment
- **Phase 2 — Real-time evaluation pipeline** — engineered a pipeline that ingests synchronized multimodal streams (speech, gaze, mouse-click, facial expression) during live online-meeting conversations and outputs real-time estimates of users' performance and cognitive states (emerging prediction trouble, processing load, repair initiation), enabling iterative usability testing in naturalistic conversations
- **Cognitive fluency metric** — a novel quantifiable measure of cognitive fluency in AI-mediated speech, derived by mapping multimodal behavioral signals (speech disfluency, gaze, mouse clicks, facial expressions) to specific speech-processing stages
- **Task-level benchmarks & HITL evaluation** — defined task taxonomy, behavioral metrics, and success criteria; architected human-in-the-loop evaluation protocols for real-time AI agents
- **Algorithmic personalization framework** — translated qualitative insights from inductive coding of 1:1 interviews and surveys into dynamic metrics that adapt agent interventions to individual cognitive traits

The roadmap is driven by a 19-person cross-functional team (UX, Engineering, Data), with traction secured through venture showcases and demos via the Cornell eLab incubator.

### Personalization

A core contribution of XPLAIN is its **adaptive personalization engine**, which optimizes the amount and complexity of information output in real time based on three user-level cognitive dimensions:

- **Language proficiency** — adjusting vocabulary complexity, syntactic density, and the granularity of contextual cues to match each user's comprehension capacity
- **Metacognitive awareness** — calibrating how explicitly the system externalizes processing support (e.g., flagging ambiguity vs. silently simplifying) based on users' self-monitoring ability and communication strategies
- **Working memory** — regulating information load per turn to prevent cognitive overload, particularly under the temporal pressure of live conversation

Using latent class analysis, we identified distinct user subgroups characterized by different patterns of externalization and responsiveness to AI support — showing that cognitive traits and cultural/strategic preferences jointly shape how people repair and maintain shared understanding. This person-centered approach drives XPLAIN's adaptive behavior: rather than one-size-fits-all scaffolding, the system tailors its interventions to each user's cognitive profile.

**Impact across settings:**

- **Educational settings** — bridging knowledge gaps for multilingual students in classroom discussions and group projects, facilitating more equitable participation
- **Workplace settings** — supporting non-native professionals in meetings and cross-cultural collaboration, facilitating knowledge transfer and reducing social awkwardness arising from communication asymmetries
- **Cross-cultural collaboration** — mitigating harmful attribution asymmetries where non-native speakers' visible effort under AI mediation can be misread as incompetence by native evaluators

### Team & Incubation

I founded and lead a **19-person cross-functional research team** (UX, Engineering, Data) and drove the end-to-end product roadmap from vision to full-stack MVP in under 8 months.

XPLAIN was selected for the [**Cornell eLab Student Startup Accelerator**](https://www.elabstartup.com/) — one of only 13 teams advancing to the Spring 2025 cohort (out of 24 accepted in Fall 2024), receiving a **$5,000 investment** and continued mentorship.

### Featured In

- [**W.E. Cornell 2023-24 Cohort**](https://eship.cornell.edu/w-e-cornell/w-e-cornell-2024-cohort/) — Entrepreneurship at Cornell (W.E. Cornell guided entrepreneurship & leadership program for women in STEM)
- [**eLab Welcomes 24 Student Startup Teams to Fall Cohort**](https://news.cornell.edu/stories/2024/10/elab-welcomes-24-student-startup-teams-fall-cohort) — Cornell Chronicle, Oct. 2024
- [**eLab Welcomes 13 Startups to Spring 2025 Cohort**](https://www.elabstartup.com/elab-welcomes-13-startups-to-spring-2025-cohort/) — eLab Blog, Feb. 2025
- [**Students Pitch Startups at Autodesk Gallery**](https://news.cornell.edu/stories/2026/04/students-pitch-startups-autodesk-gallery) — Cornell Chronicle, Apr. 2026 (Cornell Silicon Valley: Student Startup Showcase at Autodesk Gallery, San Francisco)
- [**Eclectic Convergence**](https://eship.cornell.edu/event/eclectic-convergence/) — Entrepreneurship at Cornell's annual NYC entrepreneurship summit, featuring startup pitches to investors and the Cornell alumni network

### Related Publications

- He, W. P. & Fussell, S. R. (2026). "XPLAIN: A Proactive Scaffold Across Speech Processing Stages." *CUI 2026*. (Under review)
- He, W. P. & Fussell, S. R. (2026). "User Heterogeneity in AI-Mediated Communication: Extending Cognitive Theories via Latent Class Analysis." *CogSci 2026*. (Accepted)
- He, W. P. (2026). "Disfluency as a Window into Cognitive Mediation." *CHI EA 2026*. [Paper](https://drive.google.com/file/d/1YB9yG12XW01DvO6hbD5Tau3iy6sPmG40/view)
- He, W. P. & Fussell, S. R. (2025). "Proactivity in Scaffolding Comprehension and Production in Real-Time Turn-Taking." *CSCW Companion '25*. [Paper](https://doi.org/10.1145/3715070.3749273)

### Manuscripts In Preparation

- He, W. P. & Fussell, S. R. "Cognitive Trade-offs Between Speech Disfluencies and Active Engagement from Proactive AI-Mediated Scaffolds in Turn-taking."
- He, W. P. & Fussell, S. R. "Context-Adaptive Translations for Optimized Processing under Time-Pressured AI-Mediated Turn-Taking for Non-Native Speakers."
- He, W. P. & Fussell, S. R. "Deploying Cognitive Measures as Personalization Metrics for Proactive AI-Mediated Scaffolds in Turn-taking: A Mixed-Methods Study."
