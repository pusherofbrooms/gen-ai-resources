# Generative AI!

## What is Generative AI?
ChatGPT can answer that question. One might have good luck asking ChatGPT the following questions to understand the basics:
- What is generative AI?
- What are Large Language Models?
- Summarize the "Attention is all you need" paper.

## Learning resources
- https://www.youtube.com/@AemonAlgiz/videos Technically deep explanations of llm topics.
- https://www.youtube.com/@code4AI/videos Technical deep dives into various topics
- https://www.youtube.com/watch?v=kCc8FmEb1nY build gpt from scratch.

## Frameworks

### Development frameworks
- Langchain python llm framework https://python.langchain.com/
- Microsoft Guidance llm framework https://github.com/microsoft/guidance
- C++ LLM tools: https://github.com/ggerganov/llama.cpp https://github.com/ggerganov/ggml
- C++ speech to text: https://github.com/ggerganov/whisper.cpp
- exllama, efficient inference of quantized models https://github.com/turboderp/exllama
- Oobabooga LLM UI https://github.com/oobabooga/text-generation-webui
- GPT4All LLM UI https://github.com/nomic-ai/gpt4all

## Interesting AI Research

### Seminal papers
- Attention is all you need https://arxiv.org/pdf/1706.03762.pdf

### Improving performance of existing models
- Low Rank Adaptation fine tuning https://arxiv.org/pdf/2106.09685.pdf
- Classifier Free Guidance https://arxiv.org/pdf/2306.17806.pdf
- Chain of Thought https://arxiv.org/pdf/2201.11903.pdf
- Chain of Thought with Self-Consistency https://arxiv.org/pdf/2203.11171.pdf
- Tree of Thought https://arxiv.org/pdf/2305.10601.pdf

### Improving context length
- ALiBI https://arxiv.org/pdf/2108.12409.pdf
- SuperHOT https://kaiokendev.github.io/til#extending-context-to-8k
- NTK ROPE https://www.reddit.com/r/LocalLLaMA/comments/14lz7j5/ntkaware_scaled_rope_allows_llama_models_to_have/
- Dynamic NTK ROPE https://www.reddit.com/r/LocalLLaMA/comments/14mrgpr/dynamically_scaled_rope_further_increases/
- LONGNET: Scaling Transformers to 1,000,000,000 Tokens https://arxiv.org/pdf/2307.02486.pdf (This isn't a magic bullet).

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