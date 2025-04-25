# Awesome-RL-based-LLM-Reasoning
[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/bruno686/Awesome-RL-based-LLM-Reasoning/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

We have witnessed the powerful capabilities of pure RL-based LLM Reasoning. In this repository, we will add  newest papers, slides, and other interesting materials that enhance LLM reasoning with reinforcement learning, helping everyone learn quickly! \
Starring this repository is like being at the forefront of RL-based LLM reasoning. \
在风口浪尖 (In the teeth of the storm) 

## Why ?
* Why do we need reasoning?
* Why do we use reinforcement learning to get reasoning ability? (What are the advantages compared to reasoning methods that do not use reinforcement learning?)

## Papers

### Outcome-based Reward Model
* [2502] [Exploring the Limit of Outcome Reward for Learning Mathematical Reasoning](https://www.alphaxiv.org/abs/2502.06781) (Shanghai AI Lab)
* [2502] [Demystifying Long Chain-of-Thought Reasoning in LLMs](https://www.alphaxiv.org/abs/2502.03373) (Introduced cosine length-scaling reward with repetition penalty for stable CoT length growth) (IN.AI)
* [2501] [SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model Post-training](https://www.alphaxiv.org/abs/2501.17161v1) (HKU, Berkeley)
* [2501] [Deepseek-r1: Incentivizing reasoning capability in llms via reinforcement learning](https://arxiv.org/pdf/2501.12948?) (Deepseek)
* [2501] [Kimi k1.5: Scaling Reinforcement Learning with LLMs](https://arxiv.org/pdf/2501.12599?) (Kimi)

### Process-based Reward Model
* [2502] [S<sup>2</sup> R: Teaching LLMs to Self-verify and Self-correct via Reinforcement Learning](https://arxiv.org/pdf/2502.12853#page=16.08) (Tencent)
* [2502] [Can 1B LLM Surpass 405B LLM? Rethinking Compute-Optimal Test-Time Scaling](https://www.alphaxiv.org/abs/2502.06703) (THU)
* [2502] [QLASS: Boosting Language Agent Inference via Q-Guided Stepwise Search](https://arxiv.org/pdf/2502.02584) (UCLA-Yizhou Sun)
* [2312] [Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations](https://arxiv.org/abs/2312.08935) (PKU & Deepseek)
* [2305] [Let's verify step by step](https://arxiv.org/pdf/2305.20050) (OpenAI)
* [2211] [Solving math word problems with process-and outcome-based feedback](https://arxiv.org/pdf/2211.14275) (DeepMind)

### Reinforcement learning
* [2504] [Learning to Reason under Off-Policy Guidance](https://arxiv.org/abs/2504.14945) (Shanghai AI Lab)
* [2504] [THINKPRUNE: Pruning Long Chain-of-Thought of LLMs via Reinforcement Learning](https://arxiv.org/pdf/2504.01296)
* [2504] [GPG: A Simple and Strong Reinforcement Learning Baseline for Model Reasoning](https://www.arxiv.org/pdf/2504.02546)
* [2504] [When To Solve, When To Verify: Compute-Optimal Problem Solving and Generative Verification for LLM Reasoning](https://arxiv.org/pdf/2504.01005) [| Explain](https://x.com/hbXNov/status/1907253956788777041)
* [2503] [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/pdf/2503.15478) (agent & reasoning)
* [2503] [DAST: Difficulty-Adaptive Slow-Thinking for Large Reasoning Models](https://arxiv.org/pdf/2503.04472) (short length of thinking by RL)
* [2503] [L1: Controlling How Long A Reasoning Model Thinks With Reinforcement Learning](https://www.arxiv.org/pdf/2503.04697) (CMU)
* [2502] [Scaling Test-Time Compute Without Verification or RL is Suboptimal](https://arxiv.org/pdf/2502.12118) (CMU, UC Berkeley) (verifier-based (VB) is better than verifier-free (VF))
* [2502] [Reasoning with Reinforced Functional Token Tuning](https://arxiv.org/pdf/2502.13389)
* [2502] [Provably Optimal Distributional RL for LLM Post-Training](https://arxiv.org/pdf/2502.20548) (Cornell, Harvard)
* [2502] [On the Emergence of Thinking in LLMs I: Searching for the Right Intuition ](https://www.alphaxiv.org/abs/2502.06773) (Reinforcement Learning via Self-Play) (MIT)
* [2502] [STP: Self-play LLM Theorem Provers with Iterative Conjecturing and Proving](https://arxiv.org/pdf/2502.00212) (the scarcity of correct proofs sparse rewards will make performance quickly plateaus. To overcome this, we draw inspiration from mathematicians, who continuously develop new results, partly by proposing novel conjectures or exercises (which are often variants of known
results) and attempting to solve them.) (Stanford-Tengyu Ma)
* [2409] [Training Language Models to Self-Correct via Reinforcement Learning](https://arxiv.org/abs/2409.12917) (DeepMind)


### Search algorithms (Monte Carlo Tree Search or Beam Search)
* [2502] [Don’t Get Lost in the Trees: Streamlining LLM Reasoning by Overcoming Tree Search Exploration Pitfalls](https://arxiv.org/pdf/2502.11183v1) (Tencent)
* [2408] [Deepseek-prover-v1. 5: Harnessing proof assistant feedback for reinforcement learning and monte-carlo tree search](https://arxiv.org/abs/2408.08152) (DeepSeek)
* [2310] [Solving olympiad geometry without human demonstrations](https://www.nature.com/articles/s41586-023-06747-5.pdf) (DeepMind)

### Question about LLM Reasoning Ability
* [2504] [A Sober Look at Progress in Language Model Reasoning: Pitfalls and Paths to Reproducibility](https://arxiv.org/pdf/2504.07086) 
* [2504] [Recitation over Reasoning: How Cutting-Edge Language Models Can Fail on Elementary School-Level Reasoning Problems?](https://arxiv.org/pdf/2504.00509) (ByteDance Seed) (by changing one phrase in the condition, top models such as OpenAI-o1 and DeepSeek-R1 can suffer 60% performance loss on elementary school-level arithmetic and reasoning problems)
* [2503] [Proof or Bluff? Evaluating LLMs on 2025 USA Math Olympiad](https://arxiv.org/pdf/2503.21934v1) (the outcome of the 2025 USA Math Olympiad was worse. Most of the results were 0)


### Other Newest Interesting Papers about LLM Reasoning
* [2504] [DeepSeek-R1 Thoughtology: Let's <think> about LLM Reasoning](https://arxiv.org/pdf/2504.07128)
* [2504] [Reasoning Models Know When They’re Right: Probing Hidden States for Self-Verification](https://arxiv.org/pdf/2504.05419v1)
* [2503] [Efficient Test-Time Scaling via Self-Calibration](https://arxiv.org/pdf/2503.00031)
* [2504] [Do Larger Language Models Imply Better Reasoning? A Pretraining Scaling Law for Reasoning](https://arxiv.org/pdf/2504.03635)
* [2503] [Effectively Controlling Reasoning Models through Thinking Intervention](https://www.alphaxiv.org/abs/2503.24370)
* [2503] [Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models](https://arxiv.org/pdf/2503.22165) (visulize reasoning process)
* [2503] [Efficient Test-Time Scaling via Self-Calibration](https://arxiv.org/pdf/2503.00031) (WUSTL) (LLMs are known to be overconfident and provide unreliable confidence estimation)
* [2503] [Interpreting the Repeated Token Phenomenon in Large Language Models](https://arxiv.org/pdf/2503.08908) (DeepMind)
* [2503] [Attentive Reasoning Queries: A Systematic Method for Optimizing Instruction-Following in Large Language Models](https://arxiv.org/pdf/2503.03669v1) (Emcie Co Ltd)
* [2502] [Revisiting the Test-Time Scaling of o1-like Models: Do they Truly Possess Test-Time Scaling Capabilities?](https://arxiv.org/pdf/2502.12215)
* [2502] [When More is Less: Understanding Chain-of-Thought Length in LLMs](https://www.alphaxiv.org/abs/2502.07266) (I think is also about overthinking) (PKU, MIT)
* [2502] [Token Assorted: Mixing Latent and Text Tokens for Improved Language Model Reasoning](https://arxiv.org/pdf/2502.03275) (Meta-Yuandong Tian)
* [2502] [CoT-Valve: Length-Compressible Chain-of-Thought Tuning](https://www.alphaxiv.org/abs/2502.09601) (overthinking) (NUS)
* [2502] [The Danger of Overthinking: Examining the Reasoning-Action Dilemma in
Agentic Tasks](https://www.alphaxiv.org/abs/2502.08235) (I think overthinking is a practical problem, interesting!) (Berkeley)
* [2502] [ReasonFlux: Hierarchical LLM Reasoning via Scaling Thought Templates](https://www.alphaxiv.org/abs/2502.06772) (Princeton)
* [2502] [Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach](https://www.alphaxiv.org/abs/2502.05171) (Current approaches to improving LM capabilities rely heavily on increasing model size or specialized prompting) (Max-Plank)
* [2502] [LIMO: Less is More for Reasoning](https://arxiv.org/pdf/2502.03387?) (LIMO offers a more principled and direct path through explicit trajectory design obtaining complex reasoning ability) (SJTU)
* [2502] [Confidence Improves Self-Consistency in LLMs](https://arxiv.org/pdf/2502.06233) (the quality of LLM outputs) (Google Reasearch)
* [2502] [LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!](https://arxiv.org/pdf/2502.07374) (UC Berkeley)
* [2502] [BOLT: Bootstrap Long Chain-of-Thought in Language Models without
Distillation](https://arxiv.org/pdf/2502.03860) (Salesforce AI Research)
* [2502] [LLMs Can Teach Themselves to Better Predict the Future](https://arxiv.org/pdf/2502.05253) (self-play generate data) (LSE) 
* [2501] [Reasoning Language Models: A Blueprint](https://arxiv.org/pdf/2501.11223)
* [2501] [s1: Simple test-time scaling](https://arxiv.org/pdf/2501.19393) (Stanford) (distillation and using 'wait' append response)
* [2412] [Formal Mathematical Reasoning: A New Frontier in AI](https://arxiv.org/pdf/2412.16075)
* [2412] [Efficiently Serving LLM Reasoning Programs with Certaindex](https://arxiv.org/pdf/2412.20993) (UCSD) (overthinking, probe in the middle)
* [2412] [Training Large Language Model to Reason in a Continuous Latent Space](https://arxiv.org/pdf/2412.06769?) (Meta-Yuandong Tian)
* [2412] [Scaling of search and learning: A roadmap to reproduce o1 from reinforcement learning perspective](https://arxiv.org/pdf/2412.14135) 
* [2408] [Visual Agents as Fast and Slow Thinkers](https://arxiv.org/pdf/2408.08862)

### Surveys
* [2504] [An Illusion of Progress? Assessing the Current State of Web Agents](https://www.alphaxiv.org/abs/2504.01382) (OSU, Berkeley)
* [2503] [Agentic Large Language Models, a survey](https://www.alphaxiv.org/abs/2503.23037) (LeidenU)
* [2503] [Harnessing the Reasoning Economy A Survey of Efficient Reasoning for Large Language Models](https://www.alphaxiv.org/abs/2503.24377) (CUHK)
* [2503] [What, How, Where, and How Well? A Survey on Test-Time Scaling in Large Language Models](https://www.alphaxiv.org/abs/2503.24235) (CityU)
* [2503] [A Survey of Efficient Reasoning for Large Reasoning Models: Language, Multimodality, and Beyond](https://arxiv.org/pdf/2503.21614)
* [2503] [Stop Overthinking: A Survey on Efficient Reasoning for Large Language Models](https://arxiv.org/pdf/2503.16419v1)
* [2502] [From System 1 to System 2: A Survey of Reasoning Large Language Models](https://arxiv.org/pdf/2502.17419)
* [2407] [A comprehensive survey of LLM alignment techniques: RLHF, RLAIF, PPO, DPO and more](https://arxiv.org/pdf/2407.16216#page=31.08)

<!-- * []()
* [] []() ()
* []()
* []()  -->

### 

## Slides and Discussion
* [Self-improvement of LLM agents through Reinforcement Learning at Scale ](https://www.csail.mit.edu/event/scale-ml-self-improvement-llm-agents-through-reinforcement-learning-scale)
* [A Visual Guide to Reasoning LLMs](https://substack.com/home/post/p-153314921)
* [Understanding Reasoning LLMs Methods and Strategies for Building and Refining Reasoning Models](https://sebastianraschka.com/blog/2025/understanding-reasoning-llms.html)
* [What is the difference between large reasoning model and LLM?](https://www.zhihu.com/question/11667247329) (Zhihu)
* [LLM Reasoning: Key Ideas and Limitations](https://llm-class.github.io/slides/Denny_Zhou.pdf) Denny Zhou-DeepMind ([Video](https://www.google.com/search?q=llm+reasoning+key+ideas+and+limitations&oq=LLM+Reasoning+key+ideas&gs_lcrp=EgZjaHJvbWUqBwgAEAAYgAQyBwgAEAAYgAQyBggBEEUYOTINCAIQABiGAxiABBiKBTINCAMQABiGAxiABBiKBTINCAQQABiGAxiABBiKBTINCAUQABiGAxiABBiKBdIBCDQ5NjRqMGoxqAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:22a2556e,vid:-SZAciVbswk,st:0))
* [Towards Reasoning in Large Language Models](https://jeffhj.github.io/files/acl2023-slides-llm-reasoning.pdf) Jie Huang-UIUC
* [Can LLMs Reason & Plan?](https://icml.cc/media/icml-2024/Slides/33965.pdf) Subbarao Kambhampati-ASU
* [Inference-Time Techniques for LLM Reasoning](https://rdi.berkeley.edu/adv-llm-agents/slides/inference_time_techniques_lecture_sp25.pdf) Xinyun Chen-DeepMind
* [Chain-of-Thought Reasoning In Language Models](https://bcmi.sjtu.edu.cn/~zhangzs/slides/CoT-zhuosheng.pdf) Zhuosheng Zhang-SJTU
* [Learning to Self-Improve & Reason with LLMs](https://rdi.berkeley.edu/adv-llm-agents/slides/Jason-Weston-Reasoning-Alignment-Berkeley-Talk.pdf) Jason Weston-Meta & NYU
* [为什么在Deepseek-R1-ZERO出现前，无人尝试放弃微调对齐，通过强化学习生成思考链推理模型？](https://www.zhihu.com/question/10696846752) Zhihu
* [Kimi Flood Sung](https://www.zhihu.com/question/10114790245/answer/84028353434) Zhihu
* [Deepseek系列文章梳理](https://www.zhihu.com/question/10714706736/answer/102795684744) Zhihu
* [ChatGPT and The Art of Post-Training](https://docs.google.com/presentation/d/11KWCKUORnPpVMSY6vXgBeFSWo7fJcuGQ9yuR6vC1pzE/edit#slide=id.g329eafab7b6_0_3) Stanford-25/02/18


## Video
* [[LLM+RL] R1 论文导读，SFT vs. RL，RL 基础以及 GRPO 细节，以及一系列复现工作讨论](https://www.bilibili.com/video/BV15yA3eWE5b/?spm_id_from=333.1387.upload.video_card.click&vd_source=228d782c60d8b392d7077abd8d7a1fee)
* [[LLM+RL] 理解 GRPO 公式原理及 TRL GrpoTrainer 代码实现（advantage 与 loss 计算）](https://www.bilibili.com/video/BV1pXA5eyEEg?spm_id_from=333.788.videopod.sections&vd_source=228d782c60d8b392d7077abd8d7a1fee)
* [LLM-Based Reasoning: Opportunities and Pitfalls (LAVA Workshop in ACCV 2024)](https://www.youtube.com/watch?v=sPEwVTOtAZ0)
* [Reinforcement Learning in DeepSeek r1 Visualized](https://www.youtube.com/watch?v=H20Hd6Xb7Qo) ([Chinese](https://www.bilibili.com/video/BV1dWKHetELd/?spm_id_from=333.1007.tianma.1-2-2.click&vd_source=228d782c60d8b392d7077abd8d7a1fee))
* [EZ撸paper: DeepSeek-R1 论文详解 part 3：GPT发展史 | scaling law | 训练范式 | emergent ability](https://www.youtube.com/watch?v=6fPvbIFF_wY&t=1s)
* [EZ撸paper: DeepSeek-R1 论文详解 part 2：AGI是什么? | Reinforcement Learning快速入门 | AlphaGo介绍](https://www.youtube.com/watch?v=_dLlfAPuilM)
* [EZ撸paper: DeepSeek-R1 论文详解 part 1：比肩 OpenAI-o1，如何做到的？](https://www.youtube.com/watch?v=tRuN8xYdETs&t=283s)
* [[GRPO Explained] DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://www.youtube.com/watch?v=bAWV_yrqx4w)
* [DeepSeek R1 Explained to your grandma](https://www.youtube.com/watch?v=kv8frWeKoeo&t=226s)


## Open-Source Project
* ![TinyZero Stars](https://img.shields.io/github/stars/Jiayi-Pan/TinyZero) [TinyZero](https://github.com/Jiayi-Pan/TinyZero) (4*4090 is enough for 0.5B LLM, but can't observe aha moment)
* ![Open-r1 Stars](https://img.shields.io/github/stars/huggingface/open-r1) [Open-r1](https://github.com/huggingface/open-r1)
* ![Logic-RL Stars](https://img.shields.io/github/stars/Unakar/Logic-RL) [Logic-RL](https://github.com/Unakar/Logic-RL)
* ![Unsloth-GRPO Stars](https://img.shields.io/github/stars/unslothai/unsloth) [Unsloth-GRPO](https://colab.research.google.com/drive/11t4njE3c4Lxl-07OD8lJSMKkfyJml3Tn?usp=sharing) (simplest r1 implementation)
* ![OpenR](https://img.shields.io/github/stars/openreasoner/openr) [OpenR](https://github.com/openreasoner/openr) (An Open Source Framework for Advanced Reasoning)
* [DeepSeek-RL-Qwen-0.5B-GRPO-gsm8k](https://github.com/waylandzhang/DeepSeek-RL-Qwen-0.5B-GRPO-gsm8k/blob/main/train-checkpoint-900.ipynb)
* [deepseek_r1_train](https://github.com/wyf3/llm_related/blob/main/deepseek_learn/deepseek_r1_train/deepseek_r1_train.py)

## Introduction to Reinforcement Learning
The core essence of reinforcement learning is **how an agent determines the next action** within an environment to **maximize the return**; the environment’s role is to provide the state and reward.
* **Q-learning (Value-based method)**: A threshold is set, and if the current value is greater than the threshold (epsilon-greddy), a random action is selected; if it is smaller, an action is chosen from the Q-table. Regardless of which method is chosen, the Q-table needs to be updated. After every action, we update the Q-table of the previous state to maximize the return.
* **REINFORCE (Policy-based method)**: It’s like playing Mario where every action in a given playthrough is determined by a policy network. After the game ends, we have the reward for each state and can compute the cumulative return (G) for each state. Then, using this computed G, we calculate the loss and update the parameters of the policy network.
---
* [（PPO、Q-learning、DQN、A3C）算法原理](https://www.bilibili.com/video/BV1Za4y1d7YJ?spm_id_from=333.788.player.switch&vd_source=228d782c60d8b392d7077abd8d7a1fee&p=3)
* [pytorch 强化学习-五道口纳什](https://www.bilibili.com/video/BV1tP411M7dT?spm_id_from=333.788.videopod.sections&vd_source=228d782c60d8b392d7077abd8d7a1fee)
* [【莫烦Python】强化学习 Reinforcement Learning](https://www.bilibili.com/video/BV13W411Y75P/?spm_id_from=333.788.top_right_bar_window_custom_collection.content.click&vd_source=228d782c60d8b392d7077abd8d7a1fee)


## X_PO
* [2501] [(REINFORCE++) A Simple and Efficient Approach for Aligning Large Language Models](https://arxiv.org/pdf/2501.03262) 6 (REINFORCE++ is more stable in training compared to GRPO and faster than PPO in OpenRLHF report)
* [2405] [(SimPO) Simple Preference Optimization with a Reference-Free Reward](https://arxiv.org/pdf/2405.14734) 227
* [2402] [(KTO) Model Alignment as Prospect Theoretic Optimization](https://arxiv.org/pdf/2402.01306) 326
* [2402] [(GRPO) DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/pdf/2402.03300) 250
* [2305] [(DPO) Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/pdf/2305.18290) 2580
* [2203] [(InstructGPT/PPO+LLM) Training language models to follow instructions with human feedback](https://www.mikecaptain.com/resources/pdf/InstructGPT.pdf) 12443
* [1707] [(PPO) Proximal Policy Optimization Algorithms](https://arxiv.org/pdf/1707.06347) 23934
* [1502] [(TRPO)Trust Region Policy Optimization](https://arxiv.org/pdf/1502.05477) 9579
* [1706] [(RLHF) Deep Reinforcement Learning from Human Preferences](https://arxiv.org/abs/1706.03741) 3571

## Cloud GPU
* [Compshare](https://passport.compshare.cn/register?referral_code=Cb96G1f6v4pCdYvO9jqDYd) (After registration, there is a quota of 50 yuan, enough to run R1 on unsloth)


## Other Interesting RL-based Reasoning Repository
* [awesome-llm-reasoning-long2short-papers](https://github.com/yzhangchuck/awesome-llm-reasoning-long2short-papers)
* [Awesome-Long2short-on-LRMs](https://github.com/Hongcheng-Gao/Awesome-Long2short-on-LRMs)
* [Awesome-Efficient-CoT-Reasoning-Summary](https://github.com/zwxandy/Awesome-Efficient-CoT-Reasoning-Summary)
* [Awesome RL-based Reasoning MLLMs](https://github.com/Sun-Haoyuan23/Awesome-RL-based-Reasoning-MLLMs)
* [DecryptPrompt](https://github.com/DSXiangLi/DecryptPrompt) (very comprehensive)

## Contributing

* Feel free to contribute more papers or other any resources!
