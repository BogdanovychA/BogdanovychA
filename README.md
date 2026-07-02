# Andrii BOGDANOVYCH
- **Location:** Kyiv, Ukraine 🇺🇦
- **Projects Portfolio:** https://apps.bogdanovych.org/en/

---

## Selected Projects

### LLM Wiki

*An agent-driven persistent personal knowledge base built on the "LLM Wiki" pattern, enabling automated information ingestion, cross-linking, and consistency auditing.*

- **Designed and implemented** an automated personal wiki system utilizing **LLM Agents**, following the concept proposed by Andrej Karpathy and adapted for Ukrainian language processing.
- **Developed custom agent workflows and skills** (`ingest`, `query`, `linter`) for autonomous repository updates, cascade updates, and query result archiving.
- **Built a Python-based static analysis engine** (`lint.py`) for automated repository maintenance, checking markdown link integrity, index consistency, identifying orphaned pages, and auto-correcting broken links.
- **Established a structured, versioned architecture** separating raw source archives (`raw/`), agent-curated knowledge categories (`wiki/concepts/`, `wiki/entities/`), query archives, and automated logs.

**GitHub:** https://github.com/BogdanovychA/llm-wiki  

---

### Crimea is Ukraine RAG

*Minimalist RAG (Retrieval-Augmented Generation) assistant powered by Chainlit and LangChain, enabling rapid context retrieval and conversational Q&A regarding the occupation of Crimea.*

- **Architected and developed** a retrieval-augmented generation (RAG) assistant using **Python 3.12**, **Chainlit**, and **LangChain** to retrieve and answer questions from historical documentation.
- **Designed a multi-step conversational pipeline** with query rephrasing and history preservation to ensure contextually accurate responses.
- **Engineered data ingestion and vector indexing** using **Chroma DB**, **Ollama** embeddings (`mxbai-embed-large`), and custom Markdown parsing scripts for semantic document chunking.
- **Integrated multi-model LLM support** (Anthropic, Google Gemini, OpenAI, Ollama) and application configuration powered by **Pydantic v2** and **Pydantic Settings**.
- **Implemented localized multi-language UI support** (Ukrainian/English) by integrating self-developed **Fluent Manager** PyPI package.
- **Streamlined deployment & execution** using **Docker**, **Docker Compose**, and **uv** package manager for containerized orchestration.

**GitHub:** https://github.com/BogdanovychA/crimea-rag  
**Web:** https://chat.crimea-is-ukraine.org  

---

### Slovohr.AI

*Interactive Flet-based chat interface featuring configurable historical and fictional Ukrainian characters powered by Lapathoniia LLM provider.*

- **Architected and developed** a cross-platform (Web & Desktop) conversational application using **Python 3.12** and **Flet** (Flutter-based framework).
- **Engineered dynamic character customization** allowing rapid onboarding of new personas (such as Taras Shevchenko, Lesya Ukrainka, and Carpathian Hutsul) via YAML-based system prompt configurations.
- **Integrated asynchronous LLM communication** utilizing the `openai` client (AsyncOpenAI) optimized for the **Lapathoniia** API, featuring user-controlled model parameters (temperature, max tokens).
- **Implemented reliable state and configuration management** powered by **Pydantic v2** and **Pydantic Settings**.
- **Streamlined deployment & development workflow** using **Docker** and **uv** for fast package synchronization and reproducible execution environments.

**GitHub:** https://github.com/BogdanovychA/slovohr-ai  
**Web:** https://slovohr-ai.bogdanovych.org/  
**Google Play:** https://play.google.com/store/apps/details?id=org.bogdanovych.slovohrai

---

### H-Line

*Open-source hotline automation system for government sector digitalization.*

- **Architected and developed** a cross-platform application using **Python 3.14** and **Flet**, strictly adhering to **SOLID** principles and modular design for long-term maintainability.
- **Automated citizen appeal processes** for the State Energy Supervision of Ukraine, implementing a **scalable document generation engine** (DOCX, MD, HTML) using the **Registry Pattern** and **Jinja2** templates.
- **Engineered a robust communications layer** with secure **SMTP (SSL/TLS)** delivery and enterprise-grade data validation/configuration management using **Pydantic v2**.
- **Streamlined deployment and development workflows** using **Docker** and **uv**, ensuring consistent execution across Desktop, Web, and server-side environments.
- **Standardized for Open Source & Research**: Orchestrated the public release under **EUPL-1.2**, ensuring full metadata compliance with **PEP 639** and establishing research citability via **DOI**.

**GitHub:** https://github.com/BogdanovychA/h-line

---

### Flet Storage (PyPI Library)

[![PyPI Downloads](https://static.pepy.tech/personalized-badge/flet-storage?period=total&units=INTERNATIONAL_SYSTEM&left_color=GREY&right_color=BLUE&left_text=downloads)](https://pepy.tech/projects/flet-storage)

*Asynchronous data persistence library for Flet applications.*

- Designed and developed a reusable storage solution with automatic JSON serialization for complex data types
- Implemented data isolation via namespacing, enabling safe multi-module usage
- Published and actively maintained as an open-source package on PyPI

**GitHub:** https://github.com/BogdanovychA/flet-storage  
**PyPI:** https://pypi.org/project/flet-storage/  
**AI Skill:** https://skills.sh/bogdanovycha/flet-storage/flet-storage

---

### Fluent Manager (PyPI Library)

[![PyPI Downloads](https://static.pepy.tech/personalized-badge/fluent-manager?period=total&units=INTERNATIONAL_SYSTEM&left_color=GREY&right_color=BLUE&left_text=downloads)](https://pepy.tech/projects/fluent-manager)

*Lightweight Project Fluent localisation manager with automatic locale fallback.*

- Designed and developed a streamlined localization solution featuring automatic discovery of `.ftl` resource files from the filesystem
- Implemented a robust fallback chain (preferred locales → default locale → key itself) to ensure reliable string rendering across multiple languages
- Published and actively maintained as an open-source package on PyPI

**GitHub:** https://github.com/BogdanovychA/fluent-manager  
**PyPI:** https://pypi.org/project/fluent-manager/  
**AI Skill:** https://skills.sh/bogdanovycha/fluent-manager/fluent-manager  

---

### Mr. Transcript (PyPI Library)

[![PyPI Downloads](https://static.pepy.tech/personalized-badge/mr-transcript?period=total&units=INTERNATIONAL_SYSTEM&left_color=GREY&right_color=BLUE&left_text=downloads)](https://pepy.tech/projects/mr-transcript)

*Lightweight Python wrapper for reliable retrieval of YouTube transcripts with automatic URL parsing and subtitle fallback.*

- Designed and developed an open-source Python library that simplifies transcript extraction from YouTube videos across multiple URL formats, including `youtube.com`, `youtu.be`, `shorts`, and `embed`
- Implemented a resilient transcript lookup flow that prioritizes manually created subtitles and automatically falls back to YouTube-generated transcripts when needed
- Added developer-friendly features such as language discovery, optional timecoded output, and type hints to improve integration into automation, research, and content-processing workflows

**GitHub:** https://github.com/BogdanovychA/mr-transcript  
**PyPI:** https://pypi.org/project/mr-transcript/  
**AI Skill:** https://skills.sh/bogdanovycha/mr-transcript/mr-transcript

---

### Measurement API (PyPI Library)

[![PyPI Downloads](https://static.pepy.tech/personalized-badge/measurement-api?period=total&units=INTERNATIONAL_SYSTEM&left_color=GREY&right_color=BLUE&left_text=downloads)](https://pepy.tech/projects/measurement-api)

*Lightweight asynchronous Python client for the Google Analytics 4 (GA4) Measurement Protocol.*

- Designed and developed an asynchronous client using `httpx` to send telemetry and events to Google Analytics 4.
- Implemented connection pooling with async context managers and support for custom `httpx.AsyncClient` injection to optimize network overhead and reuse TCP connections.
- Integrated a debug/validation mode using GA4's validation server (`/debug/mp/collect`) to verify event payload structures without logging dummy production events.
- Structured support for complex parameters, including nested e-commerce tracking objects (`items`), lists, dictionaries, and primitives.

**GitHub:** https://github.com/BogdanovychA/measurement-api  
**PyPI:** https://pypi.org/project/measurement-api/  
**AI Skill:** https://skills.sh/bogdanovycha/measurement-api/measurement-api

---

### Nexus Shell — AI Agent Bot
*Telegram-based interface for interacting with multiple LLM providers.*

- Designed secure API key storage system using AES encryption
- Enabled safe multi-user interaction with Gemini, ChatGPT, and Claude
- Implemented multilingual support

**GitHub:** https://github.com/BogdanovychA/nexus-shell  
**Bot:** https://t.me/NexusShellBot

---

### CodeUA (Ukrainian Code)
*Social application to honor the memory of fallen heroes.*

- Developed cross-platform application (Web, Android) using Flet
- Implemented multilingual support
- Delivered a user-facing product with real-world purpose

**GitHub:** https://github.com/BogdanovychA/CodeUA  
**Web:** https://codeua.foundation101.org/  
**Google Play:** https://play.google.com/store/apps/details?id=org.foundation101.codeua

---

### MiniGames
*Collection of casual games for mobile and web platforms.*

- Developed cross-platform applications using Flet
- Built and deployed web and Android versions
- Structured multi-project architecture for scalability

**GitHub:** https://github.com/BogdanovychA/bmg  
**Web:** https://minigames.bogdanovych.org/  
**Google Play:** https://play.google.com/store/apps/details?id=org.foundation101.minigames

---

### Karatel Game
*RPG game based on D&D 5e mechanics with custom Ukrainian content.*

- Developed backend logic for combat system, progression, and dice mechanics
- Integrated LLM APIs for dynamic interactions
- Built web-based interface using Streamlit and FastAPI

**GitHub:** https://github.com/BogdanovychA/karatel-game  
**Web:** https://karatel.ua/
