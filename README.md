# Awesome-RL-based-LLM-Reasoning
[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/bruno686/Awesome-RL-based-LLM-Reasoning/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

We have witnessed the powerful capabilities of pure RL-based LLM Reasoning. In this repository, we will add  newest papers, slides, and other interesting materials that enhance LLM reasoning with reinforcement learning, helping everyone learn quickly! \
Starring this repository is like being at the forefront of RL-based LLM reasoning. \
在风口浪尖 (In the teeth of the storm) 


## Papers

### Policy Optimization
* [2501] [Deepseek-r1: Incentivizing reasoning capability in llms via reinforcement learning](https://arxiv.org/pdf/2501.12948?) (Deepseek)
* [2501] [Kimi k1.5: Scaling Reinforcement Learning with LLMs](https://arxiv.org/pdf/2501.12599?) (Kimi)

### Process-based Reward Models
* [2502] [QLASS: Boosting Language Agent Inference via Q-Guided Stepwise Search](https://arxiv.org/pdf/2502.02584) (UCLA-Yizhou Sun)
* [2312] [Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations](https://arxiv.org/abs/2312.08935) (PKU & Deepseek)
* [2305] [Let's verify step by step](https://arxiv.org/pdf/2305.20050) (OpenAI)
* [2211] [Solving math word problems with process-and outcome-based feedback](https://arxiv.org/pdf/2211.14275) (DeepMind)

### Reinforcement learning
* [2502] [STP: Self-play LLM Theorem Provers with Iterative Conjecturing and Proving](https://arxiv.org/pdf/2502.00212) (the scarcity of correct proofs sparse rewards will make performance quickly plateaus. To overcome this, we draw inspiration from mathematicians, who continuously develop new results, partly by proposing novel conjectures or exercises (which are often variants of known
results) and attempting to solve them.) (Stanford-Tengyu Ma)
* [2409] [Training Language Models to Self-Correct via Reinforcement Learning](https://arxiv.org/abs/2409.12917) (DeepMind)


### Search algorithms (Monte Carlo Tree Search or Beam Search)
* [2310] [Solving olympiad geometry without human demonstrations](https://www.nature.com/articles/s41586-023-06747-5.pdf) (DeepMind)
* [2408] [Deepseek-prover-v1. 5: Harnessing proof assistant feedback for reinforcement learning and monte-carlo tree search](https://arxiv.org/abs/2408.08152) (DeepSeek)


### Other Newest Interesting Papers about LLM Reasoning
* [2502] [LIMO: Less is More for Reasoning](https://arxiv.org/pdf/2502.03387?) (LIMO offers a more principled and direct path through explicit trajectory design obtaining complex reasoning ability) (SJTU)
* [2502] [Confidence Improves Self-Consistency in LLMs](https://arxiv.org/pdf/2502.06233) (the quality of LLM outputs) (Google Reasearch)
* [2502] [LLMs Can Easily Learn to Reason from Demonstrations
Structure, not content, is what matters!](https://arxiv.org/pdf/2502.07374) (UC Berkeley)
* [2502] [BOLT: Bootstrap Long Chain-of-Thought in Language Models without
Distillation](https://arxiv.org/pdf/2502.03860) (Salesforce AI Research)
* [2502] [LLMs Can Teach Themselves to Better Predict the Future](https://arxiv.org/pdf/2502.05253) (self-play generate data) (LSE) 

<!-- * []()
* []()
* []()
* []()  -->

### 

## Slides

* **[LLM Reasoning: Key Ideas and Limitations](https://llm-class.github.io/slides/Denny_Zhou.pdf)** Denny Zhou-DeepMind ([Video](https://www.google.com/search?q=llm+reasoning+key+ideas+and+limitations&oq=LLM+Reasoning+key+ideas&gs_lcrp=EgZjaHJvbWUqBwgAEAAYgAQyBwgAEAAYgAQyBggBEEUYOTINCAIQABiGAxiABBiKBTINCAMQABiGAxiABBiKBTINCAQQABiGAxiABBiKBTINCAUQABiGAxiABBiKBdIBCDQ5NjRqMGoxqAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:22a2556e,vid:-SZAciVbswk,st:0))
* **[Towards Reasoning in Large Language Models](https://jeffhj.github.io/files/acl2023-slides-llm-reasoning.pdf)** Jie Huang-UIUC
* **[Can LLMs Reason & Plan?](https://icml.cc/media/icml-2024/Slides/33965.pdf)** Subbarao Kambhampati-ASU
* **[Inference-Time Techniques for LLM Reasoning](https://rdi.berkeley.edu/adv-llm-agents/slides/inference_time_techniques_lecture_sp25.pdf)** Xinyun Chen-DeepMind
* **[Chain-of-Thought Reasoning In Language Models](https://bcmi.sjtu.edu.cn/~zhangzs/slides/CoT-zhuosheng.pdf)** Zhuosheng Zhang-SJTU
* **[Learning to Self-Improve & Reason with LLMs](https://rdi.berkeley.edu/adv-llm-agents/slides/Jason-Weston-Reasoning-Alignment-Berkeley-Talk.pdf)** Jason Weston-Meta & NYU

## Video
* [EZ撸paper: DeepSeek-R1 论文详解 part 1：比肩 OpenAI-o1，如何做到的？](https://www.youtube.com/watch?v=tRuN8xYdETs&t=283s)
* [EZ撸paper: DeepSeek-R1 论文详解 part 2：AGI是什么? | Reinforcement Learning快速入门 | AlphaGo介绍](https://www.youtube.com/watch?v=_dLlfAPuilM)
* [[GRPO Explained] DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://www.youtube.com/watch?v=bAWV_yrqx4w)
* [DeepSeek R1 Explained to your grandma](https://www.youtube.com/watch?v=kv8frWeKoeo&t=226s)


## Open-Source Project
* 🔥 ![TinyZero Stars](https://img.shields.io/github/stars/Jiayi-Pan/TinyZero) [TinyZero](https://github.com/Jiayi-Pan/TinyZero) (4*4090 is enough for 0.5B LLM, but can't observe aha moment)
* 🔥 ![Open-r1 Stars](https://img.shields.io/github/stars/huggingface/open-r1) [Open-r1](https://github.com/huggingface/open-r1)
* 🔥 ![Logic-RL Stars](https://img.shields.io/github/stars/Unakar/Logic-RL) [Logic-RL](https://github.com/Unakar/Logic-RL)
* 🔥 ![Unsloth-GRPO Stars](https://img.shields.io/github/stars/unslothai/unsloth) [Unsloth-GRPO](https://colab.research.google.com/drive/11t4njE3c4Lxl-07OD8lJSMKkfyJml3Tn?usp=sharing) (simplest r1 implementation)


## Introduction to Reinforcement Learning
* [（PPO、Q-learning、DQN、A3C）算法原理](https://www.bilibili.com/video/BV1Za4y1d7YJ?spm_id_from=333.788.player.switch&vd_source=228d782c60d8b392d7077abd8d7a1fee&p=3)
* [pytorch 强化学习-五道口纳什](https://www.bilibili.com/video/BV1tP411M7dT?spm_id_from=333.788.videopod.sections&vd_source=228d782c60d8b392d7077abd8d7a1fee)
* [【莫烦Python】强化学习 Reinforcement Learning](https://www.bilibili.com/video/BV13W411Y75P/?spm_id_from=333.788.top_right_bar_window_custom_collection.content.click&vd_source=228d782c60d8b392d7077abd8d7a1fee)


## Cloud GPU
* [Compshare](https://passport.compshare.cn/register?referral_code=Cb96G1f6v4pCdYvO9jqDYd) (After registration, there is a quota of 50 yuan, enough to run R1 on unsloth)


## Contributing

* Feel free to contribute more papers or other any resources!
