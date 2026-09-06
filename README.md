<h1 align="center">Hi, I'm Sergio Vizcaino 👋</h1>

## About Me

I'm an ML Engineer who builds and ships production ML systems end-to-end. My core strengths are fine-tuning and deploying local and quantized models for real-world use. B.Sc. in Data Science and Engineering from Universidad Carlos III de Madrid.

## Open Source Contributions

**[huggingface/peft](https://github.com/huggingface/peft)** — Parameter-Efficient Fine-Tuning library

- [#3427](https://github.com/huggingface/peft/pull/3427) — Fixed LoRA hotswapping for grouped `Conv2d` layers: rank padding was treating a per-group dimension as the global rank, causing shape errors.
- [#3315](https://github.com/huggingface/peft/pull/3315) — Fixed the LoRA-FA optimizer to use each layer's actual scaling instead of one global value, which broke gradients when `rank_pattern`/`alpha_pattern` varied across layers.
- All merged contributions, ongoing work, and issue discussions — [all merged PRs](https://github.com/huggingface/peft/pulls?q=is%3Apr+author%3AeSVeeF+is%3Amerged) · [all issues](https://github.com/huggingface/peft/issues?q=is%3Aissue+author%3AeSVeeF)

**[huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers)** — embeddings & semantic search library

- Merged contributions, ongoing work, and issue reports — [all merged PRs](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr+author%3AeSVeeF+is%3Amerged) · [all issues](https://github.com/huggingface/sentence-transformers/issues?q=is%3Aissue+author%3AeSVeeF)

## Tech Stack

**Core & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=flat&logoColor=black)
![llama.cpp](https://img.shields.io/badge/🦙%20llama.cpp-1a1a1a?style=flat&logoColor=white)

**Infrastructure & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
