# Awesome-LLM-Interview-Questions-and-Answers  
**大模型算法工程师、大模型 Agent 开发工程师面试常见题目和答案**  

本项目提供了一系列与大模型相关的知识点、面试问题及答案，答案由 **Poe 平台上的 Gemini-2.5-Pro 或 GPT-4o** 生成（访问 Poe 分享链接可能需要翻墙）。  

## 目录  
1. [大模型基础](#大模型基础)  
2. [Transformer 和 Attention](#transformer-和-attention)  
3. [强化学习相关](#强化学习相关)  
4. [Retrieval Augmented Generation (RAG)相关](#retrieval-augmented-generation-rag相关)  
5. [训练优化](#训练优化)  
6. [模型压缩](#模型压缩)  
7. [疑难问题](#疑难问题)  
8. [大模型开源框架](#大模型开源框架)  
9. [知乎参考](#知乎参考)  
10. [项目经验](#项目经验)  

---

## 大模型基础  

- **大语言模型开发各阶段**  
  [大语言模型开发各阶段](https://poe.com/s/ZA30ztgmME6mBOWmuZ)  

- **模型微调和通用能力**  
  [模型微调和通用能力](https://poe.com/s/sIIaJudZd7lC7ASLlH)  

- **Function Call & MCP**  
  [Function Call & MCP](https://poe.com/s/AKbb4hRLDj1gJbaxVZ)  

- **上下文工程**  
  [上下文工程](https://poe.com/s/GBVBqvF4L1fS1HwTJe)  

- **Tool Use**  
  [Tool Use](https://poe.com/s/pXHoxdvyhUgXrvbXCP)  

- **ReAct 论文**  
  [ReAct 论文](https://poe.com/s/m2FxxLOAURZo0Og2)  

- **Tokenizer, BPE, WordPiece, SentencePiece**  
  [Tokenizer, BPE, WordPiece, SentencePiece](https://poe.com/s/7drnge1LyjGweszUxR)  

- **Activation Functions**  
  [Activation Functions](https://poe.com/s/0p4tRA32ybL4zA5y6g)  

- **Optimizers**  
  [Optimizers](https://poe.com/s/FoXHLxqTiH5OCnQTTd)  

- **BERT, MLM, NSP**  
  [BERT, MLM, NSP](https://poe.com/s/sjndlhFBOPU10smVGr)  

- **损失函数和常见评估指标**  
  [损失函数和常见评估指标](https://poe.com/s/bmEtuR0YvobUA1vxGj)  

- **KL Divergence**  
  [KL Divergence](https://poe.com/s/RTYZWZpNYY0Efe8ueP)  

- **增量预训练（Continual Pretraining）**  
  [增量预训练](https://poe.com/s/lMtcu6SA95doDq1qSb)  

- **不同阶段损失函数**  
  [不同阶段损失函数](https://poe.com/s/brzTnZIwa0szT5vwGe)  

- **AI 领域常见公式**  
  [AI 领域常见公式](https://poe.com/s/btAIolBXgHJoDivOSh)  

---

## Transformer 和 Attention  

- **Transformer**  
  [Transformer 基础](https://poe.com/s/ieIDlCnOqtM2WfrIUz)  
  [Transformer 深入](https://poe.com/s/uGVXOWAgtExTPiHcR)  

- **Attention**  
  [Attention 机制](https://poe.com/s/ZkgZPm5tp3WGfHqn8)  

- **MHA, MQA, GQA, MLA**  
  [MHA, MQA, GQA, MLA](https://poe.com/s/GrrSvbD1EZbvNnle2)  

- **Encoder, Decoder, Encoder-Decoder**  
  [Encoder, Decoder, Encoder-Decoder](https://poe.com/s/NZSMlHxUBpmIsmvnUC)  

- **Position Encoding**  
  [Position Encoding 基础](https://poe.com/s/wGM5G2YrPpGK3Z2rZ)  
  [Position Encoding 深入](https://poe.com/s/5FE2iK0B1Tw7MxgXP)  

- **Normalization**  
  [Normalization, BatchNorm, LayerNorm](https://poe.com/s/Sg2To53Abjzjl2J9W)  

---

## 强化学习相关  

- **PPO, DPO, GRPO**  
  [PPO, DPO, GRPO](https://poe.com/s/B4EpGMzTcLqr9hED)  
  [PPO, DPO, GRPO 深入](https://poe.com/s/SXvfbci4kqrR3cdKs)  

- **REINFORCE, REINFORCE++**  
  [REINFORCE 基础](https://poe.com/s/fPYaaITcyYSWdKS3u)  
  [REINFORCE 深入](https://poe.com/s/C7PNV8Fogp98HmWNV)  
  [REINFORCE++](https://poe.com/s/ft55xkEuR2wlKPZ69X)  

- **显存占用**  
  [强化学习的显存占用](https://poe.com/s/o4vyh9DyFJXk0npqW)  

---

## Retrieval Augmented Generation (RAG)相关  

- **RAG 基础**  
  [Retrieval Augmented Generation (RAG)](https://poe.com/s/816ADff2YCnNCvUjI)  

- **分块与嵌入**  
  [分块与嵌入 (Chunking & Embedding)](https://poe.com/s/GBuhrZmviq2pJCta9)  

- **检索策略**  
  [检索策略](https://poe.com/s/1QeLyLAxLW6oIs0TU)  

- **重排**  
  [重排](https://poe.com/s/DkktTefVDfThDNUfv)  

- **RAG 系统评测**  
  [RAG 系统评测](https://poe.com/s/l2Wlc5zfnPcJNDvwa)  

---

## 训练优化  

- **显存和时间估算**  
  [训练显存和时间估算](https://poe.com/s/RC6yNDqo1SqeyMN95v)  
  [深入显存估算](https://poe.com/s/3KmgZGrp7xm1qBMyfp)  

- **并行训练**  
  [数据并行，模型并行，混合并行](https://poe.com/s/FnuDFqEu64UIREnG)  

- **参数高效微调**  
  [LoRA](https://poe.com/s/mFE7z9iy4ooqIzjze)  
  [PEFT](https://poe.com/s/mH04bKuclL19QQ321)  

- **混合精度训练**  
  [混合精度训练](https://poe.com/s/7nO9FMZCh7yBtJJoL)  

---

## 模型压缩  

- **剪枝 (Pruning)**  
  [剪枝](https://poe.com/s/ctVXwpoz3X6KqNchmA)  

- **知识蒸馏**  
  [知识蒸馏](https://poe.com/s/tGVTCMYR2oMXMbvAPR)  

- **量化**  
  [量化](https://poe.com/s/7vRIt0JIcc3lhjaspf)  

- **Mixture of Experts (MoE)**  
  [Mixture of Experts (MoE)](https://poe.com/s/tZ9nheeSPCZnfRtS4J)  

- **低秩分解**  
  [低秩分解](https://poe.com/s/yW5OCjehtdoVcz80YF)  

- **参数共享**  
  [参数共享](https://poe.com/s/zugK9xgmA2Yw7njHGg)  

---

## 疑难问题  

- **灾难性遗忘**  
  [灾难性遗忘](https://poe.com/s/WdtNDMPhJaTMJyKXl)  

- **梯度消失**  
  [梯度消失](https://poe.com/s/4RmyV1fx0EOyQpeos)  

- **长文本处理**  
  [长文本问题](https://poe.com/s/JDxLufwRdmIY3NGx7)  

- **大模型幻觉**  
  [大模型幻觉](https://poe.com/s/GsWqvxIhNOz3xgXFX)  

- **课程学习**  
  [课程学习](https://poe.com/s/1qlYhxJPtXwhHtkuA)  

---

## 大模型开源框架  

- **预训练、微调、后训练框架对比**  
  [框架对比](https://poe.com/s/gyyG4QWF7RRJkDJYMM)  

- **强化学习框架**  
  [强化学习框架](https://zhuanlan.zhihu.com/p/19361654410903285)  

- **Agent 框架**  
  [Agent 框架](https://poe.com/s/1yvb0Hgw0MHlSEbTMT)  

---

## 知乎参考  

- **AI 煎饼摊**  
  [复现 DeepSeek R1，开发 Deep Research](https://www.zhihu.com/column/c_13464328408218624)  

- **DeepSeek R1 和 V3 的贡献**  
  [DeepSeek R1 和 V3 的贡献](https://zhuanlan.zhihu.com/p/211850307)  

- **DeepSeek R1 和 Kimi 1.5**  
  [DeepSeek R1 和 Kimi 1.5](https://zhuanlan.zhihu.com/p/272811792)  

- **大模型 SFT 实践落地**  
  [大模型 SFT 实践落地](https://zhuanlan.zhihu.com/p/6928924)  

---

## 项目经验  

