# Awesome AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/brunocroh/awesome-ai-apis/)

A collection of awesome AI projects that you can use on your products as API, framework, plataform or self hosted.

## Contents

- [Image](#image)
- [Audio](#audio)
- [Video](#video)
- [Run models locally](#run-models-locally)
- [Model Language (Text/Chat)](#model-language)
- [Code Completion](#code-completion)
- [Embeddings](#embeddings)
- [Platforms](#platforms)
- [GPU Hosts](#gpu-hosts)
- [Model Chaining](#model-chaining)

---

## Image

### API

- [OpenAI Image](https://platform.openai.com/docs/api-reference/images) - Given a prompt and/or an input image, the model will generate a new image.
- [Leonardo.Ai](https://leonardo.ai/api/) - Create production-quality visual assets for your projects with unprecedented quality, speed, and style-consistency.
- [Stability Ai](https://platform.stability.ai/)

### Models

- [Stable diffusion](https://github.com/Stability-AI/stablediffusion)
- [SDXL Lightning](https://huggingface.co/ByteDance/SDXL-Lightning)

## Model Language

### API

- [Google PalM 2 for text](https://replicate.com/meta/llama-2-13b-chat) - foundation models are optimized for a variety of natural language tasks such as sentiment analysis, entity extraction, and content creation. The types of content that the PaLM 2 for Text models can create include document summaries, answers to questions, and labels that classify content
- [Google PaLM 2 for Chat](https://cloud.google.com/vertex-ai/docs/generative-ai/model-reference/text-chat) - foundation model is a large language model (LLM) that excels at language understanding, language generation, and conversations. This chat model is fine-tuned to conduct natural multi-turn conversations, and is ideal for text tasks about code that require back-and-forth interactions.
- [Perplexity](https://docs.perplexity.ai/reference/post_chat_completions) - Here, you'll find documentation and examples that will help you get started with blazingly fast LLM inference.
- [OpenAI Chat](https://platform.openai.com/docs/api-reference/chat) - Given a list of messages comprising a conversation, the model will return a response.

### Models

- [Gemma 7b](https://huggingface.co/google/gemma-7b)
- [Mixtral 8x7b](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1)
- [Llamma 7b chat-hf](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)

## Audio

### API

- [ElevenLabs](https://elevenlabs.io/api) - Elevate your projects with the fastest & most powerful text to speech & voice API. Quickly generate AI voices in multiple languages for your chatbots, agents, LLMs, websites, apps and more.
- [DupDub](https://www.dupdub.com/api) - Text-to-speech open API.
- [Open Ai - text-to-speech](https://platform.openai.com/docs/guides/text-to-speech)
- [Open Ai - speech-to-text](https://platform.openai.com/docs/guides/speech-to-text)

### Models

- [Bark with voice clone](https://github.com/serp-ai/bark-with-voice-clone) - About 🔊 Text-prompted Generative Audio Model - With the ability to clone voices
- [Piper](https://github.com/rhasspy/piper) - A fast, local neural text to speech system
- [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) - Port of OpenAI's Whisper model in C/C++

## Run models locally

- [GPT4All](https://gpt4all.io/index.html) - A free-to-use, locally running, privacy-aware chatbot. No GPU or internet required.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Inference of Meta's LLaMA model (and others) in pure C/C++
- [LM Studio](https://lmstudio.ai/) - Run any LLaMa Falcon MPT Gemma Replit GPT-Neo-X gguf models from Hugging Face
- [Ollama](https://ollama.com/) - Run Llama 2, Code Llama, and other models. Customize and create your own.

## Platforms

_Platforms that provide more that just one API_

### Community

- [Hugging Face](https://huggingface.co/) - The platform where the machine learning community collaborates on models, datasets, and applications.

### Models as a service

- [fal.ai](https://fal.ai/) - Fastest way to serve open source ML models to millions
- [infermatic](https://infermatic.ai/)
- [Replicate](https://replicate.com/) - Run AI with an API. Run and fine-tune open-source models. Deploy custom models at scale. All with one line of code.
- [stability.ai](https://stability.ai/) - Open models in every modality, for everyone, everywhere.

## GPU Hosts

- [Banana](https://www.banana.dev/#pricing) - GPUs for Scale. Inference hosting for AI teams who ship fast and scale faster.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) - Run machine learning models, powered by serverless GPUs, on Cloudflare's global network.
- [Crusoe](https://www.crusoe.ai/cloud/pricing/index.html) - GPU Compute.
- [LambdaLabs](https://lambdalabs.com/) - The GPU Cloud for AI. On-demand & reserved cloud GPUs for AI training & inference.
- [RunPod](https://www.runpod.io) - The Cloud Built for AI. Globally distributed GPU cloud built for production.

## LLM Chaining

- [LlamaIndex](https://www.llamaindex.ai/) - Turn your enterprise data into production-ready LLM applications
- [LangChain](https://www.langchain.com/) - Applications that can reason. Powered by LangChain.
- [crew.ai](crewai.io) - Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks.
