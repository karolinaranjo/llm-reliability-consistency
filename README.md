# LLM Reliability & Consistency 
Foundational Papers

![Reliability](https://img.shields.io/badge/-Reliability-orange)
![Consistency](https://img.shields.io/badge/-Consistency-blue)
![Model](https://img.shields.io/badge/Model-LLMs-green)
![Data](https://img.shields.io/badge/Data-Benchmarks-purple)
![Type](https://img.shields.io/badge/Type-Literature%20Review-lightblue)

## Reliability Papers

| Paper | Tags | Venue/Source | Year | Code | Description |
|---|---|---|---|---|---|
| [Red teaming ChatGPT via Jailbreaking: Bias, Robustness, Reliability and Toxicity](https://arxiv.org/pdf/2301.12867) | `bias` `robustness` `reliability` `toxicity` | arXiv | 2023 | N/A | A qualitative approach for red-teaming ethical risks of ChatGPT. |
| [TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/pdf/2401.05561) | `truthfulness` `safety` `fairness` `robustness` `privacy` `machine ethics` | ICML | 2024 | [Official](https://github.com/HowieHwong/TrustLLM) \| [HuggingFace](https://huggingface.co/papers/2401.05561) | TrustLLM is a comprehensive framework for studying the trustworthiness of LLMs. |
| [LLM Targeted Underperformance Disproportionately Impacts Vulnerable Users](https://arxiv.org/pdf/2406.17737) | `bias` `alignment` `robustness` | NeurIPS | 2024 | [Poster](https://neurips.cc/media/PosterPDFs/NeurIPS%202024/106298.png?t=1734753887.2175903) | LLM performance degrades based on user traits: education levels, English proficiency, and country of origin. |
| [When Large Language Models contradict humans? Large Language Models' Sycophantic Behaviour](https://arxiv.org/pdf/2311.09410) | `robustness` | arXiv | 2025 | N/A | This paper investigates sycophancy: the tendency for LLMs to generate responses that align with a user's viewpoint, even when that viewpoint is factually incorrect. T |

## Consistency Papers

| Paper | Tags | Venue/Source | Year | Code | Description |
|---|---|---|---|---|---|
| [Measuring and Improving Consistency in Pretrained Language Models](https://aclanthology.org/2021.tacl-1.60.pdf) | `factual-knowledge` `robustness` `consistency` | TACL | 2021 | N/A | Pretrained Language Models are factually inconsistent, providing different answers to paraphrased questions. This paper proposes a method to enhance their knowledge's robustness. |
| [Locating and Editing Factual Associations in GPT](https://proceedings.neurips.cc/paper_files/paper/2022/file/6f1d43d5a82a37e89b0665b33bf3a182-Paper-Conference.pdf) | `model-editing` `knowledge-localization` | NeurIPS | 2022 | [Official](https://github.com/kmeng01/rome) \| [Datasets](https://rome.baulab.info/data/) | Factual knowledge in transformers is stored in localized, mid-layer feed-forward modules. This paper introduces a new method called `ROME` to surgically update these facts directly within the model. |
| [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/pdf/2203.11171) | `chain-of-thought` `reasoning` `ensembling` | ICLR | 2023 | [Slides](https://iclr.cc/media/iclr-2023/Slides/11718.pdf) | This paper introduces self-consistency, a decoding strategy that boosts chain-of-thought performance by sampling multiple reasoning paths and choosing the most consistent final answer. |
| [Large Language Models Are Human-Level Prompt Engineers](https://arxiv.org/pdf/2211.01910) | `prompt-engineering` `instruction-generation` | arXiv | 2023 | [Official](https://github.com/keirp/automatic_prompt_engineer) | Automatic Prompt Engineer (APE), a method that successfully uses a large language model to automatically generate and select optimal instructions that are often better than human-crafted prompts. |
| [Evaluating the Moral Beliefs Encoded in LLMs](https://proceedings.neurips.cc/paper_files/paper/2023/file/a2cf225ba392627529efef14dc857e22-Paper-Conference.pdf) | `alignment` `model-probing` | NeurIPS | 2023 | [Official](https://github.com/ninodimontalcino/moralchoice) | A survey-based statistical method to probe the moral beliefs of LLMs, revealing that while models handle clear-cut cases well, they are often uncertain or inconsistent in ambiguous scenarios. |
| [Quantifying Language Models' Sensitivity to Spurious Features in Prompt Design or: How I learned to start worrying about prompt formatting](https://arxiv.org/pdf/2310.11324) | `prompt-engineering` `sensitivity` `robustness` | ICML | 2024 | N/A | Minor prompt formatting changes cause drastic and unpredictable performance swings in large language models (LLMs), undermining the reliability of comparing models using a single, fixed format. |




---
**Curated by:** [Dane Williamson](https://github.com/dwil2444) & [Karolina Naranjo](https://github.com/karolinaranjo)

**Lab:** [UVA Information and Language Processing Lab](https://github.com/UVa-NLP)












