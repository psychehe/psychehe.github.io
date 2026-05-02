---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Information Science (Human-Computer Interaction)**, Cornell University, Aug. 2021 - Dec. 2026
* **B.A. in Linguistics** (Dean's List), University of California, Berkeley, Aug. 2016 - Dec. 2019

Selected Research
======
* **Conversational Dynamics & Multimodal Prediction in Computer-Mediated Communication**, Jan. 2022 - Aug. 2024
  * **Multimodal cues as externalizations of predictive state**: Established that prosody, gaze, and facial expression function as externalizations of speakers' and listeners' real-time predictive models — when these channels are progressively suppressed (video → audio → transcript), word prediction degrades systematically in both accuracy and sensitivity to affect (COLING 2025; *Proc. of the 31st Int'l Conference on Computational Linguistics*, pp. 7949–7962)
  * **Novel computational measure of prediction**: Developed an LLM-based method to approximate human next-word prediction in real-time speech, replacing traditional neuroscience paradigms with a scalable corpus-and-LM approach for quantifying prediction failure in conversational turn-taking
  * **Differential cost of lean channels for non-native speakers**: Showed that L2 listeners are disproportionately affected by the loss of multimodal cues — limited L2 exposure and negative affect compound the cost of lean channels, leaving NNS with higher processing load and less reliable prediction than native speakers under the same conditions (CogSci 2025; eScholarship)
  * **Statistical modeling pipeline**: Built reproducible analysis pipelines for lab-collected behavioral data combining **GLMMs (lme4, lmerTest)**, **LASSO-regularized regression**, and multimodal behavioral coding (ELAN, Praat) across in-lab studies (cumulative N = 300+)
  * **Theoretical contribution**: Identified *which* cognitive mechanisms break down in *which* CMC modalities — providing the empirical foundation for XPLAIN's intervention design

* **AI-Mediated Communication as Cognitive Scaffolds — [XPLAIN](/portfolio/xplain/)**, Aug. 2024 - Present
  * **Theory-driven system vision**: Designed a real-time AI scaffold for non-native speakers in online meetings, grounded in the prediction-breakdown findings above; targets cognitive bottlenecks (semantic prediction failure, temporal pressure, comprehension/production trade-offs) at specific stages of speech processing (CHI EA 2026, CSCW 2025, CUI 2026 under review)
  * **Novel cognitive-fluency metric**: Developed a psycholinguistic measure that synchronizes four multimodal behavioral channels — speech disfluencies, gaze shifts, mouse clicks, and facial expressions — with specific speech-processing stages, enabling real-time inference of emerging cognitive trouble
  * **Phase 1 — Concept validation via three Wizard-of-Oz studies**: Designed and ran three lab-based WoZ studies in which a confederate simulated the AI agent's anticipatory cues, rephrasing, and timing adjustments to validate intervention *type*, *timing*, and *individual fit*:
    * **Baseline scaffolding study (N = 38)**: Evaluated three core scaffolds — lexical clarifications, idea/content suggestions, and topic summaries — in dyadic virtual meetings; demonstrated improvements in **30–80% perceived communicative efficiency**, participation, and inclusivity, moderated by individual differences in language proficiency, personality, and prior AI experience (short WIP at CSCW 2025; full manuscript in preparation)
    * **Personalization study (N = 40)**: Tested context-adaptive interventions calibrated to user-level cognitive dimensions; companion **latent class analysis** on qualitative interview data (n = 29) identified eight two-class groupings across thematic domains (e.g., AI usage and trust, communication strategies, feature-specific evaluations), revealing that user profiles reflect **domain-specific adaptation patterns rather than a global typology** (CogSci 2026, accepted)
    * **Translation study (N = 27)**: Examined how L1- vs. L2-cued translation scaffolds support real-time turn-taking under domain-specific lexical demand, integrating prediction theory, cognitive load theory, and language-dependent memory theory (manuscript in preparation)
  * **Phase 2 — Real-time evaluation pipeline for naturalistic conversation**: Engineered an evaluation pipeline that ingests synchronized multimodal streams (speech, gaze, mouse-click, facial expression) during live online-meeting conversations and outputs real-time estimates of users' **performance and cognitive states** (emerging prediction trouble, processing load, repair initiation); modeled intervention effects with **event-centered GLMMs** and interaction-state shifts via **latent transition models**; cumulative **100+ customer-discovery interviews**
  * **Listener perception (pre-registered, in-field)**: Designed a **pre-registered two-phase blind/informed listener-perception study** (OSF) measuring listeners' implicit detection of AI-assisted conversational speech, acoustic cue attribution, and the moderating effect of prior AI-knowledge — testing whether the same multimodal traces that enable AI scaffolding (disfluency, timing, prosody, visible ease/strain) trigger negative attributions of competence and authenticity from native evaluators, surfacing a **"double bind"** for non-native speakers using AI support
  * **Translation to product & impact**: Selected for the [Cornell eLab Spring 2025 cohort](https://www.elabstartup.com/elab-welcomes-13-startups-to-spring-2025-cohort/) with $5,000 prototype-build funding; identified educational and workplace use cases for bridging knowledge gaps and reducing communication-driven social friction

* **Sustaining Public Goods via Prosocial Behavior**, [Citizens & Technology Lab](https://citizensandtech.org/) (PI: J. Nathan Matias), Cornell University, Jan. 2025 - Present
  * Lead statistician on **parallel pre-registered field experiments** across four Wikipedia language communities (Arabic, German, Persian, Polish; **N = 15,558 editors**), quantifying the causal effect of peer-to-peer gratitude on upstream reciprocity and sustained volunteer participation
  * Built **end-to-end causal inference pipelines** in R: power analyses, intent-to-treat (ITT) and complier-average causal effect (CACE) estimation, multilevel models with cluster-robust standard errors, sensitivity analyses, and cross-community meta-analytic pooling
  * Designed reproducible analysis & visualization workflow handling longitudinal behavioral data (edits, contributions, retention) over multi-month observation windows
  * Translated statistical findings into actionable strategies for online community health and social sustainability; manuscript **under review at *PNAS***

* **Multilingual FrameNet Project**, International Computer Science Institute, Aug. 2019 - Dec. 2019
  * Studied structures of English lexical databases, ran model trainings on semantic relations, and refined labelings for multilingual alignment

Professional Experience
======
* **Founder & Product Lead**, XPLAIN (Proactive Meeting AI), Aug. 2024 - Present
  * Architected a real-time AI-MC system utilizing LLM-based cognitive scaffolding to mitigate miscommunication in online meetings
  * Recruited & directed a 19-person cross-functional research team (UX, Engineering, Data)
  * Secured traction via venture showcases & demos via Cornell eLab incubator

* **Content Strategist (Trust and Safety)**, ByteDance Inc., Dec. 2020 - Jun. 2021
  * Architected a new content moderation framework for sensitive word detection AI models across TikTok, Helo, Fictum (>500M users)
  * Established HITL data-labeling standards and QA evaluation metrics for AI safety models

* **Linguist Intern - Ontology in NLU**, Facebook, July - Aug. 2019
  * Built the first Mandarin NLU model for Facebook AI Assistant chatbot with culture-specific syntactic and semantic adaptations

Technical Skills
======
* **Interactive AI Systems & Prototyping**: Wizard-of-Oz concept validation, real-time multimodal evaluation pipelines (synchronized speech, gaze, mouse, facial expression streams) for naturalistic conversation, web-based experiment platforms, full-stack MVP development
* **AI/LLM Methods**: Prompt & context engineering, in-context learning, LLM-based behavioral simulation, surprisal & next-word-prediction extraction from LMs, speech transcription (Whisper), LSTM/sequence-model fine-tuning (PyTorch, CANDOR multimodal corpus), AI agent task design & benchmarking, human-in-the-loop (HITL) evaluation protocols
* **Quantitative & Statistical Modeling**: GLMMs / multilevel models, causal inference (field experiments, parallel design), latent class & latent transition analysis, regression with regularization (LASSO), time-series prediction, event-centered analyses
* **Qualitative & Mixed-Methods Research**: Semi-structured interviews, inductive thematic coding, contextual inquiry, focus groups, multimodal behavioral coding/annotation, customer-discovery interviews (100+), worker co-design
* **Research Methods**: Experimental design, user studies (80+ in-lab), surveys, usability testing, prototyping
* **Programming & Tools**: Python (pandas, NumPy, scikit-learn, statsmodels, OpenAI/Anthropic APIs), R (tidyverse, lme4, lmerTest), SQL, JsPsych, PsychoPy, Praat, ELAN, Qualtrics, Atlas.ti, Figma, Miro, Git/GitHub, LaTeX, JupyterLab

Languages
======
* **Mandarin Chinese** — Native
* **English** — Fluent
* **German** — B2 (Goethe-Institut PASCH scholar, 2015)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Manuscripts In Preparation
======
* He, W. P. & Fussell, S. R. *Cognitive Trade-offs Between Speech Disfluencies and Active Engagement from Proactive AI-Mediated Scaffolds in Turn-taking.*
* He, W. P. & Fussell, S. R. *Context-Adaptive Translations for Optimized Processing under Time-Pressured AI-Mediated Turn-Taking for Non-Native Speakers.*
* He, W. P. & Fussell, S. R. *Deploying Cognitive Measures as Personalization Metrics for Proactive AI-Mediated Scaffolds in Turn-taking: A Mixed-Methods Study.*
  
Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
**Teaching Assistant**, Cornell University (2022–2025):
* [INFO 2951 Introduction to Data Science](https://classes.cornell.edu/browse/roster/SP25/class/INFO/2951) — Spr 2025
* [INFO 6310 Behavior and Information Technology](https://classes.cornell.edu/browse/roster/FA24/class/INFO/6310) — Fall 2024
* [INFO 4450 Computer-Mediated Communication](https://classes.cornell.edu/browse/roster/SP24/class/INFO/4450) — Spr 2024
* [INFO 4430 Teams and Technology](https://classes.cornell.edu/browse/roster/FA23/class/INFO/4430) — Fall 2023
* [PSYCH 2250 Psychology of Language](https://classes.cornell.edu/browse/roster/SP23/class/PSYCH/2250) — Spr 2023
* [PSYCH 1101 Introduction to Psychology](https://classes.cornell.edu/browse/roster/FA22/class/PSYCH/1101) — Fall 2022
* [HD 4380 Language and Thought](https://classes.cornell.edu/browse/roster/SP22/class/HD/4380) — Spr & Fall 2022

**Guest Lectures**:
* INFO 4450 — Content Prediction in the Fluency of Computer-Mediated Communication (Spr 2024)
* INFO 6310 — Mechanisms of Content Prediction in Computer-Mediated Communication (Fall 2024)

**Student Mentorship** (INFO 4900 Independent Study): Coached 25 undergrads and 14 MEng students in research execution and professional development.
  
Grants & Awards
======
* **Entrepreneurship Lab (eLab) Start-Up Fund**, Cornell University, 2025 — $5,000
* **Research & Travel Grant**, Cognitive Science Program & Cornell University, 2022, 2024, 2025 — $5,000
* **SAGE Fellowship**, Cornell University, 2021-2023 — ~$65,000/year
* **Linguistics Society of America Summer Grant**, UC Berkeley, 2019 — $1,500
* **International PASCH Junior Scholarship**, Goethe-Institut, Germany, 2015 — $15,000

Service & Leadership
======
* **Journal Club Co-Lead**, Cognitive Science of Language Lab (PI: Prof. Morten H. Christiansen), Cornell University, 2021 - 2023 — Led weekly discussions on cutting-edge research in psycholinguistics, computational linguistics, and language cognition for two academic years
* **[W.E. Cornell](https://eship.cornell.edu/w-e-cornell/w-e-cornell-2024-cohort/)**, 2023-24 Cohort — Guided entrepreneurship & leadership program for women in STEM
* **Vice President**, Graduate and Professional Women's Network, Cornell University, Aug. 2022 - Dec. 2024
* **Community Engagement Researcher**, Psychology, Cornell University, May 2022 - Dec. 2022
* **Student Mentorship**: Cumulatively coached 25 undergrads and 14 engineering masters via Independent Study program
