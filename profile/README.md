# xtends

### Machine Learning Extensions for Local LLMs

> **Purpose**
>
> This document is a machine-ready ingestion prompt and quick-reference catalog for the GitHub organization at [github.com/xtends](https://github.com/xtends).
> It is designed to help a person or AI system rapidly understand the repository landscape, identify architectural themes, and extract reusable patterns from the broadest collection of LLM tooling, desktop compositing, and intelligent application development resources assembled under one organization.

---

## 1. Executive Framing

The `xtends` organization is the **extension layer** of the augmented machine learning ecosystem — a deliberate, wide-net collection of 100 repositories spanning every surface where LLMs, intelligent agents, and autonomous systems touch the real world.

Where [augml](https://github.com/augml) provides the core local runtime, `xtends` provides **everything that plugs into it**: prompt engineering, code generation, desktop applications, 3D rendering, speech pipelines, blockchain analytics, browser extensions, tokenizers, agent frameworks, workflow automation, window management, and privacy tools.

The collection logic:

```
If it extends what a local LLM can do → it belongs in xtends
If it extends what a developer can build with AI → it belongs in xtends
If it extends the user's sovereignty over their computing environment → it belongs in xtends
```

This is the largest reference organization in the ecosystem — **100 repositories across 10 functional domains** — intentionally broad because the extension surface of machine learning is broad.

---

## 2. Collection by Domain

### 2A. LLM Chat Interfaces and Desktop Applications (18 repos)

The primary interaction surface. Every way a human talks to a model.

| Repository | Description | License |
|------------|-------------|---------|
| [ollama](https://github.com/xtends/ollama) | Run Llama and other LLMs locally | MIT |
| [ollama-webui](https://github.com/xtends/ollama-webui) | ChatGPT-style web UI for Ollama | MIT |
| [chat-with-gpt](https://github.com/xtends/chat-with-gpt) | Open-source ChatGPT app with voice | MIT |
| [ChatGPTDesktop](https://github.com/xtends/ChatGPTDesktop) | ChatGPT desktop application (Mac, Windows, Linux) | AGPL-3.0 |
| [ChatGPT_desktop](https://github.com/xtends/ChatGPT_desktop) | ChatGPT desktop application (alternate) | — |
| [simpleaichat](https://github.com/xtends/simpleaichat) | Python package for minimal-complexity chat app interfaces | MIT |
| [chatgpt-clone-nodejs-express-react](https://github.com/xtends/chatgpt-clone-nodejs-express-react) | ChatGPT clone with DALL-E using gpt-3.5-turbo | Apache-2.0 |
| [chat-bot-next.js-tailwind-boilerplate](https://github.com/xtends/chat-bot-next.js-tailwind-boilerplate) | Conversational bot boilerplate with internet access | — |
| [GPT-Nextjs-Tailwind-starter](https://github.com/xtends/GPT-Nextjs-Tailwind-starter) | Boilerplate starter for GPT + Next.js + Tailwind | — |
| [gptchat](https://github.com/xtends/gptchat) | Quick GPT chat interaction with salted API key | — |
| [AI-Talks](https://github.com/xtends/AI-Talks) | ChatGPT assistant via Streamlit | MIT |
| [PowerToys4OpenAI](https://github.com/xtends/PowerToys4OpenAI) | GPT chat extension for Chrome, Edge, Opera | — |
| [shell_gpt](https://github.com/xtends/shell_gpt) | Command-line productivity tool powered by GPT | MIT |
| [speakscribe](https://github.com/xtends/speakscribe) | Web app for audio transcription + chatbot via NiceGUI | CC0-1.0 |
| [ChatGPT_Custom_Instructions](https://github.com/xtends/ChatGPT_Custom_Instructions) | Custom instructions repository for ChatGPT | MIT |
| [lwe-plugin-shell](https://github.com/xtends/lwe-plugin-shell) | LLM Workflow Engine shell plugin | — |
| [gpt-ai-agent](https://github.com/xtends/gpt-ai-agent) | AI agent demo using GPT function calling | — |
| [textual](https://github.com/xtends/textual) | Lean application framework for Python — terminal and web UIs | MIT |

**Logic:** Cover every interaction modality — browser, desktop, terminal, voice, extension, mobile — so that a local or remote model can be accessed from any context.

### 2B. Autonomous Agents and Multi-Agent Frameworks (7 repos)

Systems that go beyond chat — they plan, execute, iterate, and self-correct.

| Repository | Description | License |
|------------|-------------|---------|
| [AgentGPT](https://github.com/xtends/AgentGPT) | Assemble, configure, deploy autonomous AI agents in browser | GPL-3.0 |
| [Auto-GPT-Plugins](https://github.com/xtends/Auto-GPT-Plugins) | Plugins for Auto-GPT | MIT |
| [Auto-GPT-Plugin-Template](https://github.com/xtends/Auto-GPT-Plugin-Template) | Starting point for developing Auto-GPT plugins | MIT |
| [AutoGPT_Local_LLMs](https://github.com/xtends/AutoGPT_Local_LLMs) | LM Studio AutoGPT with local LLMs | — |
| [autogpt-telegram-chatbot](https://github.com/xtends/autogpt-telegram-chatbot) | AutoGPT deployer for Telegram | — |
| [gpt-autopilot](https://github.com/xtends/gpt-autopilot) | GPT-4 powered AI agent creating full projects iteratively | MIT |
| [ChatDev](https://github.com/xtends/ChatDev) | Create software using natural language via multi-agent collaboration | Apache-2.0 |

**Logic:** Autonomous agents are the destination for augmented ML. These repos represent the full spectrum — from single-agent loops (Auto-GPT) to collaborative software teams (ChatDev).

### 2C. Prompt Engineering and LLM Optimization (6 repos)

The craft of making models do what you mean.

| Repository | Description | License |
|------------|-------------|---------|
| [Awesome-Prompt-Engineering](https://github.com/xtends/Awesome-Prompt-Engineering) | Hand-curated prompt engineering resources (GPT, PaLM, etc.) | Apache-2.0 |
| [awesome-chatgpt-prompts](https://github.com/xtends/awesome-chatgpt-prompts) | ChatGPT prompt curation for better usage | CC0-1.0 |
| [awesome-chatgpt-plugins](https://github.com/xtends/awesome-chatgpt-plugins) | Curated list of all ChatGPT plugins with documentation | CC0-1.0 |
| [awesome-chatgpt-api](https://github.com/xtends/awesome-chatgpt-api) | Curated apps using ChatGPT API with user-configurable keys | — |
| [perfect-prompt](https://github.com/xtends/perfect-prompt) | Streamlit approach to creating perfect prompts for image generation | MIT |
| [promptsource-toolkit](https://github.com/xtends/promptsource-toolkit) | Toolkit for creating, sharing, and using natural language prompts | Apache-2.0 |

**Logic:** Prompts are the programming language of LLMs. These repos collect the community's best knowledge about writing them effectively.

### 2D. LLM Infrastructure and Serving (7 repos)

Model serving, routing, tokenization, and production deployment.

| Repository | Description | License |
|------------|-------------|---------|
| [OpenLLM](https://github.com/xtends/OpenLLM) | Open platform for operating LLMs in production | Apache-2.0 |
| [litellm](https://github.com/xtends/litellm) | Python SDK and proxy to call 100+ LLM APIs in OpenAI format | — |
| [localGPT](https://github.com/xtends/localGPT) | Chat with documents locally — no data leaves device | Apache-2.0 |
| [MemGPT](https://github.com/xtends/MemGPT) | Teaching LLMs memory management for unbounded context | Apache-2.0 |
| [LLM-Blender](https://github.com/xtends/LLM-Blender) | Ensemble framework leveraging diverse strengths of multiple LLMs | Apache-2.0 |
| [tiktoken](https://github.com/xtends/tiktoken) | Fast BPE tokenizer for OpenAI models | MIT |
| [tokenizers](https://github.com/xtends/tokenizers) | Fast state-of-the-art tokenizers optimized for research and production | Apache-2.0 |

**Logic:** Running one model is augml's domain. Running many models, routing between them, managing their context windows, and tokenizing efficiently — that's xtends territory.

### 2E. Code Generation and Developer Tools (8 repos)

Using AI to write code, generate applications, and automate development.

| Repository | Description | License |
|------------|-------------|---------|
| [Codex-CLI](https://github.com/xtends/Codex-CLI) | Turn natural language into Bash/ZShell/PowerShell commands | MIT |
| [Codex-Babylon](https://github.com/xtends/Codex-Babylon) | Turn natural language into 3D objects via Codex + BabylonJS | MIT |
| [MinecraftCodex](https://github.com/xtends/MinecraftCodex) | Prompt engineering a Minecraft SimulatedPlayer API via Codex | MIT |
| [codex-python-boilerplate](https://github.com/xtends/codex-python-boilerplate) | Boilerplate for OpenAI Codex projects | — |
| [screenshot-to-code](https://github.com/xtends/screenshot-to-code) | Drop in a screenshot → clean HTML/Tailwind/React/Vue code | MIT |
| [openai-cookbook](https://github.com/xtends/openai-cookbook) | Examples and guides for using the OpenAI API | MIT |
| [openai-python](https://github.com/xtends/openai-python) | Official Python library for the OpenAI API | Apache-2.0 |
| [codelab-platform](https://github.com/xtends/codelab-platform) | Web application platform from codelab structural reference | MIT |

**Logic:** Code generation is the highest-leverage application of LLMs for developers. These repos cover the full spectrum from CLI tools to visual-to-code pipelines.

### 2F. Speech, Audio, and Multimodal (8 repos)

Voice input, transcription, text-to-speech, and audio visualization.

| Repository | Description | License |
|------------|-------------|---------|
| [DeepSpeech](https://github.com/xtends/DeepSpeech) | Open-source embedded speech-to-text engine (Raspberry Pi to GPU) | MPL-2.0 |
| [TTS](https://github.com/xtends/TTS) | Deep learning toolkit for text-to-speech — research and production | MPL-2.0 |
| [streamlit-stt-app](https://github.com/xtends/streamlit-stt-app) | Real-time web-based speech-to-text with Streamlit | MIT |
| [OpenAI_Whisper_Streamlit](https://github.com/xtends/OpenAI_Whisper_Streamlit) | Automatic speech recognition webapp powered by Whisper | MIT |
| [whisper-gpt3-streamlit](https://github.com/xtends/whisper-gpt3-streamlit) | Whisper combined with GPT-3 | — |
| [whisper-gpt3-email-generator](https://github.com/xtends/whisper-gpt3-email-generator) | Generate formal emails from voice input | — |
| [awesome-audio-visualization](https://github.com/xtends/awesome-audio-visualization) | Curated list about audio visualization | — |
| [Audai0-VisUaiL](https://github.com/xtends/Audai0-VisUaiL) | Curated list about audio visualization (alternate) | — |

**Logic:** Voice is the natural interface. These repos build the pipeline from speech → text → reasoning → response → speech, entirely locally.

### 2G. 3D, Graphics, and Generative Visual (4 repos)

Where AI meets spatial computing and visual generation.

| Repository | Description | License |
|------------|-------------|---------|
| [three.js](https://github.com/xtends/three.js) | JavaScript 3D library | MIT |
| [DALL-E-3D-Object-Generator](https://github.com/xtends/DALL-E-3D-Object-Generator) | Generate 3D models from text prompts via DALL-E | BSL-1.0 |
| [HyperHuman](https://github.com/xtends/HyperHuman) | Hyper-realistic human generation with latent structural diffusion | — |
| [OCM-Dimensions](https://github.com/xtends/OCM-Dimensions) | Bitcoin ordinals inscription tools using three.js and p5.js | — |

**Logic:** The extension of ML into spatial and visual domains — from 3D rendering to generative humans to on-chain art.

### 2H. Compiz Desktop Compositing (10 repos)

Complete desktop window manager ecosystem — the visual sovereignty layer.

| Repository | Description | License |
|------------|-------------|---------|
| [compiz](https://github.com/xtends/compiz) | Compiz core compositing window manager | — |
| [compiz-plugins-main](https://github.com/xtends/compiz-plugins-main) | Main plugin set for Compiz | GPL-2.0 |
| [compiz-plugins-extra](https://github.com/xtends/compiz-plugins-extra) | Extra plugins for Compiz | GPL-2.0 |
| [compiz-plugins-experimental](https://github.com/xtends/compiz-plugins-experimental) | Experimental plugins for Compiz | GPL-2.0 |
| [compiz-manager](https://github.com/xtends/compiz-manager) | Compiz session manager | GPL-2.0 |
| [compiz-debug-utils](https://github.com/xtends/compiz-debug-utils) | Debugging utilities for Compiz | GPL-2.0 |
| [libcompizconfig](https://github.com/xtends/libcompizconfig) | Compiz configuration library | GPL-2.0 |
| [compizconfig-python](https://github.com/xtends/compizconfig-python) | Python bindings for Compiz configuration | GPL-2.0 |
| [ccsm](https://github.com/xtends/ccsm) | CompizConfig Settings Manager | — |
| [emerald](https://github.com/xtends/emerald) | Emerald window decorator for Compiz | GPL-2.0 |
| [emerald-themes](https://github.com/xtends/emerald-themes) | Theme collection for Emerald decorator | GPL-2.0 |

**Logic:** Desktop compositing is where the user's visual environment lives. Compiz provides the window management layer for bankonOS and sovereign desktop systems. The complete stack — core, plugins, config, decorator, themes — is preserved here as a buildable unit.

### 2I. Blockchain, Web3, and Decentralized Infrastructure (7 repos)

Chain analytics, cross-chain monitoring, IPFS, Farcaster, and ordinals.

| Repository | Description | License |
|------------|-------------|---------|
| [cross-chain-monitoring](https://github.com/xtends/cross-chain-monitoring) | Cross-chain monitoring tool | MIT |
| [outlier](https://github.com/xtends/outlier) | Blockchain analytics | MIT |
| [checkthechain](https://github.com/xtends/checkthechain) | Historical data collection for Ethereum and EVM chains | Apache-2.0 |
| [ipfs-companion](https://github.com/xtends/ipfs-companion) | Browser extension for IPFS resource access | CC0-1.0 |
| [bnb-2024](https://github.com/xtends/bnb-2024) | Web3 agent with Farcaster integration | — |
| [frame-open-content](https://github.com/xtends/frame-open-content) | Farcaster frames AI dApp deployment utility | — |
| [OCM-Dimensions](https://github.com/xtends/OCM-Dimensions) | Bitcoin ordinals inscription tools | — |

**Logic:** ML + blockchain = intelligent on-chain agents. These repos provide the chain data pipelines, decentralized content access, and social protocol integration that connect AI systems to on-chain state.

### 2J. Privacy, Productivity, and Sovereign Tools (9 repos)

Tools that protect user sovereignty and extend daily productivity.

| Repository | Description | License |
|------------|-------------|---------|
| [Piped](https://github.com/xtends/Piped) | Privacy-friendly YouTube frontend | AGPL-3.0 |
| [AdBlocker-Ultimate-for-Browsers](https://github.com/xtends/AdBlocker-Ultimate-for-Browsers) | AdBlocker Ultimate for browsers | GPL-3.0 |
| [vdhcoapp](https://github.com/xtends/vdhcoapp) | Video DownloadHelper companion application | GPL-2.0 |
| [gmail-extractor](https://github.com/xtends/gmail-extractor) | Agent to read Gmail itinerary and plan trips | MIT |
| [E2B](https://github.com/xtends/E2B) | Secure sandboxed cloud environments for AI agents | Apache-2.0 |
| [gorilla](https://github.com/xtends/gorilla) | API store for LLMs | Apache-2.0 |
| [search-ui](https://github.com/xtends/search-ui) | Libraries for fast development of search experiences | Apache-2.0 |
| [pinecone-ts-client](https://github.com/xtends/pinecone-ts-client) | Official TypeScript client for Pinecone vector database | Apache-2.0 |
| [imageprocessing](https://github.com/xtends/imageprocessing) | Computer vision and image processing on web browser or node | — |

### 2K. Education and Learning (5 repos)

| Repository | Description | License |
|------------|-------------|---------|
| [javascript-algorithms](https://github.com/xtends/javascript-algorithms) | Algorithms and data structures in JavaScript with explanations | MIT |
| [python-mini-projects](https://github.com/xtends/python-mini-projects) | Collection of simple Python mini projects | MIT |
| [wtfpython](https://github.com/xtends/wtfpython) | Learning Python through surprising code snippets | WTFPL |
| [eurisko-resources](https://github.com/xtends/eurisko-resources) | Resources for Eurisko — computational discovery system | — |
| [How-to-use-Whisper-to-transcribe-a-YouTube-video-Tutorial](https://github.com/xtends/How-to-use-Whisper-to-transcribe-a-YouTube-video-Tutorial) | Whisper transcription tutorial for YouTube videos | — |

### 2L. Original Work (3 repos)

Non-forked repositories — native to xtends.

| Repository | Description |
|------------|-------------|
| [.github](https://github.com/xtends/.github) | Organization profile |
| [gptchat](https://github.com/xtends/gptchat) | Quick GPT interaction with salted API key handling |
| [faice](https://github.com/xtends/faice) | Framework for Autonomous and Intelligent Computer Expressions |

**FAICE** — Framework for Autonomous and Intelligent Computer Expressions — is the philosophical anchor of the xtends collection. It represents the thesis that computer expressions should be autonomous, intelligent, and framework-driven rather than ad-hoc.

---

## 3. What a Machine Should Notice

This organization is not a bookmark folder. It is a **complete extension surface for local-first AI systems** covering:

- **Every chat interface pattern** (web, desktop, terminal, extension, voice, bot)
- **Every agent architecture** (Auto-GPT, ChatDev, function-calling, Prolog)
- **Every prompt engineering resource** worth collecting
- **Every model serving pattern** (local, proxy, ensemble, memory-managed)
- **The complete Compiz desktop stack** (compositor + plugins + config + decorator + themes)
- **Blockchain analytics and Web3 agent tooling**
- **Speech-to-text and text-to-speech pipelines**
- **Code generation from natural language and from screenshots**
- **Privacy and sovereignty tools** (ad blocking, private video, sandboxed execution)

The unifying principle: **if it extends what a person can do with a local machine and local intelligence, it belongs here.**

---

## 4. Relationship to the Ecosystem

| Organization | Role |
|-------------|------|
| [augml](https://github.com/augml) | Core local runtime — Ollama, LangChain, privateGPT |
| [xtends](https://github.com/xtends) | **This org** — extension layer, broadest surface |
| [Professor-Codephreak](https://github.com/Professor-Codephreak) | Parent architect — bankonOS, MASTERMIND, AGLM |
| [mastermindML](https://github.com/mastermindML) | Agency controller |
| [GATERAGE](https://github.com/GATERAGE) | Retrieval Augmented Generative Engine |
| [easyAGI](https://github.com/easyAGI) | Easy Augmented Generative Intelligence |
| [Faicey](https://github.com/Faicey) | UIUX AIML modular response systems |
| [pythaiml](https://github.com/pythaiml) | AI for the knowledge economy |
| [bankonme](https://github.com/bankonme) | Sovereign banking infrastructure |

---

## 5. Numbers

| Metric | Value |
|--------|-------|
| Total repositories | 100 |
| Forked | 97 |
| Original | 3 (`.github`, `gptchat`, `faice`) |
| Domains covered | 11 |
| Licenses represented | 12 distinct |
| Compiz stack repos | 11 (complete build chain) |

---

<div align="center">

*Extension is not accumulation. It is the deliberate expansion of capability surface.*

*Every repo here answers one question: what else can a sovereign machine do?*

[github.com/xtends](https://github.com/xtends)

</div>
