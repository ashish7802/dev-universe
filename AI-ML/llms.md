# AI / ML — LLMs (Large Language Models)

> Comprehensive collection of repositories for open source LLMs, fine-tuning, inference, RAG, agents, evaluation, and production deployment.

---

## Open Source Models

| Repository | Description | Stars |
|------------|-------------|-------|
| [meta-llama/llama](https://github.com/meta-llama/llama) | Meta's LLaMA — foundational open LLM used by most OSS models | ![Stars](https://img.shields.io/github/stars/meta-llama/llama?style=flat-square) |
| [meta-llama/llama3](https://github.com/meta-llama/llama3) | LLaMA 3 — Meta's most capable open model family | ![Stars](https://img.shields.io/github/stars/meta-llama/llama3?style=flat-square) |
| [mistralai/mistral-src](https://github.com/mistralai/mistral-src) | Mistral 7B — outperforms LLaMA 2 13B on most benchmarks | ![Stars](https://img.shields.io/github/stars/mistralai/mistral-src?style=flat-square) |
| [google/gemma](https://github.com/google-deepmind/gemma) | Google Gemma — lightweight open models from Google DeepMind | ![Stars](https://img.shields.io/github/stars/google-deepmind/gemma?style=flat-square) |
| [microsoft/phi](https://github.com/microsoft/phi-2) | Microsoft Phi — small but powerful models | ![Stars](https://img.shields.io/github/stars/microsoft/phi-2?style=flat-square) |
| [EleutherAI/gpt-neox](https://github.com/EleutherAI/gpt-neox) | Large-scale autoregressive LM training framework | ![Stars](https://img.shields.io/github/stars/EleutherAI/gpt-neox?style=flat-square) |
| [EleutherAI/gpt-j](https://github.com/kingoflolz/mesh-transformer-jax) | GPT-J 6B — open source GPT-3-style model | ![Stars](https://img.shields.io/github/stars/kingoflolz/mesh-transformer-jax?style=flat-square) |
| [THUDM/ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) | Open bilingual Chinese-English dialogue language model | ![Stars](https://img.shields.io/github/stars/THUDM/ChatGLM-6B?style=flat-square) |
| [THUDM/ChatGLM3](https://github.com/THUDM/ChatGLM3) | ChatGLM3 — third generation bilingual LLM | ![Stars](https://img.shields.io/github/stars/THUDM/ChatGLM3?style=flat-square) |
| [BlinkDL/RWKV-LM](https://github.com/BlinkDL/RWKV-LM) | RWKV — RNN with transformer-level performance, runs on CPU | ![Stars](https://img.shields.io/github/stars/BlinkDL/RWKV-LM?style=flat-square) |
| [databrickslabs/dolly](https://github.com/databrickslabs/dolly) | Dolly — Databricks open instruction-following LLM | ![Stars](https://img.shields.io/github/stars/databrickslabs/dolly?style=flat-square) |
| [tiiuae/falcon-llm](https://github.com/Alignment-Lab-AI/AutoAlign) | Falcon LLM — TII open model, top of open LLM leaderboard | ![Stars](https://img.shields.io/github/stars/tiiuae/falcon-7b?style=flat-square) |
| [openlm-research/open_llama](https://github.com/openlm-research/open_llama) | Open reproduction of LLaMA using RedPajama dataset | ![Stars](https://img.shields.io/github/stars/openlm-research/open_llama?style=flat-square) |
| [mosaicml/llm-foundry](https://github.com/mosaicml/llm-foundry) | LLM training code for MosaicML's MPT models | ![Stars](https://img.shields.io/github/stars/mosaicml/llm-foundry?style=flat-square) |
| [deepseek-ai/DeepSeek-LLM](https://github.com/deepseek-ai/DeepSeek-LLM) | DeepSeek LLM — strong open model from China | ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-LLM?style=flat-square) |
| [deepseek-ai/DeepSeek-Coder](https://github.com/deepseek-ai/DeepSeek-Coder) | DeepSeek Coder — best open code model | ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Coder?style=flat-square) |
| [Qwen/Qwen](https://github.com/QwenLM/Qwen) | Alibaba's Qwen — strong multilingual open LLM | ![Stars](https://img.shields.io/github/stars/QwenLM/Qwen?style=flat-square) |
| [01-ai/Yi](https://github.com/01-ai/Yi) | Yi models — bilingual 6B/34B open LLMs | ![Stars](https://img.shields.io/github/stars/01-ai/Yi?style=flat-square) |

---

## Inference & Local Running

| Repository | Description | Stars |
|------------|-------------|-------|
| [ollama/ollama](https://github.com/ollama/ollama) | Run LLaMA, Mistral, Gemma, Phi locally — one command | ![Stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square) |
| [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | LLM inference in C/C++ — CPU, Metal, CUDA, Vulkan | ![Stars](https://img.shields.io/github/stars/ggerganov/llama.cpp?style=flat-square) |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | PagedAttention — 24x higher throughput than HuggingFace | ![Stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square) |
| [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | Training, serving, and evaluating LLM chatbots | ![Stars](https://img.shields.io/github/stars/lm-sys/FastChat?style=flat-square) |
| [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) | Run LLMs on your laptop — cross-platform desktop app | ![Stars](https://img.shields.io/github/stars/nomic-ai/gpt4all?style=flat-square) |
| [Mozilla-Ocho/llamafile](https://github.com/Mozilla-Ocho/llamafile) | Run LLMs as a single executable file — no install needed | ![Stars](https://img.shields.io/github/stars/Mozilla-Ocho/llamafile?style=flat-square) |
| [ggerganov/whisper.cpp](https://github.com/ggerganov/whisper.cpp) | Port of OpenAI's Whisper in C++ — CPU-friendly | ![Stars](https://img.shields.io/github/stars/ggerganov/whisper.cpp?style=flat-square) |
| [mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm) | Run LLMs natively on any device — iOS, Android, browser | ![Stars](https://img.shields.io/github/stars/mlc-ai/mlc-llm?style=flat-square) |
| [LostRuins/koboldcpp](https://github.com/LostRuins/koboldcpp) | Easy-to-use llama.cpp wrapper with KoboldAI UI | ![Stars](https://img.shields.io/github/stars/LostRuins/koboldcpp?style=flat-square) |
| [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) | Gradio web UI for running LLMs locally | ![Stars](https://img.shields.io/github/stars/oobabooga/text-generation-webui?style=flat-square) |
| [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference) | HuggingFace production LLM serving toolkit | ![Stars](https://img.shields.io/github/stars/huggingface/text-generation-inference?style=flat-square) |
| [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) | Run LLMs on any cloud — lowest cost, best GPU availability | ![Stars](https://img.shields.io/github/stars/skypilot-org/skypilot?style=flat-square) |

---

## Fine-tuning

| Repository | Description | Stars |
|------------|-------------|-------|
| [huggingface/peft](https://github.com/huggingface/peft) | LoRA, QLoRA, prefix tuning, P-tuning — all in one library | ![Stars](https://img.shields.io/github/stars/huggingface/peft?style=flat-square) |
| [huggingface/trl](https://github.com/huggingface/trl) | RLHF, PPO, DPO, SFT — train LLMs with RL | ![Stars](https://img.shields.io/github/stars/huggingface/trl?style=flat-square) |
| [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) | Unified fine-tuning for 100+ LLMs — LoRA, full, QLoRA | ![Stars](https://img.shields.io/github/stars/hiyouga/LLaMA-Factory?style=flat-square) |
| [artidoro/qlora](https://github.com/artidoro/qlora) | QLoRA — fine-tune 65B model on single GPU | ![Stars](https://img.shields.io/github/stars/artidoro/qlora?style=flat-square) |
| [tloen/alpaca-lora](https://github.com/tloen/alpaca-lora) | Instruct-tune LLaMA on consumer hardware using LoRA | ![Stars](https://img.shields.io/github/stars/tloen/alpaca-lora?style=flat-square) |
| [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) | ZeRO optimization — train massive models on limited hardware | ![Stars](https://img.shields.io/github/stars/microsoft/DeepSpeed?style=flat-square) |
| [Lightning-AI/lit-gpt](https://github.com/Lightning-AI/litgpt) | Fine-tune and pretrain LLMs — Lightning clean codebase | ![Stars](https://img.shields.io/github/stars/Lightning-AI/litgpt?style=flat-square) |
| [OpenAccess-AI-Collective/axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) | Streamline fine-tuning of AI models — supports many formats | ![Stars](https://img.shields.io/github/stars/OpenAccess-AI-Collective/axolotl?style=flat-square) |
| [jondurbin/torchtune](https://github.com/pytorch/torchtune) | PyTorch native fine-tuning library for LLMs | ![Stars](https://img.shields.io/github/stars/pytorch/torchtune?style=flat-square) |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | Fine-tune LLaMA, Mistral 2x faster — 70% less memory | ![Stars](https://img.shields.io/github/stars/unslothai/unsloth?style=flat-square) |
| [huggingface/alignment-handbook](https://github.com/huggingface/alignment-handbook) | Robust recipes for alignment — SFT, DPO, RLHF | ![Stars](https://img.shields.io/github/stars/huggingface/alignment-handbook?style=flat-square) |

---

## RAG (Retrieval-Augmented Generation)

| Repository | Description | Stars |
|------------|-------------|-------|
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | Complete RAG framework — loaders, chunking, retrieval, synthesis | ![Stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square) |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | RAG chains, document loaders, retrievers, vector stores | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square) |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | AI-native open-source vector database — embeddings storage | ![Stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square) |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | High-performance vector search engine in Rust | ![Stars](https://img.shields.io/github/stars/qdrant/qdrant?style=flat-square) |
| [weaviate/weaviate](https://github.com/weaviate/weaviate) | ML-first vector database — hybrid search, GraphQL | ![Stars](https://img.shields.io/github/stars/weaviate/weaviate?style=flat-square) |
| [milvus-io/milvus](https://github.com/milvus-io/milvus) | Cloud-native vector DB for billion-scale similarity search | ![Stars](https://img.shields.io/github/stars/milvus-io/milvus?style=flat-square) |
| [pgvector/pgvector](https://github.com/pgvector/pgvector) | Vector similarity search inside PostgreSQL | ![Stars](https://img.shields.io/github/stars/pgvector/pgvector?style=flat-square) |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | Call 100+ LLM APIs using the OpenAI format — unified interface | ![Stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat-square) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | End-to-end NLP framework for RAG and QA pipelines | ![Stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square) |
| [embedchain/embedchain](https://github.com/mem0ai/mem0) | Mem0 — memory layer for LLM applications | ![Stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square) |
| [whyhow-ai/knowledge-graph-studio](https://github.com/microsoft/graphrag) | GraphRAG — knowledge graph based RAG by Microsoft | ![Stars](https://img.shields.io/github/stars/microsoft/graphrag?style=flat-square) |

---

## LLM Agents & Orchestration

| Repository | Description | Stars |
|------------|-------------|-------|
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | Build stateful multi-actor agent workflows as graphs | ![Stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square) |
| [microsoft/autogen](https://github.com/microsoft/autogen) | Multi-agent conversations — agents collaborate to solve tasks | ![Stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat-square) |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | Role-based multi-agent framework — autonomous crews | ![Stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square) |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Autonomous AI agents — goal-driven with long-term memory | ![Stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=flat-square) |
| [geekan/MetaGPT](https://github.com/geekan/MetaGPT) | Multi-agent framework — assigns roles like PM, engineer, QA | ![Stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square) |
| [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | Type-safe agent framework by Pydantic team | ![Stars](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=flat-square) |
| [agno-agi/agno](https://github.com/agno-agi/agno) | Full-stack framework for building multi-modal AI agents | ![Stars](https://img.shields.io/github/stars/agno-agi/agno?style=flat-square) |
| [openai/swarm](https://github.com/openai/swarm) | Educational multi-agent orchestration framework by OpenAI | ![Stars](https://img.shields.io/github/stars/openai/swarm?style=flat-square) |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | Make websites accessible to AI agents — browser automation | ![Stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square) |
| [microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver) | Code-first agent framework — data analytics tasks | ![Stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=flat-square) |

---

## Prompt Engineering & Management

| Repository | Description | Stars |
|------------|-------------|-------|
| [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | Comprehensive guide — zero-shot, few-shot, CoT, ReAct, RAG | ![Stars](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=flat-square) |
| [openai/openai-cookbook](https://github.com/openai/openai-cookbook) | OpenAI official examples and best practices | ![Stars](https://img.shields.io/github/stars/openai/openai-cookbook?style=flat-square) |
| [anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) | Claude API examples — RAG, tools, vision, agents | ![Stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=flat-square) |
| [brexhq/prompt-engineering](https://github.com/brexhq/prompt-engineering) | Brex's internal prompt engineering guide | ![Stars](https://img.shields.io/github/stars/brexhq/prompt-engineering?style=flat-square) |
| [microsoft/promptflow](https://github.com/microsoft/promptflow) | Build, evaluate, and deploy LLM flows — Microsoft | ![Stars](https://img.shields.io/github/stars/microsoft/promptflow?style=flat-square) |
| [hegelai/prompttools](https://github.com/hegelai/prompttools) | Open source tools for testing and experimenting with prompts | ![Stars](https://img.shields.io/github/stars/hegelai/prompttools?style=flat-square) |
| [ErikBjare/gptme](https://github.com/ErikBjare/gptme) | Personal AI assistant in your terminal — tool use, code execution | ![Stars](https://img.shields.io/github/stars/ErikBjare/gptme?style=flat-square) |

---

## LLM UI & Chat Interfaces

| Repository | Description | Stars |
|------------|-------------|-------|
| [open-webui/open-webui](https://github.com/open-webui/open-webui) | Self-hosted ChatGPT-like UI — works with Ollama and OpenAI | ![Stars](https://img.shields.io/github/stars/open-webui/open-webui?style=flat-square) |
| [lobehub/lobe-chat](https://github.com/lobehub/lobe-chat) | Open source ChatGPT alternative — plugins, vision, TTS | ![Stars](https://img.shields.io/github/stars/lobehub/lobe-chat?style=flat-square) |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | Enhanced ChatGPT clone — multi-model, self-hostable | ![Stars](https://img.shields.io/github/stars/danny-avila/LibreChat?style=flat-square) |
| [mckaywrigley/chatbot-ui](https://github.com/mckaywrigley/chatbot-ui) | Open source ChatGPT UI — simple and clean | ![Stars](https://img.shields.io/github/stars/mckaywrigley/chatbot-ui?style=flat-square) |
| [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) | Gradio web UI for LLMs — GPTQ, GGUF, ExLlama support | ![Stars](https://img.shields.io/github/stars/oobabooga/text-generation-webui?style=flat-square) |
| [Yidadaa/ChatGPT-Next-Web](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web) | Well-designed cross-platform ChatGPT UI | ![Stars](https://img.shields.io/github/stars/ChatGPTNextWeb/ChatGPT-Next-Web?style=flat-square) |
| [lencx/ChatGPT](https://github.com/lencx/ChatGPT) | ChatGPT desktop app — macOS, Windows, Linux | ![Stars](https://img.shields.io/github/stars/lencx/ChatGPT?style=flat-square) |

---

## Evaluation & Benchmarking

| Repository | Description | Stars |
|------------|-------------|-------|
| [openai/evals](https://github.com/openai/evals) | OpenAI framework for evaluating LLMs and prompts | ![Stars](https://img.shields.io/github/stars/openai/evals?style=flat-square) |
| [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | 200+ NLP benchmarks — MMLU, HellaSwag, ARC, TruthfulQA | ![Stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness?style=flat-square) |
| [google/BIG-bench](https://github.com/google/BIG-bench) | Beyond Imitation Game — 200+ challenging tasks for LLMs | ![Stars](https://img.shields.io/github/stars/google/BIG-bench?style=flat-square) |
| [allenai/OLMO](https://github.com/allenai/OLMo) | Open Language Model — fully open weights, data, and training code | ![Stars](https://img.shields.io/github/stars/allenai/OLMo?style=flat-square) |
| [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | Chatbot Arena — human preference evaluation of LLMs | ![Stars](https://img.shields.io/github/stars/lm-sys/FastChat?style=flat-square) |
| [confident-ai/deepeval](https://github.com/confident-ai/deepeval) | LLM evaluation framework — like pytest for LLMs | ![Stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=flat-square) |
| [brainlid/langchain](https://github.com/uptrain-ai/uptrain) | UpTrain — evaluate and improve LLM applications | ![Stars](https://img.shields.io/github/stars/uptrain-ai/uptrain?style=flat-square) |
| [explodinggradients/ragas](https://github.com/explodinggradients/ragas) | Evaluate RAG pipelines — faithfulness, relevance, recall | ![Stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=flat-square) |

---

## LLM Safety & Alignment

| Repository | Description | Stars |
|------------|-------------|-------|
| [anthropics/constitutional-ai](https://github.com/anthropics/hh-rlhf) | Anthropic's human feedback dataset for RLHF research | ![Stars](https://img.shields.io/github/stars/anthropics/hh-rlhf?style=flat-square) |
| [openai/safety-gym](https://github.com/openai/safety-gym) | Environments for developing safe RL algorithms | ![Stars](https://img.shields.io/github/stars/openai/safety-gym?style=flat-square) |
| [llm-attacks/llm-attacks](https://github.com/llm-attacks/llm-attacks) | Universal adversarial attacks on aligned LLMs | ![Stars](https://img.shields.io/github/stars/llm-attacks/llm-attacks?style=flat-square) |
| [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) | Add guardrails to LLM outputs — validation and correction | ![Stars](https://img.shields.io/github/stars/guardrails-ai/guardrails?style=flat-square) |
| [NVIDIA/NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Programmable guardrails for LLM-based apps — NVIDIA | ![Stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails?style=flat-square) |

---

## Quantization & Compression

| Repository | Description | Stars |
|------------|-------------|-------|
| [qwopqwop200/GPTQ-for-LLaMa](https://github.com/qwopqwop200/GPTQ-for-LLaMa) | GPTQ quantization for LLaMA — 4-bit inference | ![Stars](https://img.shields.io/github/stars/qwopqwop200/GPTQ-for-LLaMa?style=flat-square) |
| [TimDettmers/bitsandbytes](https://github.com/TimDettmers/bitsandbytes) | 8-bit and 4-bit quantization — run large models on small GPUs | ![Stars](https://img.shields.io/github/stars/TimDettmers/bitsandbytes?style=flat-square) |
| [IST-DASLab/gptq](https://github.com/IST-DASLab/gptq) | GPTQ — accurate post-training quantization for GPT models | ![Stars](https://img.shields.io/github/stars/IST-DASLab/gptq?style=flat-square) |
| [casper-hansen/AutoAWQ](https://github.com/casper-hansen/AutoAWQ) | AWQ quantization — 4-bit with minimal accuracy loss | ![Stars](https://img.shields.io/github/stars/casper-hansen/AutoAWQ?style=flat-square) |

---

## Code LLMs

| Repository | Description | Stars |
|------------|-------------|-------|
| [bigcode-project/starcoder2](https://github.com/bigcode-project/starcoder2) | StarCoder 2 — best open code model, 15B parameters | ![Stars](https://img.shields.io/github/stars/bigcode-project/starcoder2?style=flat-square) |
| [deepseek-ai/DeepSeek-Coder](https://github.com/deepseek-ai/DeepSeek-Coder) | DeepSeek Coder — top open code LLM | ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Coder?style=flat-square) |
| [Codium-ai/pr-agent](https://github.com/Codium-ai/pr-agent) | AI-powered PR reviews and code analysis | ![Stars](https://img.shields.io/github/stars/Codium-ai/pr-agent?style=flat-square) |
| [continuedev/continue](https://github.com/continuedev/continue) | Open source AI code assistant — VS Code and JetBrains | ![Stars](https://img.shields.io/github/stars/continuedev/continue?style=flat-square) |
| [cline/cline](https://github.com/cline/cline) | Autonomous coding agent in VS Code — uses any LLM | ![Stars](https://img.shields.io/github/stars/cline/cline?style=flat-square) |
| [aider-chat/aider](https://github.com/paul-gauthier/aider) | AI pair programming in terminal — edit code with LLMs | ![Stars](https://img.shields.io/github/stars/paul-gauthier/aider?style=flat-square) |
| [OpenDevin/OpenDevin](https://github.com/All-Hands-AI/OpenHands) | OpenHands — open source Devin AI software engineer | ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square) |
| [mentat-ai/mentat](https://github.com/AbanteAI/mentat) | AI coding assistant that understands your codebase | ![Stars](https://img.shields.io/github/stars/AbanteAI/mentat?style=flat-square) |

---

## Multimodal LLMs

| Repository | Description | Stars |
|------------|-------------|-------|
| [haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA) | LLaVA — large language and vision assistant | ![Stars](https://img.shields.io/github/stars/haotian-liu/LLaVA?style=flat-square) |
| [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | Supports LLaVA multimodal inference locally | ![Stars](https://img.shields.io/github/stars/ggerganov/llama.cpp?style=flat-square) |
| [microsoft/LLaVA-Med](https://github.com/microsoft/LLaVA-Med) | LLaVA for medical visual question answering | ![Stars](https://img.shields.io/github/stars/microsoft/LLaVA-Med?style=flat-square) |
| [THUDM/CogVLM](https://github.com/THUDM/CogVLM) | Visual language model — strong image understanding | ![Stars](https://img.shields.io/github/stars/THUDM/CogVLM?style=flat-square) |
| [openai/CLIP](https://github.com/openai/CLIP) | CLIP — connects text and images, zero-shot classification | ![Stars](https://img.shields.io/github/stars/openai/CLIP?style=flat-square) |
| [salesforce/BLIP](https://github.com/salesforce/BLIP) | Bootstrapping language-image pretraining for vision-language | ![Stars](https://img.shields.io/github/stars/salesforce/BLIP?style=flat-square) |

---

[← Back to Index](../README.md)
