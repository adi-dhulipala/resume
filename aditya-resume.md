# Aditya Dhulipala

213-807-4043 |  adi@dhulipala.xyz |  [GitHub](https://github.com/adi-dhulipala) |  [LinkedIn](https://www.linkedin.com/in/adityadhulipala) |  Cupertino, CA

---

## SUMMARY

ML & Software Engineer with deep expertise in speech and language systems on Apple platforms.  Specializes in post-training of small, on-device models — on-policy distillation (OPD), rejection-sampling fine-tuning (RSFT), and reinforcement learning.

Interest areas are in advancing private, local, on-device AI.

---

## WORK EXPERIENCE

### Apple Inc. — Sr. Machine Learning Engineer  
**Cupertino, CA**  
**Jul 2019 – Present**

#### Siri AI (2024-2026) (current)
- Built an end-to-end **on-policy distillation (OPD) post-training pipeline** for Siri's on-device planner and across model families (Gemma 4, AFM) — datagen → rejection-sampling fine-tuning (RSFT) → reverse-KL distillation of 31B-class teachers into compact ~2–3B on-device students.
- Owner of the **on-device planner model in app use tool calling** — drove model training and quality end-to-end, from training-data curation (~15M tokens) and fine-tuning through large-scale evaluation.
- Engineer #1 on Apple OS simulation framework for computer-use assistant, model fine-tuning infra. Simulator used in experiments for LoRA training, RL, OPD, State-space models pre-training etc. 
- Designed **Rejection-Sampling Fine-Tuning (RSFT)** data pipelines for the on-device planner, generating high-quality SFT targets from teacher rollouts filtered by correctness, recovering capability lost to catastrophic forgetting.
- Contributed to **reinforcement-learning experiments strengthening math/arithmetic operations** in Siri's on-device planner, after identifying that it underperformed on clock, alarm, and timer arithmetic (e.g. "set a timer for 5 minutes from now"); built RL environments with verifiable rewards to train and evaluate the fix.
- Authored the team's first **mechanistic-interpretability tooling** (logprob + activation probes) for the on-device planner, predicting and explaining tool-call failures: failing calls carry ~4× higher token entropy, with a probe predicting failure at 82% accuracy.

#### Siri Speech & NLP (2019-2024)
- Improved Siri's intent routing to ChatGPT & Personal Search using synthetic data generation; boosted accuracy from 60% to 95%.
- Led on-device migration of Siri's conversational domains with a cross-functional team of 3.
- Compressed 300MB of user data to 20MB via hash table optimization, enabling "Listen for Hey Siri" on a billion devices.
- Tuned A100 cluster training: reduced model variance from 10% to <0.02% via hyperparameter tuning.
- Contributed to Apple's MLX framework.

### Amazon — Software Development Engineer  
**Seattle, WA**  
**Dec 2016 – Jun 2019**

- Architected elastic search solutions to handle 2 years of seller data (~10M users).

### MathWorks — Software Engineer  
**Natick, MA**  
**Jan 2016 – Nov 2016**

- Modernized MATLAB SimBiology UI with web technologies.
- Developed Monte Carlo simulation APIs for PK/PD analysis.

---

## EDUCATION

**University of Southern California, Los Angeles, CA**  
*M.S. in Computer Science* — Dec 2015

**Nitte Meenakshi Institute of Technology, Bangalore, India**  
*B.E. in Computer Science* — May 2013

---

## TECHNICAL SKILLS

- **ML – Modeling & Infra:** Speech Recognition, Language Modeling, On-device ML, Post-Training (RSFT, On-Policy Distillation), Reinforcement Learning & RL Environments, Knowledge Distillation, LoRA, Model Quantization, Distributed Training, MLX, PyTorch, vLLM, ElasticSearch, DynamoDB
- **Programming:** Python, Swift, Objective-C, C++, MATLAB  

---

## PROJECTS & CONTRIBUTIONS

- **MLX Contributions:** Added Moore-Penrose inverse to `mlx.core.linalg.pinv`  
  - PRs: [mlx#875](https://github.com/ml-explore/mlx/pull/875), [mlx-examples#483](https://github.com/ml-explore/mlx-examples/pull/483)
- **Bitlinear GPT on Apple Silicon:** Created lightweight, educational GPT example using MLX
