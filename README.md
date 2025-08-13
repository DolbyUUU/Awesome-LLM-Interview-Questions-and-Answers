# Awesome-LLM-Interview-Questions-and-Answers

**大模型算法工程师、大模型 Agent 开发工程师面试常见题目和答案**

本项目旨在系统性地整理大语言模型（LLM）相关的核心知识点，并提供一系列常见的面试问题及参考答案。内容涵盖大模型算法工程师、大模型 Agent 开发工程师等热门岗位。

所有答案主要由 **Poe 平台上的 Gemini-2.5-Pro 或 GPT-4o** 生成，部分答案参考了知乎社区的优质内容。

## 目录  
1. [大模型基础](#大模型基础)  
2. [Transformer 和 Attention](#transformer-和-attention)  
3. [强化学习](#强化学习)  
4. [检索增强生成 (RAG)](#检索增强生成-rag)
5. [大模型 Agent](#大模型-agent)  
6. [训练优化](#训练优化)  
7. [模型压缩](#模型压缩)  
8. [疑难问题](#疑难问题)  
9. [大模型开源框架](#大模型开源框架)  
10. [知乎参考](#知乎参考)  
11. [项目经验](#项目经验)  

---

## 大模型基础  

- **大语言模型开发各阶段**  
  [大语言模型开发各阶段](https://poe.com/s/ZA30ztgmME6mBOWmuZtW)  

- **模型微调和通用能力**  
  [模型微调和通用能力](https://poe.com/s/sIIaJudZd7lC7ASLlHiY)  

- **Tokenizer, BPE, WordPiece, SentencePiece**  
  [Tokenizer, BPE, WordPiece, SentencePiece](https://poe.com/s/7drnge1LyjGweszUxRiS)  

- **Activation Functions**  
  [Activation Functions](https://poe.com/s/0p4tRA32ybL4zA5y6gqO)  

- **Optimizers**  
  [Optimizers](https://poe.com/s/FoXHLxqTiH5OCnQTTd3i)  

- **BERT, MLM, NSP**  
  [BERT, MLM, NSP](https://poe.com/s/sjndlhFBOPU10smVGrKS)  

- **损失函数和常见评估指标**  
  [损失函数和常见评估指标](https://poe.com/s/bmEtuR0YvobUA1vxGjQK)  

- **KL Divergence**  
  [KL Divergence](https://poe.com/s/RTYZWZpNYY0Efe8ueP7H)  

- **增量预训练（Continual Pretraining）**  
  [增量预训练](https://poe.com/s/lMtcu6SA95doDq1qSbJa)  

- **损失函数**
  [指令微调损失函数](https://poe.com/s/ZVbA8tAuN4DJBOmxkYhS)
  [GRPO 损失函数](https://poe.com/s/kJgJZCcfHdiIkJqwa91j)

---

## Transformer 和 Attention  

- **Transformer**  
  [Transformer 1](https://poe.com/s/ieIDlCnOqtM2WfrIUzzC)
  [Transformer 2](https://poe.com/s/uGVXOWAgtExTPiHcRqTQ)  

- **Attention**  
  [Attention](https://poe.com/s/ZkgZPm5tp3WGfHqn8DIl)  

- **MHA, MQA, GQA, MLA**  
  [MHA, MQA, GQA, MLA](https://poe.com/s/GrrSvbD1EZbvNnle2Jq7)  

- **Encoder, Decoder, Encoder-Decoder**  
  [Encoder, Decoder, Encoder-Decoder](https://poe.com/s/NZSMlHxUBpmIsmvnUCmO)  

- **Position Encoding**  
  [Position Encoding 1](https://poe.com/s/wGM5G2YrPpGK3Z2rZFUx)  
  [Position Encoding 2](https://poe.com/s/5FE2iK0B1Tw7MxgXPRsw)  

- **Normalization**  
  [Normalization, BatchNorm, LayerNorm](https://poe.com/s/Sg2To53Abjzjl2J9WhZu)  

---

## 强化学习  

- **PPO, DPO, GRPO**  
  [PPO, DPO, GRPO 1](https://poe.com/s/B4EpGMzTcLqr9hED7cIJ)  
  [PPO, DPO, GRPO 2](https://poe.com/s/SXvfbci4kqrR3cdKs6BM)  

- **REINFORCE, REINFORCE++**  
  [REINFORCE, REINFORCE++ 1](https://poe.com/s/fPYaaITcyYSWdKS3uj65)  
  [REINFORCE, REINFORCE++ 2](https://poe.com/s/C7PNV8Fogp98HmWNVwxr)  
  [REINFORCE, REINFORCE++ 3](https://poe.com/s/ft55xkEuR2wlKPZ69XsD)  

- **RL 显存占用**  
  [RL 显存占用](https://poe.com/s/o4vyh9DyFJXk0npqWkaD)  

---

## 检索增强生成 (RAG)  

- **RAG 基础**  
  [Retrieval Augmented Generation (RAG)](https://poe.com/s/816ADff2YCnNCvUjIQkL)  

- **分块与嵌入**  
  [分块与嵌入](https://poe.com/s/GBuhrZmviq2pJCta9XqO)  

- **检索策略**  
  [检索策略](https://poe.com/s/1QeLyLAxLW6oIs0TU5dk)  

- **重排**  
  [重排](https://poe.com/s/DkktTefVDfThDNUfv2sC)  

- **RAG 系统评测**  
  [RAG 系统评测](https://poe.com/s/l2Wlc5zfnPcJNDvwasJU)  

---

## 大模型 Agent  

- **Function Call & MCP**  
  [Function Call & MCP](https://poe.com/s/AKbb4hRLDj1gJbaxVZKy)  

- **上下文工程**  
  [上下文工程](https://poe.com/s/GBVBqvF4L1fS1HwTJe3s)  

- **Tool Use**  
  [Tool Use](https://poe.com/s/pXHoxdvyhUgXrvbXCPrw)  

- **ReAct 论文**  
  [ReAct 论文](https://poe.com/s/m2FxxLOAURZo0Og2EWjO)

- **损失屏蔽**  
  [Retrieved Tokens Loss Masking](https://poe.com/s/tu69rFXupEE0VDM7Ht8i)

---

## 训练优化  

- **显存和时间估算**  
  [显存和时间估算 1](https://poe.com/s/RC6yNDqo1SqeyMN95v1q)  
  [显存和时间估算 2](https://poe.com/s/3KmgZGrp7xm1qBMyfpYR)  

- **并行训练**  
  [数据并行，模型并行，混合并行](https://poe.com/s/FnuDFqEu64UIREnGjbi7)  

- **LoRA**  
  [LoRA 1](https://poe.com/s/mFE7z9iy4ooqIzjze1I0)

- **其他参数高效微调（PEFT）**  
  [参数高效微调（PEFT）](https://poe.com/s/mH04bKuclL19QQ321flF)  

- **混合精度训练**  
  [混合精度训练](https://poe.com/s/7nO9FMZCh7yBtJJoL59A)  

---

## 模型压缩  

- **剪枝 (Pruning)**  
  [剪枝](https://poe.com/s/ctVXwpoz3X6KqNchmAtP)  

- **知识蒸馏**  
  [知识蒸馏](https://poe.com/s/tGVTCMYR2oMXMbvAPRLy)  

- **量化**  
  [量化](https://poe.com/s/7vRIt0JIcc3lhjaspfg5)  

- **混合专家 (MoE)**  
  [Mixture of Experts (MoE)](https://poe.com/s/tZ9nheeSPCZnfRtS4J7p)  

- **参数共享**  
  [参数共享](https://poe.com/s/zugK9xgmA2Yw7njHGgVJ)  

---

## 疑难杂症  

- **灾难性遗忘**  
  [灾难性遗忘](https://poe.com/s/WdtNDMPhJaTMJyKXlxpN)  

- **梯度消失**  
  [梯度消失](https://poe.com/s/4RmyV1fx0EOyQpeosYfG)  

- **长文本处理**  
  [长文本问题](https://poe.com/s/JDxLufwRdmIY3NGx7C06)  

- **幻觉**  
  [幻觉](https://poe.com/s/GsWqvxIhNOz3xgXFX3FV)  

- **课程学习**  
  [课程学习](https://poe.com/s/1qlYhxJPtXwhHtkuAat5)  

---

## 开源框架  

- **预训练、微调、后训练框架对比**  
  [框架对比](https://poe.com/s/gyyG4QWF7RRJkDJYMM2y)  

- **强化学习框架**  
  [强化学习框架](https://zhuanlan.zhihu.com/p/1936165441090328553)  

- **Agent 框架**  
  [Agent 框架](https://poe.com/s/1yvb0Hgw0MHlSEbTMTEm)  

---

## 知乎参考  

- **复现 DeepSeek R1，开发 Deep Research 等**  
  [复现 DeepSeek R1，开发 Deep Research 等](https://www.zhihu.com/column/c_1346432840821862401)  

- **DeepSeek R1 和 V3 的贡献**  
  [DeepSeek R1 和 V3 的贡献](https://zhuanlan.zhihu.com/p/21185030727)  

- **DeepSeek R1 和 Kimi 1.5 对比**  
  [DeepSeek R1 和 Kimi 1.5 对比](https://zhuanlan.zhihu.com/p/27281179209)  

- **大模型 SFT 实践落地**  
  [大模型 SFT 实践落地](https://zhuanlan.zhihu.com/p/692892489)  

---

## 项目经验  

#### 数据集和模型训练
- **数据获取**：训练数据集是如何获取的？
- **SFT 数据格式**：在特定的训练框架下，SFT（Supervised Fine-Tuning）数据集需要遵循什么样的格式？
- **强化学习数据格式**：在特定的训练框架下，强化学习（如 RLHF）的数据集需要遵循什么样的格式？
- **过拟合**：在项目中遇到过哪些过拟合现象？具体是如何分析和解决的？
- **泛化性**：采用了哪些方法来增强模型的泛化能力？
- **损失函数**：是否尝试过修改或自定义损失函数？为什么？效果如何？
- **奖励函数设计**：在强化学习任务中，你是如何设计奖励函数（Reward Function）的？

#### 评测与落地
- **评测体系**：如何构建测试数据集和设计评测指标？
- **效果评估**：如何对项目的整体效果进行综合评测？
- **落地挑战**：你认为大模型在实际业务中难以落地的主要原因有哪些？对应的解决方法是什么？
- **落地经验**：分享一次你成功或失败的落地经验。
- **最大难题**：在整个项目中，你遇到的最大难题是什么？你是如何一步步分析并最终解决的？
