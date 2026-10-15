# 朋友 Space (Pengyou Space)
### A Hyper-Local Social Discovery Platform for University Campuses

**Research Paper | Nantong University | October 2026**

[![Research](https://img.shields.io/badge/Project-Research%20Case%20Study-6C4AB6)](./朋友Space_Research_Paper_v3.pdf)
[![Study](https://img.shields.io/badge/Survey-150%20Students-6C4AB6)](./朋友Space_Research_Paper_v3.pdf)
[![Platform](https://img.shields.io/badge/Focus-Campus%20Social%20Discovery-6C4AB6)](./朋友Space_Research_Paper_v3.pdf)

**What if finding friends on campus were as easy as finding an event?**

朋友 Space (Pengyou Space) is a university-scoped social discovery platform designed to help students discover campus activities, find people with similar interests, and turn online interactions into real-world meetups.

This repository accompanies a research case study examining the campus discovery gap, the design of Pengyou Space, and its reported use among 150 student users at Nantong University, China.

**📄 [Read the full research paper (PDF)](./朋友Space_Research_Paper_v3.pdf)**

---

## 🌱 The Problem: The Campus Discovery Gap

University campuses are full of people who share interests, schedules, hobbies, and opportunities to connect. Yet finding someone to study with, play sports, grab food, or simply hang out with is not always easy.

Students may struggle because they:

- Do not know where other students gather or what activities are happening.
- Feel shy or uncomfortable approaching unfamiliar people.
- Lack a convenient way to discover events and connect with like-minded students.
- Rely on scattered messages, social media feeds, posters, and existing friendship groups.

Pengyou Space approaches this as a **social discovery and coordination problem**, rather than simply a lack of motivation to socialise.

## 💡 The Solution: 朋友 Space

Pengyou Space is built around a simple idea: help students discover what is happening on campus, join activities with shared context, and meet people offline.

### Core platform concepts

- **Campus-focused discovery:** Make relevant activities and hangout opportunities easier to find.
- **Time-and-place activity cards:** Present hangouts and events with their locations, schedules, participants, and available actions.
- **Interest-based connections:** Help students discover others with similar interests.
- **Low-friction participation:** Allow users to join or leave activities and see their social context.
- **Community interaction:** Support group conversations, invitations, comments, and shared media.
- **University-scoped access:** Use authentication and database-level access controls to apply campus boundaries.

The central design principle is to prioritise meaningful real-world interaction over passive scrolling and engagement time.

## 🔬 Research Overview

This study investigates four questions:

1. **RQ1 — Before adoption:** How difficult did students find informal hangout discovery, and what barriers did they experience?
2. **RQ2 — After adoption:** What changes in discovery, interest matching, and joining activities did users report?
3. **RQ3 — User experience:** Which platform features did users value, and what improvements did they request?
4. **RQ4 — Engagement:** What satisfaction and usage patterns emerged, and how did they vary by year of study and campus tenure?

### Methodology at a glance

| Component | Description |
|---|---|
| Research setting | Nantong University, China |
| Study period | October 1–14, 2026 |
| Participants | 150 student users |
| Instrument | 14-item self-report survey |
| Sampling | Non-probabilistic, self-selected participants |
| Analysis | Descriptive statistics, frequency distributions, cross-tabulations, and open-text theme counts |
| Study design | Single-group, retrospective, post-adoption evaluation |

The study focuses on users' reported experiences. It does not treat survey responses as direct measurements of behaviour or as proof of causality.

## 📊 Key Findings

The survey revealed a substantial reported gap between students' desire to socialise and their ability to discover informal campus activities.

| Finding | Result |
|---|---:|
| Students who found hangout discovery difficult before adoption | **77.3%** (116/150) |
| Students who reported that discovery became easier after adoption | **86.7%** (130/150) |
| Students satisfied or very satisfied with the platform | **82.0%** (123/150) |
| Students reporting at-least-weekly usage | **82.0%** (123/150) |
| Students who wanted to socialise at least monthly | **86.7%** (130/150) |

### What challenges did students report?

- **45.3%** did not know where people usually gathered.
- **42.7%** felt shy or awkward approaching others.
- **40.7%** lacked a convenient way to discover events or groups.
- **34.0%** found it difficult to meet people with similar interests.

### What benefits did users report?

- **53.3%** reported easier discovery of hangout spots.
- **52.7%** reported easier connections with people sharing similar interests.
- **49.3%** reported finding events and activities more quickly.
- **48.0%** reported reduced awkwardness when approaching strangers.

These descriptive findings show that the benefits users reported corresponded to several of the difficulties they had identified before adoption.

**Important interpretation:** These figures represent self-reported experiences from a survey of existing platform users. They do not establish that Pengyou Space caused the reported changes or that the results generalise to every university.

## 🛠️ Technology Stack

The application described in the paper uses a modern web-development stack.

| Layer | Technologies |
|---|---|
| Frontend | React 18, TypeScript |
| Build tooling | Vite |
| Styling | Tailwind CSS |
| Routing | React Router v6 |
| Backend services | Supabase |
| Authentication | Supabase Auth, JWT sessions |
| Database | PostgreSQL with Row Level Security (RLS) |
| Realtime features | Supabase Realtime |
| File and media storage | Supabase Storage |
| Server-side workflows | Supabase Edge Functions |
| Testing | Vitest and jsdom |
| Deployment | Netlify or Vercel |

The architecture uses managed backend services to support authentication, relational data, media storage, and realtime communication without requiring a separately managed application server.

## 📖 Research Contributions

This project contributes more than a description of a student-facing application.

- **A documented design case:** An example of a university-scoped, discovery-first platform built around informal campus interaction.
- **First-party user evaluation:** Survey evidence describing pre-adoption difficulties, post-adoption perceptions, satisfaction, and engagement.
- **A reproducible survey instrument:** The complete 14-item questionnaire is provided in Appendix A.
- **Transparent descriptive reporting:** Full frequency tables are provided in Appendix B.
- **Citation verification:** Appendix C documents the manuscript's reference-verification audit.
- **A practical research direction:** A foundation for more rigorous longitudinal and controlled evaluations of campus social discovery systems.

## 📁 Repository Contents

The accompanying manuscript contains the study's methodology, platform description, figures, results, discussion, references, and appendices.

- **`README.md`** — Project and research overview.
- **`朋友Space_Research_Paper_v3.pdf`** — Full research manuscript.
- **Appendix A** — Survey instrument.
- **Appendix B** — Full frequency tables.
- **Appendix C** — Citation verification audit.

The appendix materials are contained within the PDF. Separate data files, application source code, and deployment links should only be listed here if they are actually included or made publicly available.

## ⚠️ Limitations and Responsible Interpretation

This study has several important limitations:

- **No control group:** The study cannot isolate the platform's contribution from other possible explanations.
- **Retrospective self-report:** Participants recalled their earlier experiences and reported their current perceptions.
- **Self-selection:** Participants were existing users who chose to respond; less-engaged or dissatisfied former users may be underrepresented.
- **Single-campus setting:** The sample comes from one university in China.
- **No demonstrated causal effect:** The findings establish reported experiences and descriptive associations, not proof that the platform reduces social isolation.

Future work should investigate longer-term outcomes, compare similar student groups with and without access to the platform, examine actual attendance and join-to-meet conversion under appropriate consent, and evaluate deployments across multiple campuses.

## 🚀 Future Directions

Potential next steps identified by the study include:

- Stronger student-account verification.
- More platform-organised offline activities.
- Improved privacy controls and finer-grained visibility.
- Better interest-matching mechanisms.
- Expansion to additional campuses and cities.
- Longitudinal and controlled evaluations using pre-specified methods.

The long-term goal is to make campus social discovery a practical, trustworthy layer of university life.

## 📄 Read the Paper

The full manuscript includes the related work, system architecture description, research design, survey instrument, detailed results, limitations, and references.

**[→ Open the complete research paper](./朋友Space_Research_Paper_v3.pdf)**

## 📚 Citation

If you reference this work, please cite the manuscript as follows:

> Huda, A. K. (2026). *朋友 Space (Pengyou Space): A Case Study on Developing a Hyper-Local Social Media Platform to Alleviate Student Social Isolation on University Campuses.* Research report, Nantong University, Nantong, China. October 14, 2026.

BibTeX:

```bibtex
@misc{huda2026pengyouspace,
  author       = {Huda, Abu Kayes},
  title        = {{朋友 Space (Pengyou Space): A Case Study on Developing a Hyper-Local Social Media Platform to Alleviate Student Social Isolation on University Campuses}},
  year         = {2026},
  institution  = {Nantong University},
  howpublished = {Research report},
  note         = {October 14, 2026}
}
```

## 👤 Author

**Abu Kayes Huda**  
Computer Science Student, Nantong University  
Nantong, Jiangsu, China

## 🙏 Acknowledgements

The author thanks the Nantong University students who participated in the survey and the developers and maintainers of the open-source technologies used to build the platform.

---

*Designed to help students move beyond discovering content to discovering community.*
