<div align="center">

  <!-- Dynamic Typing SVG Header -->
  <a href="https://github.com/ioseba">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1200&color=61AFEF&center=true&vCenter=true&width=650&height=50&lines=I.+Alonso;AI+Systems+%26+Software+Engineer;LLM+Routing+%26+Streaming+Engines;Bridging+Research+%26+Industrial+Scale" alt="I. Alonso Typing SVG" />
  </a>

  <p align="center">
    <strong>Bilbao, Spain 🇪🇸 &nbsp;|&nbsp; Industrial AI & Software Architecture</strong>
  </p>

  <p align="center">
    <a href="https://github.com/ioseba"><img src="https://img.shields.io/badge/Status-Shipping_Code-00E676?style=for-the-badge&logo=git&logoColor=black" alt="Status" /></a>
    <a href="https://github.com/BerriAI/litellm"><img src="https://img.shields.io/badge/LiteLLM-Core_Contributor-5C6BC0?style=for-the-badge&logo=python&logoColor=white" alt="LiteLLM Contributor" /></a>
    <a href="https://huggingface.co"><img src="https://img.shields.io/badge/Hugging_Face-🤗_Ecosystem-FFD21E?style=for-the-badge&logoColor=black" alt="Hugging Face Contributor" /></a>
    <a href="https://github.com/ioseba"><img src="https://img.shields.io/badge/Architecture-Agentic_%26_RAG-7928CA?style=for-the-badge" alt="Architecture" /></a>
  </p>

</div>

---

```yaml
# system_manifest.yml
identity: "I. Alonso"
discipline: "AI Systems Engineering & Production Deployment"
location: "Bilbao, Spain (CET / UTC+1)"
philosophy: "From research notebooks to deterministic, low-latency production runtimes."
recent_work:
  - org: "BerriAI/litellm"
    scope: "Streaming chunk builder & tool-call fragment reconstruction engine"
  - org: "huggingface/course"
    scope: "Transformers pipeline architecture & tokenizer mechanics"
```

---

### ⚡ Core Engineering & Architecture

```
  ┌───────────────────────────────────────────────────────────┐
  │                 CLIENT / AGENTIC CONSUMER                 │
  └─────────────────────────────┬─────────────────────────────┘
                                │  REST / WebSocket (Streaming)
  ┌─────────────────────────────▼─────────────────────────────┐
  │         GATEWAY & ROUTING LAYER (FastAPI / LiteLLM)       │
  │     • Tool-Call Assemblers   • Token Rate Limits          │
  │     • Fallbacks & Retries    • Real-Time Spend Tracking   │
  └─────────────────────────────┬─────────────────────────────┘
                                │
  ┌─────────────────────────────▼─────────────────────────────┐
  │                MODEL & INFERENCE RUNTIMES                 │
  │     • Transformers (HF)      • Vector Indexes (Embeddings)│
  │     • Local & Cloud Backends • Structured Output Schemas  │
  └───────────────────────────────────────────────────────────┘
```

---

### 🛠️ Technical Arsenal

<div align="center">

| Layer | Stack |
| :--- | :--- |
| **AI / ML & Modeling** | ![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Transformers](https://img.shields.io/badge/Transformers-FFA000?style=flat-square) ![LiteLLM](https://img.shields.io/badge/LiteLLM-263238?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) |
| **Backend & Services** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![REST/WebSocket](https://img.shields.io/badge/REST_%26_WebSocket-005571?style=flat-square) |
| **Infra & Tooling** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux_x86%2Farm64-FCC624?style=flat-square&logo=linux&logoColor=black) |

</div>

---

### 🧬 Open Source Track Record

* ⚡ **[BerriAI/litellm](https://github.com/BerriAI/litellm) (PR [#44439](https://github.com/BerriAI/litellm/pull/44439)):**
  Engineered multi-chunk concatenation fix for streaming tool calls in `ChunkProcessor.get_combined_tool_content`, eliminating truncated `id` and `name` tokens during multi-vendor proxy streaming. Added comprehensive regression tests in `test_streaming_chunk_builder_utils.py`.
* 🤗 **[huggingface/course](https://github.com/huggingface/course) (PR [#1325](https://github.com/huggingface/course/pull/1325)):**
  Authored official Spanish curriculum for Chapter 2 (*Detrás del pipeline*), detailing raw text preprocessing, tensor projection, and logit distribution decoding. All CI builds validated green.

---

### 📈 Telemetry & Activity

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ioseba&theme=tokyonight&hide_border=true" alt="I. Alonso GitHub Streak" height="165" />
  <img src="https://github-readme-stats.vercel.app/api?username=ioseba&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="I. Alonso GitHub Stats" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ioseba&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="140" />
</div>

---

<div align="center">
  <sub><code>return {"status": 200, "maintainer": "I. Alonso", "build": "production"}</code></sub>
</div>
