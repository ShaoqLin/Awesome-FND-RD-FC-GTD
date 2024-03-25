[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ShaoqLin/Awesome-FND-RD-FC-GTD)

# <p align=center>`A collection of FND, RD, FC and GTD`</p>

**A collection of NLP tasks: Fake News Detection(FND), Rumor Detection(RD), Fact-Checking(FC) and Generated Texts Detection(GTD)**

## Categories
**Following [Awesome-Fake-News-Detection](https://github.com/wangbing1416/Awesome-Fake-News-Detection), we split this repo into four categories.**
|:cat:|:dog:|:tiger:|:wolf:|
|------|------|------|------|
|[1.Fake News Detection(FND)(虚假新闻检测)](#1)|[2.Rumor Detection(RD)(谣言检测)](#2)|[3.Fact-Checking(FC)(事实核查)](#3)|[4.Generated Texts Detection(GTD)(生成文本检测)](#4)|

## 📢 Updates
:fire: Last Updated 2024.03.25

- **2024.3.25**: Added 5 papers of 1.1.1.2 Domain Adaptation; Added 2 papers of 1.1.1.3 Knowledge base-based
- **2024.3.21**: Added 8 papers of 1.1.1.1 Supervised Learning


## <a name="1">1.Fake News Detection(FND)(虚假新闻检测)</a>

### <a name="1.1">1.1 Context-based FND(基于内容的虚假新闻检测)</a>

#### <a name="1.1.1">1.1.1 Text-only Methods</a>

##### <a name="1.1.1.1">1.1.1.1 Supervised Learning</a>
|Abbreviation|Title|Publication|Paper|Code|Device Requirement|
|:---:|---|:---:|:---:|:---:|:---:|
|**FTT**|**Learn over Past, Evolve for Future: Forecasting Temporal Trends for Fake News Detection**|ACL2023|[paper](https://arxiv.org/pdf/2306.14728.pdf)|[code](https://github.com/ICTMCG/FTT-ACL23)|single GPU|
|**FakingFakeNews**|**Faking Fake News for Real Fake News Detection: Propaganda-loaded Training Data Generation**|ACL2023|[paper](https://arxiv.org/pdf/2203.05386.pdf)|[code](https://github.com/khuangaf/FakingFakeNews)|single V100|
|**NEP**|**Zoom Out and Observe: News Environment Perception for Fake News Detection**|ACL2022|[paper](https://aclanthology.org/2022.acl-long.311.pdf)|[code](https://github.com/ICTMCG/News-Environment-Perception)|single GPU|
|**CofCED**|**A Coarse-to-fine Cascaded Evidence-Distillation Neural Network for Explainable Fake News Detection**|COLING2022|[paper](https://aclanthology.org/2022.coling-1.230.pdf)|[code](https://github.com/Nicozwy/CofCED)|single GPU|
|**DS**|**Demystifying Neural Fake News via Linguistic Feature-Based Interpretation**|COLING2022|[paper](https://aclanthology.org/2022.coling-1.230.pdf)|None|single GPU|
|**ENDEF**|**Generalizing to the Future: Mitigating Entity Bias in Fake News Detection**|SIGIR2022|[paper](https://arxiv.org/pdf/2204.09484.pdf)|[code](https://github.com/ICTMCG/ENDEF-SIGIR2022)|single GPU|
|**ECML**|**Early Detection of Fake News with Multi-source Weak Social Supervision**|ECML2021|[paper](https://arxiv.org/pdf/2004.01732.pdf)|[code](https://github.com/microsoft/MWSS)|>=1 GPU|
|**MDEFND**|**Mining Dual Emotion for Fake News Detection**|ECML2021|[paper](https://arxiv.org/pdf/2004.01732.pdf)|[TensorFlow code](https://github.com/RMSnow/WWW2021)|Unknown|


##### <a name="1.1.1.2">1.1.1.2 Domain Adaptation</a>
|Abbreviation|Title|Publication|Paper|Code|Device Requirement|
|:---:|---|:---:|:---:|:---:|:---:|
|**DITFEND**|**Improving Fake News Detection of Influential Domain via Domain- and Instance-Level Transfer**|COLING2022|[paper](https://arxiv.org/pdf/2209.08902.pdf)|[code](https://github.com/ICTMCG/DITFEND)|~ single GPU|
|**REAL-FND**|**Domain Adaptive Fake News Detection via Reinforcement Learning**|WWW2022|[paper](https://arxiv.org/pdf/2202.08159.pdf)|None|Unknown|
|**M^3FEND**|**Memory-Guided Multi-View Multi-Domain Fake News Detection**|TKDE2022|[paper](https://arxiv.org/pdf/2206.12808.pdf)/[zhihu](https://zhuanlan.zhihu.com/p/568567527)|[code](https://github.com/ICTMCG/M3FEND)|single GPU|
|**CWMDFNN**|**Characterizing Multi-domain False News and Underlying User Effects on Chinese Weibo**|IPM2022|[paper](https://arxiv.org/pdf/2205.03068.pdf)|[code](https://github.com/ICTMCG/Characterizing-Weibo-Multi-Domain-False-News)|No GPU required|
|**FuDFEND**|**FuDFEND: Fuzzy-domain for Multi-domain Fake News Detection**|NLPCC2022|[paper](https://arxiv.org/ftp/arxiv/papers/2205/2205.03778.pdf)|[code](https://github.com/ChaoqiLiang/FuDFEND)|single GPU|


##### <a name="1.1.1.3">1.1.1.3 Knowledge base-based</a>
|Abbreviation|Title|Publication|Paper|Code|Device Requirement|
|:---:|---|:---:|:---:|:---:|:---:|
|**KPL**|**Fake News Detection via Knowledgeable Prompt Learning**|IPM2022|[paper](https://www.sciencedirect.com/science/article/pii/S030645732200139X)|[code](https://github.com/Zzoay/disinformation_detection)|~ single GPU|
|**KAN**|**KAN:Knowledge-aware Attention Network for Fake News Detection**|AAAI2021|[paper](https://aaai.org/papers/00081-kan-knowledge-aware-attention-network-for-fake-news-detection/)|None|Unknown|



## Acknowledgment
This repo is heavily based on [Awesome-Fake-News-Detection](https://github.com/wangbing1416/Awesome-Fake-News-Detection) AND [Awesome-Remote-Sensing-Foundation-Models](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models), we sincerely appreciate their wonderful work :)