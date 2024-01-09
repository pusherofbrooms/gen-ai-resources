# Generative AI!

## What is Generative AI?
ChatGPT can answer that question. One might have good luck asking ChatGPT the following questions to understand the basics:
- What is generative AI?
- What are Large Language Models?
- Summarize the "Attention is all you need" paper.

## Learning resources
- https://www.youtube.com/@code4AI/videos Technical deep dives into various topics
- https://www.youtube.com/@samwitteveenai/videos Mostly Langchain but other LLM topics as well
- https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ Neural networks: Zero to Hero
- https://www.youtube.com/watch?v=kCc8FmEb1nY build gpt from scratch.

## Frameworks

### AI Agents / AGI
- AutoGPT https://github.com/Significant-Gravitas/AutoGPT
- autogen https://github.com/microsoft/autogen
- CrewAI https://github.com/joaomdmoura/crewAI (newer competitor to AutoGen)
- ChatDEV https://github.com/OpenBMB/ChatDev
- Aider https://github.com/paul-gauthier/aider (coding assistant)
- Add long memory to your GPT https://github.com/cpacker/MemGPT

### Development frameworks
- Langchain python llm framework https://python.langchain.com/
- Microsoft Guidance llm framework https://github.com/microsoft/guidance
- C++ LLM tools: https://github.com/ggerganov/llama.cpp https://github.com/ggerganov/ggml
- C++ speech to text: https://github.com/ggerganov/whisper.cpp
- API use by LLM's: https://github.com/ShishirPatil/gorilla

### Run models locally with a UI
- exllamav2, efficient inference of quantized models https://github.com/turboderp/exllamav2
- Oobabooga LLM UI https://github.com/oobabooga/text-generation-webui
- GPT4All LLM UI https://github.com/nomic-ai/gpt4all This is the easiest way to run LLM's locally with a nice UI.
- H2OGPT https://github.com/h2oai/h2ogpt Query documents.

### ML Ops
- MLFlow https://mlflow.org/
- git-theta https://github.com/r-three/git-theta
- Data Version Control https://dvc.org/
- HuggingFace https://huggingface.co/

## Interesting AI Research

### Seminal papers
- Attention is all you need https://arxiv.org/pdf/1706.03762.pdf
- Generative Agents: https://arxiv.org/pdf/2304.03442.pdf (planning, reflecting, acting)

### Improving performance of existing models
- Low Rank Adaptation fine tuning https://arxiv.org/pdf/2106.09685.pdf
- Classifier Free Guidance https://arxiv.org/pdf/2306.17806.pdf
- Chain of Thought https://arxiv.org/pdf/2201.11903.pdf
- Chain of Thought with Self-Consistency https://arxiv.org/pdf/2203.11171.pdf
- Tree of Thought https://arxiv.org/pdf/2305.10601.pdf
- Mixture of Experts meets instruction tuning https://arxiv.org/pdf/2305.14705.pdf
- The Poison of Alignment https://arxiv.org/pdf/2308.13449.pdf
- Original Speculative Decoding paper (with updates) https://arxiv.org/pdf/2211.17192.pdf
- Staged Specilative Decoding https://arxiv.org/pdf/2308.04623.pdf
- Chain of Verificaion Reduces Hallucination https://arxiv.org/pdf/2309.11495.pdf
- Nasa's Bio-inspired design and research assistant prompt https://github.com/nasa-petal/discord_bot#bidara--bio-inspired-design-and-research-assistant
- Reddit post on sampling settings (temperature, top-k, top-p, min-p, etc.) https://www.reddit.com/r/LocalLLaMA/comments/17vonjo/your_settings_are_probably_hurting_your_model_why/

### Improving context length
- ALiBI https://arxiv.org/pdf/2108.12409.pdf
- SuperHOT https://kaiokendev.github.io/til#extending-context-to-8k
- NTK ROPE https://www.reddit.com/r/LocalLLaMA/comments/14lz7j5/ntkaware_scaled_rope_allows_llama_models_to_have/
- Dynamic NTK ROPE https://www.reddit.com/r/LocalLLaMA/comments/14mrgpr/dynamically_scaled_rope_further_increases/
- LONGNET: Scaling Transformers to 1,000,000,000 Tokens https://arxiv.org/pdf/2307.02486.pdf (This isn't a magic bullet).
- LM-Infinite: sliding context windows with additions: https://arxiv.org/pdf/2308.16137 

### Running large models on small hardware
- gptq https://arxiv.org/pdf/2210.17323.pdf
- Activation Aware Quantization https://arxiv.org/pdf/2306.00978.pdf
- ggml (run inference on CPU) https://github.com/ggerganov/ggml

### Improving the quality of small models
- Less is More for Alignment https://arxiv.org/pdf/2305.11206v1.pdf
- Textbooks are all you need https://arxiv.org/pdf/2306.11644.pdf
- TinyStories https://arxiv.org/pdf/2305.07759.pdf
- Specialization on health related data https://arxiv.org/pdf/2305.07804.pdf
- Direct Preference Optimization https://arxiv.org/pdf/2305.18290
- Teaching Arithmetic to Small Transformers https://arxiv.org/pdf/2307.03381.pdf
- Orca: Progressive Learning from Complex Explanation Traces of GPT-4 https://arxiv.org/pdf/2306.02707.pdf
- Orca2: Teaching Small Language Models How to Reason https://arxiv.org/pdf/2311.11045.pdf
- LLM AUGMENTED LLMS: EXPANDING CAPABILITIES THROUGH COMPOSITION https://arxiv.org/pdf/2401.02412.pdf