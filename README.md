# Harsh Gupta

Final-Year Student at IIT Kanpur | AI Systems & Infrastructure  
Building agent runtimes, LLM performance instrumentation, and on-device applications.

I focus on the engineering layer of AI systems—profiling runtime overhead, instrumenting model inference, and building local-first developer tools.

---

### Tech Stack

**AI & Agent Frameworks**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Gemini Nano](https://img.shields.io/badge/Gemini_Nano-8E75C2?style=flat-square&logo=google&logoColor=white)

**Backend & Data**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

**Systems & Infrastructure**  
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

**Frontend & Desktop**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri_v2-FFC131?style=flat-square&logo=tauri&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

### Featured Projects

#### [Forge](https://github.com/harshgupta-23/Forge)
*Local-first autonomous desktop AI agent with dynamic tree branching.*
* **What it does:** Allows users to interact with LLMs through an interactive decision-tree canvas, exploring alternate prompts without losing conversational context.
* **Key Implementation:** Built a multi-node LangGraph backend with JIT context pruning (compacting prior failed tool attempts and filtering historical turn relevance) to reduce token consumption. Packaged in a native Tauri v2 shell with sandboxed tool execution and hybrid pgvector retrieval.
* **Stack:** Tauri v2, Rust, Python, LangGraph, FastAPI, PostgreSQL (pgvector), Docker

#### [LLM Pipeline Profiler](https://github.com/harshgupta-23/llm-pipeline-profiler)
*Full-stack telemetry and performance instrumentation tool for LLM execution.*
* **What it does:** Instruments and visualizes latency, memory consumption, and kernel-level bottlenecks across LLM inference and fine-tuning pipelines.
* **Key Implementation:** Combines an in-memory Python tracer (`torch.profiler`) with an out-of-process C++ system sampler (NVML and `/proc` over Unix domain sockets) to decouple sampling overhead from the execution loop. Streams traces to a Next.js/PostgreSQL dashboard for run-to-run comparison and CUDA flamegraphs.
* **Stack:** Python, C++, PyTorch CUDA, Next.js, TypeScript, PostgreSQL, Prisma

#### [PromptLift](https://github.com/harshgupta-23/promptlift)
*Zero-cloud on-device Chrome extension for real-time prompt enhancement.*
* **What it does:** Rewrites rough draft prompts into structured, high-context queries directly inside Claude, ChatGPT, and Gemini web interfaces.
* **Key Implementation:** Interfaces with Chrome's native Prompt API (Gemini Nano) for on-device inference without external API keys or remote egress. Features custom DOM adapters for React, ProseMirror, and Lexical editors alongside a user-only context scraper.
* **Stack:** Chrome Extension (Manifest V3), JavaScript, Gemini Nano, CSS

---

### GitHub Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api?username=harshgupta-23&show_icons=true&theme=github_dark&hide_border=true&hide_rank=true&include_all_commits=true&count_private=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-fast.vercel.app/api?username=harshgupta-23&show_icons=true&theme=github_light&hide_border=true&hide_rank=true&include_all_commits=true&count_private=true" />
    <img src="https://github-readme-stats-fast.vercel.app/api?username=harshgupta-23&show_icons=true&theme=github_dark&hide_border=true&hide_rank=true&include_all_commits=true&count_private=true" alt="Harsh's GitHub stats" height="150" />
  </picture>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=harshgupta-23&layout=compact&theme=github_dark&hide_border=true&hide=jupyter%20notebook,tex,html,css,makefile" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=harshgupta-23&layout=compact&theme=github_light&hide_border=true&hide=jupyter%20notebook,tex,html,css,makefile" />
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=harshgupta-23&layout=compact&theme=github_dark&hide_border=true&hide=jupyter%20notebook,tex,html,css,makefile" alt="Top Languages" height="150" />
  </picture>
</p>

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-harshguptaiitk-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshguptaiitk)
[![Email](https://img.shields.io/badge/Email-harshgupta.180206%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:harshgupta.180206@gmail.com)
