# Awesome AI Agent Leaderboards

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of benchmarks, evaluations, and testing frameworks for AI agents and frontier models. This resource tracks the capabilities of increasingly sophisticated AI systems, providing insights into progress toward artificial general intelligence (AGI).

This project is maintained by Parni and Ian. Follow Supernal Intelligence for more updates.

**Website**: supernalintelligence.com  
**Join our Discord**: Supernal Intelligence Discord

## Contents

- [Meta-Benchmarks](#meta-benchmarks)
  - [Evaluation Platforms](#evaluation-platforms)
  - [Benchmark Collections](#benchmark-collections)
  - [Community Evaluation](#community-evaluation)
  - [Tool Selection & Usage](#tool-selection--usage)
- [Agent Evaluations](#agent-evaluations)
  - [Multi-Benchmark Assessment](#multi-benchmark-assessment)
  - [General Capabilities](#general-capabilities)
  - [Safety Assessment](#safety-assessment)
  - [Cybersecurity Capabilities](#cybersecurity-capabilities)
  - [Code Generation](#code-generation)
- [AI Model Evaluations](#ai-model-evaluations)
  - [Frontier Capabilities](#frontier-capabilities)
  - [Complex Reasoning](#complex-reasoning)
- [Intelligence and Reasoning](#intelligence-and-reasoning)
  - [Knowledge Breadth](#knowledge-breadth)
  - [General Intelligence](#general-intelligence)
- [Mathematical Reasoning](#mathematical-reasoning)
  - [Elementary Math](#elementary-math)
- [Coding and Software Engineering](#coding-and-software-engineering)
  - [Code Generation](#code-generation-1)

## Meta-Benchmarks

### Evaluation Platforms

- [GAIA Leaderboard](https://gaia-benchmark.github.io/) - General AI Assistants benchmark focused on tool use, web browsing, reasoning, and multimodal tasks. Maintained by the HAL Team at Princeton.
- [Scale AI SEAL](https://scale.com/seal) - Frontier reasoning benchmark focused on honesty, safety, and complex reasoning. Maintained by Scale AI.
- [LLM-Stats.com](https://llm-stats.com/) - LLM Performance Metrics focusing on context length, latency, and cost. Independently maintained.
- [LMSYS Chatbot Arena](https://lmsys.org/chatbot_arena/) - Human preference rankings for conversational AI with an open leaderboard. Maintained by LMSYS Org.
- [MT-Bench](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge) - Multi-turn conversation benchmark with an open leaderboard. Maintained by LMSYS Org.
- [Agent Leaderboard](/) - Evaluating autonomous agent capabilities. Maintained by various organizations.
- [HELM](https://crfm.stanford.edu/helm/) - Holistic Evaluation of Language Models with an open benchmark scoring up to 92.10%. Maintained by Stanford CRFM.

### Benchmark Collections

- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) - Community-driven open evaluation of general LLMs. Maintained by Hugging Face with top models including Claude 3.5 Sonnet and Gemini.
- [Epoch AI Benchmarking Dashboard](https://epochai.org/blog/benchmarking-dashboard) - Broad progress tracking across scientific and technical reasoning domains. Maintained by Epoch AI.
- [LLM Leaderboard (Vellum AI)](https://www.vellum.ai/llm-leaderboard) - Comparison across reasoning, math, and speed capabilities of general LLMs. Maintained by Vellum AI.
- [LiveBench](https://livebench.ai/) - Reliable model evaluation with live performance updates. Maintained by academic and independent researchers.
- [AlpacaEval](https://tatsu-lab.github.io/alpaca_eval/) - Evaluating instruction-following capabilities with an open leaderboard. Maintained by Stanford CRFM.

### Community Evaluation

- [Reddit r/singularity](https://www.reddit.com/r/singularity/) - Community leaderboards with crowd-sourced evaluations. Community curated.

### Tool Selection & Usage

- [Galileo Agent Leaderboard](https://huggingface.co/spaces/galileo-ai/agent-leaderboard) - Evaluates AI models on their ability to function as agents in real-world business scenarios using Tool Selection Quality (TSQ) as the primary metric. Synthesizes benchmarks from BFCL, τ-bench, xLAM, and ToolACE covering 14 diverse scenarios.

## Agent Evaluations

### Multi-Benchmark Assessment

- [HAL (Holistic Agent Leaderboard)](https://hal.cs.princeton.edu/) - A standardized, cost-aware, third-party leaderboard for evaluating agents across various benchmarks including SWE-bench Verified, USACO, AppWorld, CORE-bench, AgentHarm, GAIA, Cybench, and tau-bench.

### General Capabilities

- [HAL GAIA Leaderboard](https://hal.cs.princeton.edu/gaia) - Princeton HAL's implementation of the GAIA benchmark for General AI Assistants. Evaluates agents on 450 questions requiring reasoning, multi-modality handling, web browsing, and tool-use proficiency across three difficulty levels.

### Safety Assessment

- [HAL AgentHarm Leaderboard](https://hal.cs.princeton.edu/agentharm) - Princeton HAL's leaderboard for evaluating AI agents on safety and harm prevention capabilities, focusing on agents' ability to refuse harmful requests while still completing legitimate tasks.

### Cybersecurity Capabilities

- [HAL Cybench Leaderboard](https://hal.cs.princeton.edu/cybench) - Princeton HAL's leaderboard for evaluating cybersecurity capabilities and risks of language models on professional-level Capture The Flag (CTF) tasks across various cybersecurity domains.

### Code Generation

- [HAL SWE-bench Verified Leaderboard](https://hal.cs.princeton.edu/swebench) - Princeton HAL's leaderboard for evaluating code generation and bug fixing capabilities of AI agents using the SWE-bench Verified benchmark, which tests agents on real-world GitHub issues.

## AI Model Evaluations

### Frontier Capabilities

- [Scale AI SEAL Leaderboards](https://scale.com/leaderboard) - Scale's Safety, Evaluations, and Alignment Lab (SEAL) maintains neutral, tamper-proof leaderboards ranking frontier LLMs using private datasets assessed by verified domain experts across multiple capabilities.
- [Scale SEAL Agentic Tool Use Leaderboard](https://scale.com/leaderboard/tool_use_enterprise) - Scale's specialized leaderboard evaluating frontier models on enterprise agentic tool use capabilities, focusing on the ability to effectively use tools in complex enterprise scenarios.

### Complex Reasoning

- [Scale SEAL EnigmaEval Leaderboard](https://scale.com/leaderboard/enigma_eval) - Scale's benchmark using puzzle hunts to test AI with complex reasoning, creative problem-solving, and cross-domain knowledge synthesis capabilities.

## Intelligence and Reasoning

### Knowledge Breadth

- [MMLU](https://github.com/hendrycks/test) - Massive Multitask Language Understanding with an open benchmark and top score of 95.30%. Maintained by NYU and OpenAI.

### General Intelligence

- [BIG-Bench](https://github.com/google/BIG-bench) - Beyond the Imitation Game Benchmark with an open benchmark and top score of 88.50%. Maintained by Google and the community.

## Mathematical Reasoning

### Elementary Math

- [GSM8K](https://github.com/openai/grade-school-math) - Grade School Math 8K with an open benchmark and top score of 97.20%. Maintained by Google Research.

## Coding and Software Engineering

### Code Generation

- [HumanEval](https://github.com/openai/human-eval) - Evaluating code generation capabilities with an open benchmark and top score of 89.80%. Maintained by OpenAI.

## Related Awesome Lists

- [Awesome General Agents Benchmark](https://github.com/supernalintelligence/Awesome-General-Agents-Benchmark-)
- [Awesome GUI Agents](https://github.com/supernalintelligence/Awesome-Gui-Agents-/blob/main/README.md)
- [Awesome General Agents Leaderboard](https://github.com/supernalintelligence/Awesome-General-Agents-Leaderboard)

## License

MIT

---

For more complete data and the latest information, please visit our website: [supernalintelligence.com](https://supernalintelligence.com)

If you see an error or want to contribute, please email [i@supernal.ai](mailto:i@supernal.ai)
