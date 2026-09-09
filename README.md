# AI 发展史论文资料库

一套覆盖 **1943–2025** 的 AI 代表性论文查阅库，共 **55 篇**，按技术脉络分为四个阶段：从最早的神经模型与符号推理，到传统机器学习、深度学习兴起，再到大模型、生成模型、对齐与 Agent。适合作为 AI 发展主线的学习索引与速查资料。

> 这是一份「查阅资料库」，不是穷尽全集，也不是 2026 前沿榜单。专家系统、概率图模型、因果推断、机器人和语音等领域仍有缺口。

## 概览

| 项目 | 内容 |
|---|---|
| 时间跨度 | 1943 – 2025 |
| 论文数量 | 55 篇（54 篇已下载 PDF，1 篇仅保留链接） |
| 分类 | 4 个阶段 |
| 格式 | PDF（论文正文）+ Markdown / HTML / JSON（索引与指南） |

## 目录结构

```
.
├── 00_打开论文索引.html        # 浏览器可视化索引（推荐入口）
├── 00_阅读指南与索引.md        # 完整论文表：年份 / 阅读线索 / 公开来源
├── 论文清单.json               # 结构化清单（含页数、下载状态）
├── 01_早期与机器学习/           # 19 篇：1943 McCulloch-Pitts → 2006 DBN
├── 02_深度学习兴起/             # 11 篇：2012 AlexNet → 2016 XGBoost
├── 03_大模型与生成模型/         # 11 篇：2017 Transformer → 2021 LoRA
└── 04_对齐推理与Agent/          # 13 篇：2022 CoT → 2025 DeepSeek-R1
```

## 快速开始

1. **浏览索引**：直接打开 `00_打开论文索引.html`，在浏览器里按年份 / 分类点选。
2. **看阅读线索**：`00_阅读指南与索引.md` 里每篇论文都有「阅读线索」一句话摘要和「公开来源」链接。
3. **按需精读**：进入对应分类文件夹读 PDF。年份通常按首次公开年份，arXiv 下载可能是后续修订版。

## 推荐阅读路线（Agent 方向）

```
Transformer → InstructGPT → ReAct → Toolformer → Voyager → SWE-agent
```

## 论文清单

完整列表见 `00_阅读指南与索引.md`，涵盖（按阶段）：

- **早期与机器学习**：McCulloch-Pitts、Turing、Dartmouth、Perceptron、A\*、STRIPS、Hopfield、反向传播、决策树、时序差分、Q-learning、SVM、AdaBoost、LSTM、LeNet、随机森林、神经语言模型、深度信念网络
- **深度学习兴起**：AlexNet、DQN、VAE、word2vec、Adam、注意力机制、GAN、Seq2Seq、BatchNorm、ResNet、XGBoost
- **大模型与生成模型**：AlphaZero、PPO、Transformer、BERT、DDPM、GPT-3、RAG、Scaling Laws、ViT、CLIP、LoRA
- **对齐推理与 Agent**：Chain-of-Thought、Chinchilla、FlashAttention、InstructGPT、ReAct、DPO、Generative Agents、LLaMA、Toolformer、Tree of Thoughts、Voyager、SWE-agent、DeepSeek-R1

## 版权与许可

本仓库包含两类内容，适用不同许可：

- **自建内容**（索引、指南、清单等）：`README.md`、`00_阅读指南与索引.md`、`00_打开论文索引.html`、`论文清单.json` 采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可，详见 [LICENSE](LICENSE)。
- **论文 PDF**：各 `*.pdf` 版权归原作者或出版社所有，本仓库**不对其重新授权**。这些文件仅出于个人学习与学术参考目的收录，多数来自作者本人或机构的公开渠道（arXiv 预印本、作者主页、公开课程页等），完整出处见 `00_阅读指南与索引.md` 的「来源」列。如需使用某篇论文，请以原文出处为准并遵守其自身版权条款。
