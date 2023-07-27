# awesome-multimodal-dialogue
[![Awesome](https://awesome.re/badge.svg)](https://github.com/zjunlp/ModelEditingPapers) 
![](https://img.shields.io/github/last-commit/Aman-4-Real/awesome-multimodal-dialogue?color=green) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


List of **Papers**, **Datasets** and **Code Repositories** for open-domain multimodal dialogue. This repo contains a majority of research works in the multimodal dialogue (M.M.D) field, but it still may not encompass all the noteworthy works (especially those in 2023 and related to LLMs, which will be updated later). 

> This repo is under W.I.P. Please feel free to open issues and make PRs!


## 🗃 Datasets
- Visual Dialog, [[CVPR 2017]](https://arxiv.org/abs/1611.08669) [[data]](https://visualdialog.org/) [[code]](https://github.com/batra-mlp-lab/visdial)
- Image-Grounded Conversations: Multimodal Context for Natural Question and Response Generation, [[IJCNLP 2017]]((https://aclanthology.org/I17-1047.pdf)) [[data]](https://www.microsoft.com/en-us/download/details.aspx?id=55324&751be11f-ede8)
<!-- - Towards building large scale multimodal domain-aware conversation systems, [[arXiv 2017]](https://arxiv.org/pdf/1704.00200.pdf) [[AAAI 2018]](https://dl.acm.org/doi/pdf/10.5555/3504035.3504121) [[data]](https://amritasaha1812.github.io/MMD/download/) [[code]](https://github.com/amritasaha1812/MMD_Code) -->
- MELD: A Multimodal Multi-Party Dataset for Emotion Recognition in Conversations, [[arXiv 2018]](https://arxiv.org/pdf/1810.02508v4.pdf) [[ACL 2019]](https://aclanthology.org/P19-1050.pdf) [[data]](https://affective-meld.github.io/) [[code]](https://github.com/declare-lab/MELD/)
- Image Chat: Engaging Grounded Conversations, [[arXiv 2018]](https://arxiv.org/pdf/1811.00945.pdf) [[ACL 2020]](https://aclanthology.org/2020.acl-main.219.pdf) [[data & code]](https://parl.ai/projects/image_chat/)
- OpenViDial: A Large-Scale, Open-Domain Dialogue Dataset with Visual Context, [[arXiv 2020]]((https://arxiv.org/pdf/2012.15015.pdf)) [[data & code]](https://github.com/ShannonAI/OpenViDial)
- OpenViDial 2.0: A Larger-Scale, Open-Domain Dialogue Generation Dataset with Visual Contexts, [[arXiv 2021]](https://arxiv.org/pdf/2109.12761.pdf) [[data & code]](https://github.com/ShannonAI/OpenViDial)
- MMChat: Multi-Modal Chat Dataset on Social Media, [[arXiv 2021]](https://arxiv.org/pdf/2108.07154.pdf) [[LREC 2022]](https://aclanthology.org/2022.lrec-1.621.pdf) [[data & code]](https://github.com/silverriver/MMChat)
- Towards Expressive Communication with Internet Memes: A New Multimodal Conversation Dataset and Benchmark, [[arXiv 2021]](https://arxiv.org/pdf/2109.01839.pdf) [[data & code]](https://github.com/lizekang/DSTC10-MOD)
- PhotoChat: A Human-Human Dialogue Dataset with Photo Sharing Behavior for Joint Image-Text Modeling, [[ACL 2021]](https://aclanthology.org/2021.acl-long.479.pdf) [[data]](https://github.com/google-research/google-research/tree/master/multimodalchat/)
- MMConv: An Environment for Multimodal Conversational Search across Multiple Domains, [[SIGIR 2021]](https://dl.acm.org/doi/pdf/10.1145/3404835.3462970) [[data & code]](https://github.com/liziliao/MMConv)
- Constructing Multi-Modal Dialogue Dataset by Replacing Text with Semantically Relevant Images, [[ACL 2021]](https://aclanthology.org/2021.acl-short.113/) [[arXiv 2021]](https://arxiv.org/abs/2107.08685) [[data & code]](https://github.com/shh1574/multi-modal-dialogue-dataset)
- MSCTD: A Multimodal Sentiment Chat Translation Dataset, [[ACL 2022]](https://aclanthology.org/2022.acl-long.186.pdf) [[data & code]](https://github.com/XL2248/MSCTD)
- M3ED: Multi-modal Multi-scene Multi-label Emotional Dialogue Database, [[ACL 2022]](https://aclanthology.org/2022.acl-long.391.pdf) [[data & code]](https://github.com/aim3-ruc/rucm3ed)
- MMDialog: A Large-scale Multi-turn Dialogue Dataset Towards Multi-modal Open-domain Conversation, [[arXiv 2022]](https://arxiv.org/pdf/2211.05719v1.pdf) [[data & code]](https://github.com/victorsungo/MMDialog)
- DialogCC: Large-scale Multi-Modal Dialogue Dataset, [[arXiv 2022]](https://arxiv.org/pdf/2212.04119.pdf) [[data & code]](https://github.com/passing2961/DialogCC)
<!-- - LiveChat: A Large-Scale Personalized Dialogue Dataset Automatically Constructed from Live Streaming, [[ACL 2023]](https://aclanthology.org/2023.acl-long.858.pdf) [[arXiv 2023]](https://arxiv.org/pdf/2306.08401.pdf) [[data & code]](https://github.com/gaojingsheng/LiveChat) -->
- TikTalk: A Multi-Modal Dialogue Dataset for Real-World Chitchat, [[arXiv 2023]](https://arxiv.org/pdf/2301.05880.pdf) [MM 2023] [[data]](https://github.com/RUC-AIMind/TikTalk)



## 🏹 Methods
### VisDial
- Visual Dialog, [[CVPR 2017]](https://arxiv.org/abs/1611.08669) [[data]](https://visualdialog.org/) [[code]](https://github.com/batra-mlp-lab/visdial)
- Are You Talking to Me? Reasoned Visual Dialog Generation Through Adversarial Learning, [[arXiv 2017]](https://arxiv.org/pdf/1711.07613.pdf) [[CVPR 2018]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wu_Are_You_Talking_CVPR_2018_paper.pdf)
- FLIPDIAL: A Generative Model for Two-Way Visual Dialogue, [[arXiv 2018]](https://arxiv.org/pdf/1802.03803.pdf) [[CVPR 2018]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Massiceti_FlipDial_A_Generative_CVPR_2018_paper.pdf)
- Large-Scale Pretraining for Visual Dialog: A Simple State-of-the-Art Baseline, [[arXiv 2019]](https://arxiv.org/pdf/1912.02379.pdf) [[ECCV 2020]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630324.pdf) [[code]](https://github.com/vmurahari3/visdial-bert/)
- VD-BERT: A Unified Vision and Dialog Transformer with BERT, [[arXiv 2020]](https://arxiv.org/pdf/2004.13278.pdf) [[EMNLP 2020]](https://aclanthology.org/2020.emnlp-main.269.pdf) [[code]](https://github.com/salesforce/VD-BERT)
- DMRM: A Dual-channel Multi-hop Reasoning Model for Visual Dialog, [[arXiv 2019]](https://arxiv.org/pdf/1912.08360.pdf) [[AAAI 2020]](https://cdn.aaai.org/ojs/6248/6248-13-9473-1-10-20200516.pdf) [[code]](https://github.com/phellonchen/DMRM)
- Multimodal Incremental Transformer with Visual Grounding for Visual Dialogue Generation, [[arXiv 2021]](https://arxiv.org/pdf/2109.08478.pdf) [[ACL 2021]](https://aclanthology.org/2021.findings-acl.38.pdf)
- Improving Cross-Modal Understanding in Visual Dialog via Contrastive Learning, [[arXiv 2022]](https://arxiv.org/pdf/2204.07302.pdf) [[ICASSP 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9747769)
- VU-BERT: A Unified framework for Visual Dialog, [[arXiv 2022]](https://arxiv.org/pdf/2202.10787.pdf) [[ICASSP 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9746098)



### Image Grounded

##### Session Level
- Image-Grounded Conversations: Multimodal Context for Natural Question and Response Generation, [[IJCNLP 2017]]((https://aclanthology.org/I17-1047.pdf)) [[data]](https://www.microsoft.com/en-us/download/details.aspx?id=55324&751be11f-ede8)
- LiveBot: Generating Live Video Comments Based on Visual and Textual Contexts, [[arXiv 2018]](https://arxiv.org/pdf/1809.04938.pdf) [[AAAI 2019]](https://cdn.aaai.org/ojs/4656/4656-13-7695-1-10-20190707.pdf) [[data & code]](https://github.com/lancopku/livebot)
- Image Chat: Engaging Grounded Conversations, [[arXiv 2018]](https://arxiv.org/pdf/1811.00945.pdf) [[ACL 2020]](https://aclanthology.org/2020.acl-main.219.pdf) [[data & code]](https://parl.ai/projects/image_chat/)
- The Dialogue Dodecathlon: Open-Domain Knowledge and Image Grounded Conversational Agents, [[arXiv 2019]](https://arxiv.org/pdf/1911.03768.pdf) [[ACL 2020]](https://aclanthology.org/2020.acl-main.222.pdf) [[code]](https://parl.ai/projects/dodecadialogue/)
- Multimodal Dialogue Systems via Capturing Context-aware Dependencies of Semantic Elements, [[MM 2020]](https://dl.acm.org/doi/pdf/10.1145/3394171.3413679) [[data & code]](https://github.com/githwd2016/MATE)
- Multi-Modal Open-Domain Dialogue, [[arXiv 2020]](https://arxiv.org/pdf/2010.01082.pdf) [[EMNLP 2021]](https://aclanthology.org/2021.emnlp-main.398.pdf) [[data & code]](https://github.com/facebookresearch/ParlAI/blob/main/parlai/zoo/multimodal_blenderbot/README.md)
- OpenViDial: A Large-Scale, Open-Domain Dialogue Dataset with Visual Context, [[arXiv 2020]]((https://arxiv.org/pdf/2012.15015.pdf)) [[data & code]](https://github.com/ShannonAI/OpenViDial)
- OpenViDial 2.0: A Larger-Scale, Open-Domain Dialogue Generation Dataset with Visual Contexts, [[arXiv 2021]](https://arxiv.org/pdf/2109.12761.pdf) [[data & code]](https://github.com/ShannonAI/OpenViDial)
- Modeling Text-visual Mutual Dependency for Multi-modal Dialog Generation, [[arXiv 2021]](https://arxiv.org/pdf/2105.14445.pdf) [[data & code]](https://github.com/ShannonAI/OpenViDial)
- Maria: A Visual Experience Powered Conversational Agent, [[arXiv 2021]](https://arxiv.org/pdf/2105.13073.pdf) [[ACL 2021]](https://aclanthology.org/2021.acl-long.435.pdf) [[code]](https://github.com/jokieleung/Maria)
- MMChat: Multi-Modal Chat Dataset on Social Media, [[arXiv 2021]](https://arxiv.org/pdf/2108.07154.pdf) [[LREC 2022]](https://aclanthology.org/2022.lrec-1.621.pdf) [[data & code]](https://github.com/silverriver/MMChat)
- Affective Feedback Synthesis Towards Multimodal Text and Image Data, [[arXiv 2022]](https://arxiv.org/pdf/2203.12692.pdf) [[data & code]](https://github.com/MIntelligence-Group/MMFeed)
- PaCE: Unified Multi-modal Dialogue Pre-training with Progressive and Compositional Experts, [[arXiv 2023]](https://arxiv.org/pdf/2305.14839.pdf) [[ACL 2023]](https://aclanthology.org/2023.acl-long.749.pdf) [[code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/pace)

##### Turn Level
- Towards building large scale multimodal domain-aware conversation systems, [[arXiv 2017]](https://arxiv.org/pdf/1704.00200.pdf) [[AAAI 2018]](https://dl.acm.org/doi/pdf/10.5555/3504035.3504121) [[data]](https://amritasaha1812.github.io/MMD/download/) [[code]](https://github.com/amritasaha1812/MMD_Code)
- Improving Context Modelling in Multimodal Dialogue Generation, [[arXiv 2018]](https://arxiv.org/pdf/1810.11955.pdf) [[INLG 2018]](https://aclanthology.org/W18-6514.pdf) [[data & code]](https://github.com/shubhamagarwal92/mmd)
- MELD: A Multimodal Multi-Party Dataset for Emotion Recognition in Conversations, [[arXiv 2018]](https://arxiv.org/pdf/1810.02508v4.pdf) [[ACL 2019]](https://aclanthology.org/P19-1050.pdf) [[data]](https://affective-meld.github.io/) [[code]](https://github.com/declare-lab/MELD/)
- Multimodal Dialog System: Generating Responses via Adaptive Decoders, [[MM 2019]](https://dl.acm.org/doi/pdf/10.1145/3343031.3350923) [[data & code]](https://acmmultimedia.wixsite.com/magic)
- Modality-Transferable Emotion Embeddings for Low-Resource Multimodal Emotion Recognition, [[arXiv 2020]](https://arxiv.org/pdf/2009.09629.pdf) [[AACL 2020]](https://aclanthology.org/2020.aacl-main.30.pdf) [[code]](https://github.com/wenliangdai/Modality-Transferable-MER)
- A non-hierarchical attention network with modality dropout for textual response generation in multimodal dialogue systems, [[arXiv 2021]](https://arxiv.org/pdf/2110.09702.pdf) [[ICASSP 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9746613)
- Constructing Multi-Modal Dialogue Dataset by Replacing Text with Semantically Relevant Images, [[ACL 2021]](https://aclanthology.org/2021.acl-short.113/) [[arXiv 2021]](https://arxiv.org/pdf/2107.08685.pdf) [[data & code]](https://github.com/shh1574/multi-modal-dialogue-dataset)
- Emotion-Aware Multimodal Pre-training for Image-Grounded Emotional Response Generation, [[DASFAA 2022]](https://link.springer.com/chapter/10.1007/978-3-031-00129-1_1) [[code]](https://github.com/araloak/MM-Pre-train)
- DialogCC: Large-scale Multi-Modal Dialogue Dataset, [[arXiv 2022]](https://arxiv.org/pdf/2212.04119.pdf) [[data & code]](https://github.com/passing2961/DialogCC)
- Multimodal Dialog Systems with Dual Knowledge-enhanced Generative Pretrained Language Model, [[arXiv 2022]](https://arxiv.org/pdf/2207.07934.pdf) [[code]](https://multimodaldialog.wixsite.com/website)
- MMDialog: A Large-scale Multi-turn Dialogue Dataset Towards Multi-modal Open-domain Conversation, [[arXiv 2022]](https://arxiv.org/pdf/2211.05719v1.pdf) [[data & code]](https://github.com/victorsungo/MMDialog)
- MSCTD: A Multimodal Sentiment Chat Translation Dataset, [[ACL 2022]](https://aclanthology.org/2022.acl-long.186.pdf) [[data & code]](https://github.com/XL2248/MSCTD)
- M3ED: Multi-modal Multi-scene Multi-label Emotional Dialogue Database, [[ACL 2022]](https://aclanthology.org/2022.acl-long.391.pdf) [[data & code]](https://github.com/aim3-ruc/rucm3ed)



### Multimodal Response
- Towards Expressive Communication with Internet Memes: A New Multimodal Conversation Dataset and Benchmark, [[arXiv 2021]](https://arxiv.org/pdf/2109.01839.pdf) [[data & code]](https://github.com/lizekang/DSTC10-MOD)
- PhotoChat: A Human-Human Dialogue Dataset with Photo Sharing Behavior for Joint Image-Text Modeling, [[ACL 2021]](https://aclanthology.org/2021.acl-long.479.pdf) [[data]](https://github.com/google-research/google-research/tree/master/multimodalchat/)
- An animated picture says at least a thousand words: Selecting Gif-based Replies in Multimodal Dialog, [[arXiv 2021]](https://arxiv.org/pdf/2109.12212.pdf) [[EMNLP 2021]](https://aclanthology.org/2021.findings-emnlp.276.pdf) [[data & code]](https://github.com/xingyaoww/gif-reply)
- Multimodal Dialogue Response Generation, [[arXiv 2021]](https://arxiv.org/pdf/2110.08515.pdf) [[ACL 2022]](https://aclanthology.org/2022.acl-long.204.pdf)
- MMDialog: A Large-scale Multi-turn Dialogue Dataset Towards Multi-modal Open-domain Conversation, [[arXiv 2022]](https://arxiv.org/pdf/2211.05719v1.pdf) [[data & code]](https://github.com/victorsungo/MMDialog)



### Others
- Open Domain Dialogue Generation with Latent Images, [[arXiv 2020]](https://arxiv.org/pdf/2004.01981v1.pdf) [[AAAI 2021]](https://cdn.aaai.org/ojs/17675/17675-13-21169-1-2-20210518.pdf)
- Text is NOT Enough: Integrating Visual Impressions into Open-domain Dialogue Generation, [[arXiv 2021]](https://arxiv.org/pdf/2109.05778.pdf) [[MM 2021]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475568)
- A Survey on Multimodal Dialogue Systems: Recent Advances and New Frontiers, [[AEMCSE 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9948337)
- Gated Multimodal Fusion with Contrastive Learning for Turn-taking Prediction in Human-robot Dialogue, [[arXiv 2022]](https://arxiv.org/pdf/2204.10172.pdf) [[ICASSP 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9747056)



<img src="http://profile-counter.glitch.me/awesome-multimodal-dialogue/count.svg" alt="visit_count" style="width: 30%; text-align: center; margin-left: 40%">

