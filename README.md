# 📢 Introduction
The official repository of our survey paper: "[**Towards a Unified View of Preference Learning for Large Language Models: A Survey**](https://arxiv.org/abs/2409.02795)". 

> ❗ Please submit a **PR** or send an mail to [Bofei](gaobofei@stu.pku.edu.cn) if you wanna add your paper to the list, we will also include the paper in the next version of our survey.


<div style="text-align: center;">
    <a href="https://arxiv.org/abs/2409.02795">
        <img alt="Static Badge" src="https://img.shields.io/badge/Paper-Unified%20Vew:%20Preference%20Learning-blue">
    </a>
    <a href="https://aeolian-agenda-626.notion.site/Towards-a-unified-view-of-preference-learning-for-LLMs-A-survey-f09b77391f5a4899998ee4046dc89460">
        <img alt="Static Badge" src="https://img.shields.io/badge/Notion-Unified%20Vew:%20Preference%20Learning-red">
    </a>
</div>



This repo contains a curated list of [📙Awesome LLM Preference Learning Papers](#paperlist).

![Head Picture](./img/Formulation.png)


# 👉 Running Examples
![Running Examples](./img/Running_examples.png)

# 📖 Paper List 
<div id="paperlist"></div>

## 1. Preference Data Collection 

### 1.1 On-Policy
#### Best-of-N sampling:

  **Reinforced Self-Training (ReST) for Language Modeling (2023.8)** 
  *Caglar Gulcehre, Tom Le Paine, Srivatsan Srinivasan, Ksenia Konyushkova, Lotte Weerts, Abhishek Sharma, Aditya Siddhant, Alex Ahern, Miaosen Wang, Chenjie Gu, Wolfgang Macherey, Arnaud Doucet, Orhan Firat, Nando de Freitas* [\[paper\]](https://arxiv.org/abs/2308.08998)

  **Statistical Rejection Sampling Improves Preference Optimization (2023.9)**
  *Tianqi Liu, Yao Zhao, Rishabh Joshi, Misha Khalman, Mohammad Saleh, Peter J. Liu, Jialu Liu* [\[paper\]](https://arxiv.org/abs/2309.06657)

  **West-of-N: Synthetic Preference Generation for Improved Reward Modeling (2024.1)**  *Alizée Pace, Jonathan Mallinson, Eric Malmi, Sebastian Krause, Aliaksei Severyn*  [\[paper\]](https://arxiv.org/abs/2401.12086)

  **Regularized Best-of-N Sampling to Mitigate Reward Hacking for Language Model Alignment (2024.6)** *Yuu Jinnai, Tetsuro Morimura, Kaito Ariu, Kenshi Abe* [\[paper\]](https://arxiv.org/abs/2404.01054)

#### Monte-Carlo Tree Search based Methods:
  > MCTS-based methods are commonly found in tasks involving complex reasoning, making them particularly promising for applications in mathematics, code generation, and general reasoning.
  
  **Alphazero-like Tree-Search can Guide Large Language Model Decoding and Training (2023.9)** *Xidong Feng, Ziyu Wan, Muning Wen, Stephen Marcus McAleer, Ying Wen, Weinan Zhang, Jun Wang* [\[paper\]](https://arxiv.org/abs/2309.17179)

  **Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations (2023.12)** *Peiyi Wang, Lei Li, Zhihong Shao, R.X. Xu, Damai Dai, Yifei Li, Deli Chen, Y.Wu, Zhifang Sui* [\[paper\]](https://arxiv.org/abs/2312.08935)

  **Improve Mathematical Reasoning in Language Models by Automated Process Supervision (2024.6)** *Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun, Abhinav Rastogi* [\[paper\]](https://arxiv.org/abs/2406.06592)

  **ReST-MCTS\*: LLM Self-Training via Process Reward Guided Tree Search (2024.6)** *Dan Zhang, Sining Zhoubian, Ziniu Hu, Yisong Yue, Yuxiao Dong, Jie Tang* [\[paper\]](https://arxiv.org/abs/2406.03816)

  **Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo Tree Self-refine with LLaMa-3 8B (2024.6)** *Di Zhang, Xiaoshui Huang, Dongzhan Zhou, Yuqiang Li, Wanli Ouyang* [\[paper\]](https://arxiv.org/abs/2406.07394)

  **Recovering Mental Representations from Large Language Models with Markov Chain Monte Carlo (2024.6)** *Jian-Qiao Zhu, Haijiang Yan, Thomas L. Griffiths* [\[paper\]](https://arxiv.org/abs/2401.16657)

  **Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers (2024.8)** *Zhenting Qi, Mingyuan Ma, Jiahang Xu, Li Lyna Zhang, Fan Yang, Mao Yang*  [\[paper\]](https://arxiv.org/abs/2408.06195)

### 1.2 Off-Policy
> Off-Policy data is usually the datasets related to preference alignment, which can be found in [RewardBench](https://arxiv.org/pdf/2403.13787) and [Preference_dataset_repo](https://github.com/glgh/awesome-llm-human-preference-datasets). Preference data for training the reward model can also be used for preference learning.

## 2. Feedbacks
### 2.1 Direct Feedback <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-Feedback Source-yellow">
  **Scaling Relationship on Learning Mathematical Reasoning with Large Language Models (2023.8) -- Answer Equivalence** *Zheng Yuan, Hongyi Yuan, Chengpeng Li, Guanting Dong, Keming Lu, Chuanqi Tan, Chang Zhou, Jingren Zhou* [\[paper\]](https://arxiv.org/abs/2308.01825) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-Answer Equivalance-yellow">

  **DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data (2024.5)** *Huajian Xin, Daya Guo, Zhihong Shao, Zhizhou Ren, Qihao Zhu, Bo Liu, Chong Ruan, Wenda Li, Xiaodan Liang* [\[paper\]](https://arxiv.org/abs/2405.14333) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-LEAN-yellow">

  **DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search**  *Huajian Xin, Z.Z. Ren, Junxiao Song, Zhihong Shao, Wanjia Zhao, Haocheng Wang, Bo Liu, Liyue Zhang, Xuan Lu, Qiushi Du, Wenjun Gao, Qihao Zhu, Dejian Yang, Zhibin Gou, Z.F. Wu, Fuli Luo, Chong Ruan* [\[paper\]](https://arxiv.org/abs/2408.08152) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-LEAN-yellow">

  **Contrastive Preference Optimization: Pushing the Boundaries of LLM Performance in Machine Translation** *Haoran Xu, Amr Sharaf, Yunmo Chen, Weiting Tan, Lingfeng Shen, Benjamin Van Durme, Kenton Murray, Young Jin Kim* [\[paper\]](https://arxiv.org/abs/2401.08417) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-QE Metric-yellow">

  **PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback (2023.7)** *Bo Shen, Jiaxin Zhang, Taihong Chen, Daoguang Zan, Bing Geng, An Fu, Muhan Zeng, Ailun Yu, Jichuan Ji, Jingyang Zhao, Yuenan Guo, Qianxiang Wang* [\[paper\]](https://arxiv.org/abs/2307.14936) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-Unit Test-yellow">

  **RLTF: Reinforcement Learning from Unit Test Feedback (2023.7)** *Jiate Liu, Yiqin Zhu, Kaiwen Xiao, Qiang Fu, Xiao Han, Wei Yang, Deheng Ye* [\[paper\]](https://arxiv.org/abs/2307.04349) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-Unit Test-yellow">

  **StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback (2024.2)** *Shihan Dou, Yan Liu, Haoxiang Jia, Limao Xiong, Enyu Zhou, Wei Shen, Junjie Shan, Caishuang Huang, Xiao Wang, Xiaoran Fan, Zhiheng Xi, Yuhao Zhou, Tao Ji, Rui Zheng, Qi Zhang, Xuanjing Huang, Tao Gui* [\[paper\]](https://arxiv.org/abs/2402.01391) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-Compiler-yellow">

  **Aligning LLM Agents by Learning Latent Preference from User Edits (2024.4)** *Ge Gao, Alexey Taymanov, Eduardo Salinas, Paul Mineiro, Dipendra Misra* [\[paper\]](https://arxiv.org/abs/2404.15269) <img alt="Static Badge" src="https://img.shields.io/badge/Feedback-User-yellow">


### 2.2 Model-based Feedback
#### 2.2.1 Reward Model
  **RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback (2023.9)** *Harrison Lee, Samrat Phatale, Hassan Mansoor, Thomas Mesnard, Johan Ferret, Kellie Lu, Colton Bishop, Ethan Hall, Victor Carbune, Abhinav Rastogi, Sushant Prakash* [\[paper\]](https://arxiv.org/abs/2309.00267)

  **Regularized Best-of-N Sampling to Mitigate Reward Hacking for Language Model Alignment (2024.4)** *Yuu Jinnai, Tetsuro Morimura, Kaito Ariu, Kenshi Abe* [\[paper\]](https://arxiv.org/abs/2404.01054)

  **West-of-N: Synthetic Preference Generation for Improved Reward Modeling (2024.1)** *Alizée Pace, Jonathan Mallinson, Eric Malmi, Sebastian Krause, Aliaksei Severyn*
 [\[paper\]](https://arxiv.org/abs/2401.12086)

  **Reward Model Ensembles Help Mitigate Overoptimization (2023.10)** *Thomas Coste, Usman Anwar, Robert Kirk, David Krueger* [\[paper\]](https://arxiv.org/abs/2310.02743)

  **Uncertainty-Penalized Reinforcement Learning from Human Feedback with Diverse Reward LoRA Ensembles (2023.12)** *Yuanzhao Zhai, Han Zhang, Yu Lei, Yue Yu, Kele Xu, Dawei Feng, Bo Ding, Huaimin Wang* [\[paper\]](https://arxiv.org/abs/2401.00243)

  **WARM: On the Benefits of Weight Averaged Reward Models (2024.1)** *Alexandre Ramé, Nino Vieillard, Léonard Hussenot, Robert Dadashi, Geoffrey Cideron, Olivier Bachem, Johan Ferret* [\[paper\]](https://arxiv.org/abs/2401.12187)

  **Improving Reinforcement Learning from Human Feedback with Efficient Reward Model Ensemble (2024.1)** *Shun Zhang, Zhenfang Chen, Sunli Chen, Yikang Shen, Zhiqing Sun, Chuang Gan* [\[paper\]](https://arxiv.org/abs/2401.16635)

  **Solving math word problems with process- and outcome-based feedback (2022.11)** *Jonathan Uesato, Nate Kushman, Ramana Kumar, Francis Song, Noah Siegel, Lisa Wang, Antonia Creswell, Geoffrey Irving, Irina Higgins* [\[paper\]](https://arxiv.org/abs/2211.14275)

  **Fine-Grained Human Feedback Gives Better Rewards for Language Model Training (2023.6)** *Zeqiu Wu, Yushi Hu, Weijia Shi, Nouha Dziri, Alane Suhr, Prithviraj Ammanabrolu, Noah A. Smith, Mari Ostendorf, Hannaneh Hajishirzi* [\[paper\]](https://arxiv.org/abs/2306.01693)

  **Let's Verify Step by Step (2023.5)** *Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe* [\[paper\]](https://arxiv.org/abs/2305.20050)

  **OVM, Outcome-supervised Value Models for Planning in Mathematical Reasoning (2023.11)** *Fei Yu, Anningzhe Gao, Benyou Wang* [\[paper\]](https://arxiv.org/abs/2311.09724)

  **Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations (2023.12)**  *Peiyi Wang, Lei Li, Zhihong Shao, R.X. Xu, Damai Dai, Yifei Li, Deli Chen, Y.Wu, Zhifang Sui* [\[paper\]](https://arxiv.org/abs/2312.08935)

  **Prior Constraints-based Reward Model Training for Aligning Large Language Models (2024.4)**  *Hang Zhou, Chenglong Wang, Yimin Hu, Tong Xiao, Chunliang Zhang, Jingbo Zhu* [\[paper\]](https://arxiv.org/abs/2404.00978)

  **Improve Mathematical Reasoning in Language Models by Automated Process Supervision (2024.6)** *Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun, Abhinav Rastogi* [\[paper\]](https://arxiv.org/abs/2406.06592)

  **LLM Critics Help Catch Bugs in Mathematics: Towards a Better Mathematical Verifier with Natural Language Feedback (2024.6)** *Bofei Gao, Zefan Cai, Runxin Xu, Peiyi Wang, Ce Zheng, Runji Lin, Keming Lu, Dayiheng Liu, Chang Zhou, Wen Xiao, Junjie Hu, Tianyu Liu, Baobao Chang* [\[paper\]](https://arxiv.org/abs/2406.14024)

  **DMoERM: Recipes of Mixture-of-Experts for Effective Reward Modeling (2024.3)** *Shanghaoran Quan* [\[paper\]](https://arxiv.org/abs/2403.01197)

  **General Preference Modeling with Preference Representations for Aligning Language Models (2024.10)** *Yifan Zhang, Ge Zhang, Yue Wu, Kangping Xu, Quanquan Gu* [\[paper\]](https://arxiv.org/abs/2410.02197)

  **Rewarding Progress: Scaling Automated Process Verifiers for LLM Reasoning (2024.10)** *Amrith Setlur, Chirag Nagpal, Adam Fisch, Xinyang Geng, Jacob Eisenstein, Rishabh Agarwal, Alekh Agarwal, Jonathan Berant, Aviral Kumar* [\[paper\]](https://arxiv.org/abs/2410.08146)

  **Skywork-Reward: Bag of Tricks for Reward Modeling in LLMs (2024.10)** *Chris Yuhao Liu, Liang Zeng, Jiacai Liu, Rui Yan, Jujie He, Chaojie Wang, Shuicheng Yan, Yang Liu, Yahui Zhou* [\[paper\]](https://arxiv.org/abs/2410.18451)

#### 2.2.2 Pairwise Scoring
  **PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization (2023.6)** *Yidong Wang, Zhuohao Yu, Zhengran Zeng, Linyi Yang, Cunxiang Wang, Hao Chen, Chaoya Jiang, Rui Xie, Jindong Wang, Xing Xie, Wei Ye, Shikun Zhang, Yue Zhang* [\[paper\]](https://arxiv.org/abs/2306.05087)

  **LLM-Blender: Ensembling Large Language Models with Pairwise Ranking and Generative Fusion (2023.7)** *Dongfu Jiang, Xiang Ren, Bill Yuchen Lin* [\[paper\]](https://arxiv.org/abs/2306.02561)


#### 2.2.3 LLM-as-a-Judge

  **Self-Rewarding Language Models (2024.1)** *Weizhe Yuan, Richard Yuanzhe Pang, Kyunghyun Cho, Xian Li, Sainbayar Sukhbaatar, Jing Xu, Jason Weston* [\[paper\]](https://arxiv.org/abs/2401.10020)

  **LLM Critics Help Catch LLM Bugs (2024.6)** *Nat McAleese, Rai Michael Pokorny, Juan Felipe Ceron Uribe, Evgenia Nitishinskaya, Maja Trebacz, Jan Leike* [\[paper\]](https://arxiv.org/abs/2407.00215)

  **Meta-Rewarding Language Models: Self-Improving Alignment with LLM-as-a-Meta-Judge (2024.7)** *Tianhao Wu, Weizhe Yuan, Olga Golovneva, Jing Xu, Yuandong Tian, Jiantao Jiao, Jason Weston, Sainbayar Sukhbaatar* [\[paper\]](https://arxiv.org/abs/2407.19594)

  **Generative Verifiers: Reward Modeling as Next-Token Prediction (2024.8)** *Lunjun Zhang, Arian Hosseini, Hritik Bansal, Mehran Kazemi, Aviral Kumar, Rishabh Agarwal* [\[paper\]](https://arxiv.org/abs/2408.15240)

  **The Perfect Blend: Redefining RLHF with Mixture of Judges (2024.9)** *Tengyu Xu, Eryk Helenowski, Karthik Abinav Sankararaman, Di Jin, Kaiyan Peng, Eric Han, Shaoliang Nie, Chen Zhu, Hejia Zhang, Wenxuan Zhou, Zhouhao Zeng, Yun He, Karishma Mandyam, Arya Talabzadeh, Madian Khabsa, Gabriel Cohen, Yuandong Tian, Hao Ma, Sinong Wang, Han Fang* [\[paper\]](https://arxiv.org/abs/2409.20370)

  **Beyond Scalar Reward Model: Learning Generative Judge from Preference Data** *Ziyi Ye, Xiangsheng Li, Qiuchi Li, Qingyao Ai, Yujia Zhou, Wei Shen, Dong Yan, Yiqun Liu* [\[paper\]](https://arxiv.org/abs/2410.03742)

## 3. Algorithms
### 3.1 Pointwise Methods
![Pointwise Algorithm Examples](./img/Pointwise_methods.png)

  **STaR: Bootstrapping Reasoning With Reasoning (2022.5)** *Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman* [\[paper\]](https://arxiv.org/abs/2203.14465)

  **RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment (2023.4)** *Hanze Dong, Wei Xiong, Deepanshu Goyal, Yihan Zhang, Winnie Chow, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, Tong Zhang*  [\[paper\]](https://arxiv.org/abs/2304.06767)

  **Scaling Relationship on Learning Mathematical Reasoning with Large Language Models (2023.8)** *Zheng Yuan, Hongyi Yuan, Chengpeng Li, Guanting Dong, Keming Lu, Chuanqi Tan, Chang Zhou, Jingren Zhou* [\[paper\]](https://arxiv.org/abs/2308.01825)

  **Proximal Policy Optimization Algorithms (2017.7)** *John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov*  [\[paper\]](https://arxiv.org/abs/1707.06347)

  **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models (2024.2)**  *Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Xiao Bi, Haowei Zhang, Mingchuan Zhang, Y.K. Li, Y. Wu, Daya Guo* [\[paper\]](https://arxiv.org/abs/2402.03300)

  **ReMax: A Simple, Effective, and Efficient Reinforcement Learning Method for Aligning Large Language Models (2023.10)** *Ziniu Li, Tian Xu, Yushun Zhang, Zhihang Lin, Yang Yu, Ruoyu Sun, Zhi-Quan Luo*  [\[paper\]](https://arxiv.org/abs/2310.10505)

  **KTO: Model Alignment as Prospect Theoretic Optimization (2024.2)** *Kawin Ethayarajh, Winnie Xu, Niklas Muennighoff, Dan Jurafsky, Douwe Kiela*  [\[paper\]](https://arxiv.org/abs/2402.01306)
### 3.2 Pairwise Contrasts
  **Chain of Hindsight Aligns Language Models with Feedback (2023.2)** *Hao Liu, Carmelo Sferrazza, Pieter Abbeel*  [\[paper\]](https://arxiv.org/abs/2302.02676)

  **Calibrating Sequence likelihood Improves Conditional Language Generation (2022.9)** *Yao Zhao, Misha Khalman, Rishabh Joshi, Shashi Narayan, Mohammad Saleh, Peter J. Liu*  [\[paper\]](https://arxiv.org/abs/2210.00045)

  **Direct Preference Optimization: Your Language Model is Secretly a Reward Model (2023.5)** *Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn* [\[paper\]](https://arxiv.org/abs/2305.18290)

  **A General Theoretical Paradigm to Understand Learning from Human Preferences (2023.10)** *Mohammad Gheshlaghi Azar, Mark Rowland, Bilal Piot, Daniel Guo, Daniele Calandriello, Michal Valko, Rémi Munos* [\[paper\]](https://arxiv.org/abs/2310.12036)
  
  **Direct Alignment of Language Models via Quality-Aware Self-Refinement (2024.5)** *Runsheng Yu, Yong Wang, Xiaoqi Jiao, Youzhi Zhang, James T. Kwok* [\[paper\]](https://arxiv.org/abs/2405.21040)
  
  **ORPO: Monolithic Preference Optimization without Reference Model (2024.3)** *Jiwoo Hong, Noah Lee, James Thorne* [\[paper\]](https://arxiv.org/abs/2403.07691)

  **Mallows-DPO: Fine-Tune Your LLM with Preference Dispersions (2024.5)** *Haoxian Chen, Hanyang Zhao, Henry Lam, David Yao, Wenpin Tang* [\[paper\]](https://arxiv.org/abs/2405.14953)

  **Group Robust Preference Optimization in Reward-free RLHF (2024.5)** *Shyam Sundhar Ramesh, Yifan Hu, Iason Chaimalas, Viraj Mehta, Pier Giuseppe Sessa, Haitham Bou Ammar, Ilija Bogunovic* [\[paper\]](https://arxiv.org/abs/2405.20304)

  **Smaug: Fixing Failure Modes of Preference Optimisation with DPO-Positive (2024.2)** *Arka Pal, Deep Karkhanis, Samuel Dooley, Manley Roberts, Siddartha Naidu, Colin White* [\[paper\]](https://arxiv.org/abs/2402.13228)

  **Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints (2023.9)** *Chaoqi Wang, Yibo Jiang, Chenghao Yang, Han Liu, Yuxin Chen* [\[paper\]](https://arxiv.org/abs/2309.16240)

  **Towards Efficient Exact Optimization of Language Model Alignment (2024.2)** *Haozhe Ji, Cheng Lu, Yilin Niu, Pei Ke, Hongning Wang, Jun Zhu, Jie Tang, Minlie Huang* [\[paper\]](https://arxiv.org/abs/2402.00856)

  **SimPO: Simple Preference Optimization with a Reference-Free Reward (2024.5)** *Yu Meng, Mengzhou Xia, Danqi Chen* [\[paper\]](https://arxiv.org/abs/2405.14734)

  **sDPO: Don't Use Your Data All at Once (2024.3)** *Dahyun Kim, Yungi Kim, Wonho Song, Hyeonwoo Kim, Yunsu Kim, Sanghoon Kim, Chanjun Park* [\[paper\]](https://arxiv.org/abs/2403.19270)

  **Learn Your Reference Model for Real Good Alignment (2024.4)** *Alexey Gorbatovski, Boris Shaposhnikov, Alexey Malakhov, Nikita Surnachev, Yaroslav Aksenov, Ian Maksimov, Nikita Balagansky, Daniil Gavrilov* [\[paper\]](https://arxiv.org/abs/2404.09656)

  **Statistical Rejection Sampling Improves Preference Optimization (2023.9)** *Tianqi Liu, Yao Zhao, Rishabh Joshi, Misha Khalman, Mohammad Saleh, Peter J. Liu, Jialu Liu* [\[paper\]](https://arxiv.org/abs/2309.06657)

  **Controllable Preference Optimization: Toward Controllable Multi-Objective Alignment (2024.2)** *Yiju Guo, Ganqu Cui, Lifan Yuan, Ning Ding, Jiexin Wang, Huimin Chen, Bowen Sun, Ruobing Xie, Jie Zhou, Yankai Lin, Zhiyuan Liu, Maosong Sun* [\[paper\]](https://arxiv.org/abs/2402.19085)

  **MAPO: Advancing Multilingual Reasoning through Multilingual Alignment-as-Preference Optimization (2024.1)** *Shuaijie She, Wei Zou, Shujian Huang, Wenhao Zhu, Xiang Liu, Xiang Geng, Jiajun Chen* [\[paper\]](https://arxiv.org/abs/2401.06838)
  
  **KnowTuning: Knowledge-aware Fine-tuning for Large Language Models (2024.2)** *Yougang Lyu, Lingyong Yan, Shuaiqiang Wang, Haibo Shi, Dawei Yin, Pengjie Ren, Zhumin Chen, Maarten de Rijke, Zhaochun Ren* [\[paper\]](https://arxiv.org/abs/2402.11176)

  **TS-Align: A Teacher-Student Collaborative Framework for Scalable Iterative Finetuning of Large Language Models (2024.5)** *Chen Zhang, Chengguang Tang, Dading Chong, Ke Shi, Guohua Tang, Feng Jiang, Haizhou Li* [\[paper\]](https://arxiv.org/abs/2405.20215)

  **Beyond One-Preference-Fits-All Alignment: Multi-Objective Direct Preference Optimization (2023.10)** *Zhanhui Zhou, Jie Liu, Jing Shao, Xiangyu Yue, Chao Yang, Wanli Ouyang, Yu Qiao* [\[paper\]](https://arxiv.org/abs/2310.03708)

  **Hybrid Preference Optimization: Augmenting Direct Preference Optimization with Auxiliary Objectives(2024.5)** *Anirudhan Badrinath, Prabhat Agarwal, Jiajing Xu* [\[paper\]](https://arxiv.org/abs/2405.17956)

### 3.3 Listwise Contrasts
  **RRHF: Rank Responses to Align Language Models with Human Feedback without tears (2023.4)** *Zheng Yuan, Hongyi Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, Fei Huang* [\[paper\]](https://arxiv.org/abs/2304.05302)

  **Preference Ranking Optimization for Human Alignment (2023.6)** *Feifan Song, Bowen Yu, Minghao Li, Haiyang Yu, Fei Huang, Yongbin Li, Houfeng Wang* [\[paper\]](https://arxiv.org/abs/2306.17492)

  **CycleAlign: Iterative Distillation from Black-box LLM to White-box Models for Better Human Alignment (2023.10)** *Jixiang Hong, Quan Tu, Changyu Chen, Xing Gao, Ji Zhang, Rui Yan* [\[paper\]](https://arxiv.org/abs/2310.16271)

  **Making Large Language Models Better Reasoners with Alignment (2023.9)** *Peiyi Wang, Lei Li, Liang Chen, Feifan Song, Binghuai Lin, Yunbo Cao, Tianyu Liu, Zhifang Sui* [\[paper\]](https://arxiv.org/abs/2309.02144)

  **Don't Forget Your Reward Values: Language Model Alignment via Value-based Calibration (2024.2)** *Xin Mao, Feng-Lin Li, Huimin Xu, Wei Zhang, Anh Tuan Luu* [\[paper\]](https://arxiv.org/abs/2402.16030)

  **LiPO: Listwise Preference Optimization through Learning-to-Rank (2024.2)** *Tianqi Liu, Zhen Qin, Junru Wu, Jiaming Shen, Misha Khalman, Rishabh Joshi, Yao Zhao, Mohammad Saleh, Simon Baumgartner, Jialu Liu, Peter J. Liu, Xuanhui Wang* [\[paper\]](https://arxiv.org/abs/2402.01878)

  **LIRE: listwise reward enhancement for preference alignment (2024.5)** *Mingye Zhu, Yi Liu, Lei Zhang, Junbo Guo, Zhendong Mao* [\[paper\]](https://arxiv.org/abs/2405.13516)

  **LPOI: Listwise Preference Optimization for Vision Language Models (2025.5)** *Fatemeh Pesaran Zadeh, Yoojin Oh, Gunhee Kim* [\[paper\]](https://arxiv.org/abs/2505.21061)
### 3.4 Training-Free Methods
  **Black-Box Prompt Optimization: Aligning Large Language Models without Model Training (2023.11)** *Jiale Cheng, Xiao Liu, Kehan Zheng, Pei Ke, Hongning Wang, Yuxiao Dong, Jie Tang, Minlie Huang* [\[paper\]](https://arxiv.org/abs/2311.04155)

  **The Unlocking Spell on Base LLMs: Rethinking Alignment via In-Context Learning (2023.12)** *Bill Yuchen Lin, Abhilasha Ravichander, Ximing Lu, Nouha Dziri, Melanie Sclar, Khyathi Chandu, Chandra Bhagavatula, Yejin Choi* [\[paper\]](https://arxiv.org/abs/2312.01552)

  **ICDPO: Effectively Borrowing Alignment Capability of Others via In-context Direct Preference Optimization (2024.2)** *Feifan Song, Yuxuan Fan, Xin Zhang, Peiyi Wang, Houfeng Wang* [\[paper\]](https://arxiv.org/abs/2402.09320)

  **Aligner: Efficient Alignment by Learning to Correct (2024.2)** *Jiaming Ji, Boyuan Chen, Hantao Lou, Donghai Hong, Borong Zhang, Xuehai Pan, Juntao Dai, Tianyi Qiu, Yaodong Yang* [\[paper\]](https://arxiv.org/abs/2402.02416)

  **RAIN: Your Language Models Can Align Themselves without Finetuning (2023.9)** *Yuhui Li, Fangyun Wei, Jinjing Zhao, Chao Zhang, Hongyang Zhang* [\[paper\]](https://arxiv.org/abs/2309.07124)

  **Reward-Augmented Decoding: Efficient Controlled Text Generation With a Unidirectional Reward Model (2023.10)** *Haikang Deng, Colin Raffel* [\[paper\]](https://arxiv.org/abs/2310.09520)

  **Controlled Decoding from Language Models (2023.10)** *Sidharth Mudgal, Jong Lee, Harish Ganapathy, YaGuang Li, Tao Wang, Yanping Huang, Zhifeng Chen, Heng-Tze Cheng, Michael Collins, Trevor Strohman, Jilin Chen, Alex Beutel, Ahmad Beirami* [\[paper\]](https://arxiv.org/abs/2310.17022)

  **DeAL: Decoding-time Alignment for Large Language Models (2024.2)** *James Y. Huang, Sailik Sengupta, Daniele Bonadiman, Yi-an Lai, Arshit Gupta, Nikolaos Pappas, Saab Mansour, Katrin Kirchhoff, Dan Roth* [\[paper\]](https://arxiv.org/abs/2402.06147)

  **Decoding-time Realignment of Language Models (2024.2)** *Tianlin Liu, Shangmin Guo, Leonardo Bianco, Daniele Calandriello, Quentin Berthet, Felipe Llinares, Jessica Hoffmann, Lucas Dixon, Michal Valko, Mathieu Blondel* [\[paper\]](https://arxiv.org/abs/2402.02992)
## 4. Evaluation
### 4.1 Rule Based
> Rule-based benchmarks are traditional benchmarks that span various domains such as reasoning, translation, dialogue, question-answering, code generation, and more. We won't list them all individually.
### 4.2 LLM based
  **G-Eval: NLG Evaluation using GPT-4 with Better Human Alignment (2023.3)** *Yang Liu, Dan Iter, Yichong Xu, Shuohang Wang, Ruochen Xu, Chenguang Zhu* [\[paper\]](https://arxiv.org/abs/2303.16634)

  **Automated Evaluation of Personalized Text Generation using Large Language Models (2023.10)** *Yaqing Wang, Jiepu Jiang, Mingyang Zhang, Cheng Li, Yi Liang, Qiaozhu Mei, Michael Bendersky* [\[paper\]](https://arxiv.org/abs/2310.11593)

  **Multi-Dimensional Evaluation of Text Summarization with In-Context Learning (2023.6)** *Sameer Jain, Vaishakh Keshava, Swarnashree Mysore Sathyendra, Patrick Fernandes, Pengfei Liu, Graham Neubig, Chunting Zhou* [\[paper\]](https://arxiv.org/abs/2306.01200)

  **Large Language Models Are State-of-the-Art Evaluators of Translation Quality (2023.2)** *Tom Kocmi, Christian Federmann* [\[paper\]](https://arxiv.org/abs/2302.14520)

  **Large Language Models are not Fair Evaluators (2023.5)** *Peiyi Wang, Lei Li, Liang Chen, Zefan Cai, Dawei Zhu, Binghuai Lin, Yunbo Cao, Qi Liu, Tianyu Liu, Zhifang Sui* [\[paper\]](https://arxiv.org/abs/2305.17926)

  **Generative Judge for Evaluating Alignment (2023.10)** *Junlong Li, Shichao Sun, Weizhe Yuan, Run-Ze Fan, Hai Zhao, Pengfei Liu* [\[paper\]](https://arxiv.org/abs/2310.05470)

  **Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena (2023.6)** *Lianmin Zheng, Wei-Lin Chiang, Ying Sheng, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zi Lin, Zhuohan Li, Dacheng Li, Eric P. Xing, Hao Zhang, Joseph E. Gonzalez, Ion Stoica* [\[paper\]](https://arxiv.org/abs/2306.05685)

  **Prometheus: Inducing Fine-grained Evaluation Capability in Language Models (2023.10)** *Seungone Kim, Jamin Shin, Yejin Cho, Joel Jang, Shayne Longpre, Hwaran Lee, Sangdoo Yun, Seongjin Shin, Sungdong Kim, James Thorne, Minjoon Seo* [\[paper\]](https://arxiv.org/abs/2310.08491)

  **PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization (2023.6)** *PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization* [\[paper\]](https://arxiv.org/abs/2306.05087)

  **PRD: Peer Rank and Discussion Improve Large Language Model based Evaluations (2023.7)** *Ruosen Li, Teerth Patel, Xinya Du* [\[paper\]](https://arxiv.org/abs/2307.02762)

  **Evaluating Large Language Models at Evaluating Instruction Following (2023.10)** *Zhiyuan Zeng, Jiatong Yu, Tianyu Gao, Yu Meng, Tanya Goyal, Danqi Chen* [\[paper\]](https://arxiv.org/abs/2310.07641)

  **Wider and Deeper LLM Networks are Fairer LLM Evaluators (2023.8)** *Xinghua Zhang, Bowen Yu, Haiyang Yu, Yangyu Lv, Tingwen Liu, Fei Huang, Hongbo Xu, Yongbin Li* [\[paper\]](https://arxiv.org/abs/2308.01862)

  **How to Evaluate Reward Models for RLHF (2024.10)** *Evan Frick, Tianle Li, Connor Chen, Wei-Lin Chiang, Anastasios N. Angelopoulos, Jiantao Jiao, Banghua Zhu, Joseph E. Gonzalez, Ion Stoica* [\[paper\]](https://arxiv.org/abs/2410.14872)

# 🌟Contribute
Welcome to star & submit a PR to this repo! 


# 📝 Citation
```bibtex
@misc{gao2024unifiedviewpreferencelearning,
      title={Towards a Unified View of Preference Learning for Large Language Models: A Survey}, 
      author={Bofei Gao and Feifan Song and Yibo Miao and Zefan Cai and Zhe Yang and Liang Chen and Helan Hu and Runxin Xu and Qingxiu Dong and Ce Zheng and Wen Xiao and Ge Zhang and Daoguang Zan and Keming Lu and Bowen Yu and Dayiheng Liu and Zeyu Cui and Jian Yang and Lei Sha and Houfeng Wang and Zhifang Sui and Peiyi Wang and Tianyu Liu and Baobao Chang},
      year={2024},
      eprint={2409.02795},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2409.02795}, 
}
```
