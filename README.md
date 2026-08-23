<h1 align="center">Jose Lopez</h1>

<p align="center">
  <em>Architecting the intersection of biological and artificial intelligence.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jafdl"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:contacto@auto-latam.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail&logoColor=white"></a>
  <a href="https://auto-latam.com"><img alt="Website" src="https://img.shields.io/badge/Website-Visit-1f6feb?style=flat&logo=githubpages&logoColor=white"></a>
  <a href="https://medium.com/@j.b.lopez.acc"><img alt="Medium" src="https://img.shields.io/badge/Medium-Read-12100E?style=flat&logo=medium&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Madrid,%20Spain-📍-555">
</p>

---

### About me

I'm an AI engineer working across **computational neuroscience**, **computer vision**, **natural language understanding**, and **robotics**, with a foundation in **neuroscience** and **psychology**. I'm interested in the principles that biological systems use to perceive, learn, and act — and how to translate those into machines that do the same.

Most of my public work falls into four buckets:

- **Research at the neuro–AI boundary** — PhD-level work on geometric signatures of computational motifs in neural population dynamics, cortical-model reproduction (Thousand Brains / Monty), and real-time brain–computer interfaces.
- **Agentic and evolutionary systems** — neuroevolution for autonomous agents, agentic LLM systems, AlphaZero-style game AI, and reinforcement-learning playgrounds (classic control, Atari, cellular automata).
- **Document and language intelligence** — generative models for cleaning, restoring, and understanding scanned documents (cGANs, OCR pipelines), plus NLU-driven conversational systems.
- **Production engineering** — Dockerized microservices, async task queues, and cloud deployments around the above.

---

### What I'm working on

<!-- TODO: keep this section fresh — update every 4–8 weeks. Stale "currently working on" sections are worse than none. -->

- 🧠 **Brain–computer interfaces** — just shipped [flappy-brain-bci](https://github.com/aifriend/flappy-brain-bci) at the ISRC CN3 Hackathon 2026: a real-time motor-imagery EEG controller (CSP + LDA, LSL in, UDP out) that flies a Flappy Bird clone with your mind.
- 🧬 **Cortical models** — reproducing and extending the Thousand Brains model (Monty) in [milbrain-showcase](https://github.com/aifriend/milbrain-showcase): verified reproduction, interactive results dashboard, and a plan to grow the architecture via indirect encoding.
- 🔬 **Geometric signatures** — pushing [geometric-signatures-proposal](https://github.com/aifriend/geometric-signatures-proposal) into Phase 3: biological validation on IBL and Allen Brain Observatory data, testing whether the geometric motif signatures discovered in constrained RNNs (persistent homology + RSA/CKA + MARBLE) hold up in real cortex.
- 🤖 **Embodied & evolutionary agents** — training general-purpose and embodied agents with Gymnasium + MuJoCo in [evosim](https://github.com/aifriend/evosim), and iterating on [f1-neuroevolution](https://github.com/aifriend/f1-neuroevolution) (80 AI cars, 7-level curriculum, Three.js visualization).
- 🎮 **Game AI** — building [lighthouse_ai](https://github.com/aifriend/lighthouse_ai), a unified AI platform for the FaROS LaSER lighthouse strategy game plus an AlphaZero framework for board games.
- 📝 **Latest writeup** — [*Why I trained 80 cars to race using nothing but mutation and selection*](https://medium.com/@j.b.lopez.acc/why-i-trained-80-cars-to-race-using-nothing-but-mutation-and-selection-b08e42ba07b2) — a field report on neuroevolution, gradient-free learning, and what the cars surprised me with.
- 📚 **Reading** — *Self-Assembling Brain* (Peter Robin Hiesinger).

---

### Featured projects

**🧬 Research at the neuro–AI boundary**

| Project | What it does | Stack |
|---|---|---|
| [**flappy-brain-bci**](https://github.com/aifriend/flappy-brain-bci) | Real-time motor-imagery EEG controller (CSP + LDA, LSL in, UDP out) for the Flappy Brain game — ISRC CN3 Hackathon 2026. | Python · EEG · LSL · BCI |
| [**milbrain-showcase**](https://github.com/aifriend/milbrain-showcase) | Reproducing & extending the Thousand Brains cortical model (Monty): verified reproduction, interactive dashboard, and growth plan via indirect encoding. | Python · Monty · Neuroscience |
| [**geometric-signatures-proposal**](https://github.com/aifriend/geometric-signatures-proposal) | PhD codebase — discovering geometric signatures of reusable computational motifs in neural population dynamics. Constrained RNNs + biological validation on IBL & Allen Brain Observatory. | Python · PyTorch · uv · Streamlit |
| [**computational_neuroscience**](https://github.com/aifriend/computational_neuroscience) | Computational neuroscience experiments and learning notebooks — neural dynamics, encoding, decision theory, statistical inference. | Python · Notebooks |

**🤖 Agentic, evolutionary & simulation systems**

| Project | What it does | Stack |
|---|---|---|
| [**f1-neuroevolution**](https://github.com/aifriend/f1-neuroevolution) | 80 AI cars learn F1-style racing through genetic algorithms across a 7-level track curriculum. Browser visualization + headless trainer with plateau-based escalation. | JavaScript · Three.js · Node · Vitest |
| [**evosim**](https://github.com/aifriend/evosim) | Training general-purpose and embodied agents with Gymnasium and MuJoCo. | Python · Gymnasium · MuJoCo |
| [**emergence-sims**](https://github.com/aifriend/emergence-sims) | Interactive simulation portfolio — emergence, minds, agents & markets, live in the browser. | Next.js · Three.js · TypeScript |
| [**lighthouse_ai**](https://github.com/aifriend/lighthouse_ai) | Unified AI platform for the FaROS LaSER lighthouse strategy game + AlphaZero framework for board games. | Python · AlphaZero · RL |
| [**aiasis**](https://github.com/aifriend/aiasis) | In-ear AI assistant — listens via AirPods, reasons about conversations, whispers coaching insights back. | Python · LLMs |
| [**pong**](https://github.com/aifriend/pong-game-train) · [**atari**](https://github.com/aifriend/atari57-sandbox) · [**gameoflife**](https://github.com/aifriend/gameoflife-sandbox) | Simulation playgrounds — classic control, Atari environments, and Conway-style cellular automata for RL and emergent-behavior experiments. | Python · Pygame · RL |

**📄 Document & language intelligence**

| Project | What it does | Stack |
|---|---|---|
| [**doc_watermark_cleaner**](https://github.com/aifriend/doc_watermark_cleaner) | Conditional GAN (DE-GAN–style) for watermark removal, binarization, deblurring, and cleaning of scanned documents. | Python · TensorFlow · cGAN |
| [**pdf2readable**](https://github.com/aifriend/pdf2readable) | OCR microservice that turns PDFs and images into searchable text. Apache Tika + Tesseract, Celery async, AWS S3, Docker, Serverless. | Python · Flask · Celery · Tika · AWS |
| [**llm_framework**](https://github.com/aifriend/llm_framework) | LLM framework for structured data extraction from documents. | Python · LLMs |
| [**virtual_assistant**](https://github.com/aifriend/virtual_assistant) | Rasa-based virtual assistant with NLU pipelines, custom actions, and Docker Compose stacks. | Python · Rasa · NLP |

**🚀 Production engineering**

| Project | What it does | Stack |
|---|---|---|
| [**car_sharing_pooling_service**](https://github.com/aifriend/car_sharing_pooling_service) | FastAPI microservice for car-pool matching with FIFO queueing, fully Dockerized. | Python · FastAPI · Docker |
| [**nlp_service_template**](https://github.com/aifriend/nlp_service_template) | Template for shipping ML/NLP microservices — Flask + Gunicorn + Docker + AWS Lambda (Serverless). | Python · Flask · Docker |
| [**ds_template**](https://github.com/aifriend/ds_template) | Opinionated Python project template for data science — pre-wired structure for notebooks, src, data, and reproducible experiments. | Python · Cookiecutter |

---

### Tech I work with

<p>
  <img alt="Python"      src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img alt="PyTorch"     src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white">
  <img alt="TensorFlow"  src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white">
  <img alt="NumPy"       src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white">
  <img alt="SciPy"       src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white">
  <img alt="JavaScript"  src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black">
  <img alt="TypeScript"  src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img alt="Three.js"    src="https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white">
  <img alt="Next.js"     src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white">
  <img alt="Node.js"     src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white">
  <img alt="FastAPI"     src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white">
  <img alt="Flask"       src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white">
  <img alt="Celery"      src="https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white">
  <img alt="Docker"      src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img alt="AWS"         src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white">
  <img alt="OpenCV"      src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white">
  <img alt="Hugging Face" src="https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=flat">
  <img alt="ROS"         src="https://img.shields.io/badge/ROS-22314E?style=flat&logo=ros&logoColor=white">
</p>

---

### GitHub stats

<p align="center">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=aifriend&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aifriend&layout=compact&hide_border=true&theme=tokyonight">
</p>

---

### Beyond code

- **Brain ↔ machine analogies.** I think biological inspiration is undervalued as a source of architectural ideas. My PhD work pushes on this directly — looking for the geometric signatures that distinguish a circuit doing *normalization* from one doing *attractor dynamics*, in both RNNs and real cortex.
- **Open to collaboration** on neural population analysis, BCIs, neuroevolution, agentic systems, and document intelligence — drop me a line.

---

<p align="center"><em>"The best way to predict the future is to invent it."</em> — Alan Kay</p>
