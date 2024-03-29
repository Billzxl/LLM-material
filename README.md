# Large Language Model material

**This repository aims to keep track of the most worthwhile reading materials related to LLM. Rather than including all available materials, we focus on curating a collection of the most valuable, useful, and interesting materials.**

**We are eager to seek more collaborators, so if you would like to contribute, more than WELCOME!**

There are tons of materials on LLM. To keep from getting lost in them, we built this repository. We read every material in person to make sure they are worthy of being here. Since this takes a long time, we also include the materials that look good for future reading. If some materials you think are good aren't included, PULL A REQUEST! If you find this useful or want to follow our progress, we look forward to your ⭐!

✅ indicates that we have read a material and believe it is worth preserving here

🚩 indicates that we think a material is excellent and probably worth reading

🔥 indicates that a material is well-known in its field or popular now


---

## Contents
- [For Readers](#forreaders)
- [LLM Overview](#overview)
- [Prompt](#prompt)
  - [How to design a prompt](#How-to-design-a-prompt)
  - [Papers](#Papers)
- [RAG](#rag)
  - [Understanding RAG](#Understanding-RAG)
  - [How to use RAG](#How-to-use-RAG)
  - [Papers](#Papers)
- [Fine-tune](#finetune)
  - [Papers](#Papers)
- [Agent](#agent)
  - [Papers](#Papers)


# For Readers <a name="forreaders"></a>
## News

## Announcement

# Large Language Models Overview 🚀 <a name="overview"></a>
## Fine-tune V.S. RAG
- [Fine-Tuning or Retrieval? Comparing Knowledge Injection in LLMs](https://arxiv.org/pdf/2312.05934.pdf)
- [(Video) Openai Talk: A Survey of Techniques for Maximizing LLM Performance](https://www.youtube.com/watch?v=ahnGLM-RC1Y)  ✅🚩

  **A good talk that describes the specific steps of the LLM development process**

# Prompt 🚀<a name="prompt"></a>
## How to design a prompt
- [(in Chinese) Prompt Engineering Guide](https://www.promptingguide.ai/zh/introduction/tips)
- [(in Chinese) Microsoft Design Prompt](https://blog.aixcopilot.com/microsoft-official-prompt-tutorial-advanced-prompt-design-and-engineering)

## Papers

- [Decomposed Prompting: A Modular Approach for Solving Complex Tasks (ICLR2023)](https://arxiv.org/pdf/2210.02406.pdf)
- **Step-Back Prompt, useful for RAG** [Step-Back Prompting Enables Reasoning Via Abstraction in Large Language Models (ICLR2024高分888)](https://arxiv.org/pdf/2310.06117.pdf)
---
# RAG 🚀<a name="rag"></a>

## Understanding RAG
-  [Large Language Models and Search](https://weaviate.io/blog/llms-and-search)
-  [ACL 2023 Tutorial: Retrieval-based Language Models and Applications](https://acl2023-retrieval-lm.github.io/)

## How to use RAG
-  [LlamaIndex talk](materials/RAG/LlamaIndex_Talk.pdf)
-  [Retrieval-Augmented Generation (RAG): From Theory to LangChain Implementation](https://towardsdatascience.com/retrieval-augmented-generation-rag-from-theory-to-langchain-implementation-4e9bd5f6a4f2)
-  [A Guide on 12 Tuning Strategies for Production-Ready RAG Applications](https://towardsdatascience.com/a-guide-on-12-tuning-strategies-for-production-ready-rag-applications-7ca646833439#a5e2)

## Papers
- **A Survey** [Retrieval-Augmented Generation for Large Language Models: A Survey](https://arxiv.org/pdf/2312.10997v2.pdf) **and** [Analysis in Chinese](https://mp.weixin.qq.com/s?__biz=MzI0MjMyMTQ5Mw==&mid=2247488604&idx=1&sn=c49d7545ed66814391d65285dedbd4e7&chksm=e97f4566de08cc705439e2794fb3f4931190a003aa31e1fb4a4d5a9b66d0e6648afcfd2c1831#rd&spm_id_from=444.42.rich-text.link.click)✅🚩
- 🔥**Facebook Introduces the concept of RAG:** [Retrieval-augmented generation for knowledge-intensive nlp tasks (NIPS2020)](https://proceedings.neurips.cc/paper_files/paper/2020/file/6b493230205f780e1bc26945df7481e5-Paper.pdf)
- 🔥**HyDE:** [Precise Zero-Shot Dense Retrieval without Relevance Labels (ACL2023)](https://arxiv.org/pdf/2212.10496.pdf)
- [Benchmarking Large Language Models in Retrieval-Augmented Generation (AAAI2024)](https://arxiv.org/pdf/2309.01431.pdf)
- [REALM: Retrieval-Augmented Language Model Pre-Training (ICML2020)]()
- **may be useful:** [RA-DIT: Retrieval-Augmented Dual Instruction Tuning (ICLR2024)](https://arxiv.org/pdf/2310.01352.pdf)
- 🔥**Explode on Twitter:** [Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection(ICLR2024高分6888)](https://arxiv.org/pdf/2310.11511.pdf)
- **Interesting, may be useful:** [Lift Yourself Up: Retrieval-augmented Text Generation with Self-Memory (NIPS2023)](https://arxiv.org/pdf/2305.02437.pdf)
- **Retrieve from training data:** [Training Data is More Valuable than You Think: A Simple and Effective Method by Retrieving from Training Data (ACL2022)](https://arxiv.org/pdf/2203.08773.pdf)
- **Retrieve from recitation** [Recitation-Augmented Language Models (ICLR2023)](https://arxiv.org/pdf/2210.01296.pdf)
- [Generate rather than retrieve: Large language models are strong context generators (ICLR2023)](https://arxiv.org/pdf/2209.10063.pdf)
- [Promptagator: Few-shot Dense Retrieval From 8 Examples (ICLR2023)](https://arxiv.org/pdf/2209.11755.pdf)
- [PRCA: Fitting Black-Box Large Language Models for Retrieval Question Answering via Pluggable Reward-Driven Contextual Adapter (EMNLP2023)](https://aclanthology.org/2023.emnlp-main.326.pdf)
- [Augmentation-Adapted Retriever Improves Generalization of Language Models as Generic Plug-In (ACL2023)](https://arxiv.org/pdf/2305.17331.pdf)
- [Understanding Retrieval Augmentation for Long-Form Question Answering (ICLR2024)](https://arxiv.org/pdf/2310.12150.pdf)
- [Diversify Question Generation with Retrieval-Augmented Style Transfer (EMNLP2023)](https://aclanthology.org/2023.emnlp-main.104.pdf)
- **Rewrite query** [Query Rewriting for Retrieval-Augmented Large Language Models (EMNLP2023)](https://arxiv.org/pdf/2305.14283.pdf)
- **Retrieve prompt for 0-shot task** [UPRISE: Universal Prompt Retrieval for Improving Zero-Shot Evaluation (EMNLP2023)](https://arxiv.org/pdf/2303.08518.pdf)
- [Large Language Models Can Be Easily Distracted by Irrelevant Context (ICML2023)](https://arxiv.org/pdf/2302.00093.pdf)
- [Making Retrieval-Augmented Language Models Robust to Irrelevant Context (ICLR2024)](https://arxiv.org/pdf/2310.01558.pdf)
- [Few-shot Learning with Retrieval Augmented Language Models (JMLR2022)](https://arxiv.org/pdf/2208.03299.pdf)
- [Retrieval-Generation Synergy Augmented Large Language Models (Arxiv)](https://arxiv.org/pdf/2310.05149.pdf)
- [Enabling Large Language Models to Generate Text with Citations (Arxiv)](https://arxiv.org/pdf/2305.14627.pdf)
- [Dense X Retrieval: What Retrieval Granularity Should We Use? (Arxiv)](https://arxiv.org/pdf/2312.06648.pdf)

---
# Fine-tune 🚀<a name="finetune"></a>
  
## Papers

- 🔥**LoRA:** [LoRA: Low-Rank Adaptation of Large Language Models (ICLR2022)](https://arxiv.org/pdf/2106.09685.pdf)
- [LLaMA-Adapter- Efficient Fine-tuning of Language Models with Zero-init Attention (ICLR2024)](https://arxiv.org/pdf/2303.16199.pdf)

---
# Agent 🚀<a name="agent"></a>
  
## Papers

- **A survey:** [The Rise and Potential of Large Language Model Based Agents: A Survey (Arxiv)](https://arxiv.org/pdf/2309.07864.pdf) **A nice survey for LLM Agent** ✅🚩
- **Another survey:** [A Survey on Large Language Model based Autonomous Agents (Arxiv)](https://arxiv.org/pdf/2308.11432.pdf)
- [Cognitive Architectures for Language Agents (Arxiv)](https://arxiv.org/pdf/2309.02427.pdf) **An Architectural Paradigm for Agents** ✅
- **War Agent:** [War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars (Arxiv)](https://arxiv.org/pdf/2311.17227.pdf)
- **Game Agent:** [Human-level play in the game of Diplomacy by combining language models with strategic reasoning (Science)](https://www.science.org/doi/10.1126/science.ade9097) ✅

  **Example of agent participating in game**
- **Agent Society CAMEL:** [CAMEL: Communicative Agents for “Mind” Exploration of Large Language Model Society (NeurIPS2023)](https://ghli.org/camel.pdf)


