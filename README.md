# Image Forgery Detection & Localization

<p align="center">
  <b>A curated reading list for image manipulation, forgery detection, and localization.</b><br>
  Papers are grouped by task and ordered roughly from recent to earlier work. Links point to papers, project pages, or code when available.
</p>

> **Scope:** This list focuses on image forgery and manipulation. Video-only forgery and face-only deepfake detection are separate topics and are not mixed into the core categories. Entries retained from the original list are marked where appropriate by their original links; this list is community-curated and may contain preprints.

## Contents

- [General image manipulation detection and localization](#general-image-manipulation-detection-and-localization)
- [AIGC and generative image forensics](#aigc-and-generative-image-forensics)
- [Image splicing and compositing](#image-splicing-and-compositing)
- [Copy-move forgery](#copy-move-forgery)
- [Image inpainting and local editing](#image-inpainting-and-local-editing)
- [Document and tampered text detection](#document-and-tampered-text-detection)
- [Resources](#resources)

## General image manipulation detection and localization

Methods that detect or localize image manipulations across multiple edit types.

| Paper | Venue / year | Links |
|---|---|---|
| From Detection to Localization: A Unified Forensics Framework for Fully Synthetic and Tampered Images | arXiv, 2026 | [Paper](https://arxiv.org/abs/2609.02640) · [Code](https://github.com/anngal01/From-Detection-to-Localization-A-Unified-Forensics-Framework-for-Fully-Synthetic-and-Tampered-Images) |
| A Lottery Ticket Hypothesis Approach with Sparse Fine-tuning and MAE for Image Forgery Detection and Localization | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-33192-2025-02-25) |
| Mesoscopic Insights: Orchestrating Multi-Scale & Hybrid Architecture for Image Manipulation Localization | AAAI, 2025 | [Paper](https://arxiv.org/abs/2412.13753) · [Code](https://github.com/scu-zjz/Mesorch) |
| SAFIRE: Segment Any Forged Image Region | AAAI, 2025 | [Paper](https://arxiv.org/abs/2412.08197) |
| M²RL-Net: Multi-View and Multi-Level Relation Learning Network for Weakly-Supervised Image Forgery Detection | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-32501-2025-02-25) |
| Reinforced Multi-teacher Knowledge Distillation for Efficient General Image Forgery Detection and Localization | AAAI, 2025 | [Paper](https://arxiv.org/abs/2504.05224) |
| MUN: Image Forgery Localization Based on M³ Encoder and UN Decoder | AAAI, 2025 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32606) · [Code](https://github.com/MrHuan3/MUN) |
| Loupe: A Generalizable and Adaptive Framework for Image Forgery Detection | IJCAI, 2025 | [Paper](https://arxiv.org/abs/2506.16819) · [Code](https://github.com/Kamichanw/Loupe) |
| M2SFormer: Multi-Spectral and Multi-Scale Attention with Edge-Aware Difficulty Guidance for Image Forgery Localization | ICCV, 2025 | [Paper](https://arxiv.org/abs/2506.20922) |
| Pixel-Inconsistency Modeling for Image Manipulation Localization | 2025 | [Paper](https://ieeexplore.ieee.org/abstract/document/10883001) · [Code](https://github.com/ChenqiKONG/PIM) |
| A Lightweight and Effective Image Tampering Localization Network with Vision Mamba | SPL, 2025 | [Paper](https://arxiv.org/abs/2502.09941) · [Code](https://github.com/multimediaFor/ForMa) |
| SUMI-IFL: An Information-Theoretic Framework for Image Forgery Localization with Sufficiency and Minimality Constraints | 2024 | [Paper](https://arxiv.org/abs/2412.09981) |
| Image Forgery Localization with State Space Models | 2024 | [Paper](https://arxiv.org/abs/2412.11214) · [Code](https://github.com/multimediaFor/LoMa) |
| FakeShield: Explainable Image Forgery Detection and Localization via Multi-modal Large Language Models | ICLR, 2025 | [Paper](https://arxiv.org/abs/2410.02761) · [Code](https://github.com/zhipeixu/FakeShield) |
| Exploring Multi-view Pixel Contrast for General and Robust Image Forgery Localization | 2025 | [Paper](https://arxiv.org/abs/2406.13565) · [Code](https://github.com/multimediaFor/MPC) |
| Progressive Feedback-Enhanced Transformer for Image Forgery Localization | 2023 | [Paper](https://arxiv.org/abs/2311.08910) · [Code](https://github.com/multimediaFor/ProFact) |
| TruFor: Leveraging All-Round Clues for Trustworthy Image Forgery Detection and Localization | CVPR, 2023 | [Paper](https://arxiv.org/abs/2212.10957) · [Project](https://grip-unina.github.io/TruFor) |
| Effective Image Tampering Localization via Enhanced Transformer and Co-attention Fusion | ICASSP, 2024 | [Paper](https://arxiv.org/abs/2309.09306) · [Code](https://github.com/multimediaFor/EITLNet) |
| Image Tampering Localization Using a Dense Fully Convolutional Network | TIFS, 2021 | [Paper](https://ieeexplore.ieee.org/document/9393396) · [Code](https://github.com/ZhuangPeiyu/Dense-FCN-for-tampering-localization) |

## AIGC and generative image forensics

Distinguishing synthetic images from camera imagery, detecting generative edits, and localizing AI-generated regions.

| Paper | Venue / year | Links |
|---|---|---|
| Unifying Semantic Priors and High-Frequency Traces: Enhancing V-JEPA with Mixture-of-Experts for Robust Synthetic Image Forensics | arXiv, 2026 | [Paper](https://arxiv.org/abs/2609.16778) · [Code](https://github.com/ALCOR-Lab-DIAG/MoE-JEPA) |
| Code-in-the-Loop Forensics: Agentic Tool Use for Image Forgery Detection | arXiv, 2025 | [Paper](https://arxiv.org/abs/2512.16300) |
| WildFake: A Large-Scale and Hierarchical Dataset for AI-Generated Images Detection | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-32363-2025-02-25) |
| Towards Universal AI-Generated Image Detection by Variational Information Bottleneck Network | CVPR, 2025 | [Paper](https://cvpr.thecvf.com/virtual/2025/poster/35206) |
| A Bias-Free Training Paradigm for More General AI-generated Image Detection | CVPR, 2025 | [Paper](https://cvpr.thecvf.com/virtual/2025/poster/34882) |
| Community Forensics: Using Thousands of Generators to Train Fake Image Detectors | CVPR, 2025 | [Paper](https://cvpr.thecvf.com/virtual/2025/poster/32740) |
| Any-Resolution AI-Generated Image Detection by Spectral Learning | CVPR, 2025 | [Paper](https://cvpr.thecvf.com/virtual/2025/poster/33589) |
| OpenSDI: Spotting Diffusion-Generated Images in the Open World | 2025 | [Paper](https://arxiv.org/abs/2503.19653) · [Code](https://github.com/iamwangyabin/OpenSDI) |
| Zooming In on Fakes: A Novel Dataset for Localized AI-Generated Image Detection with Forgery Amplification Approach | 2025 | [Paper](https://arxiv.org/abs/2504.11922) · [Code](https://github.com/clpbc/BR-Gen) |
| Aligned Datasets Improve Detection of Latent Diffusion-Generated Images | ICLR, 2025 | [Paper](https://iclr.cc/virtual/2025/poster/28964) |
| FakeDiffer: Distributional Disparity Learning on Differentiated Reconstruction for Face Forgery Detection | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-32809-2025-02-25) |
| Transfer Learning of Real Image Features with Soft Contrastive Loss for Fake Image Detection | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-34826-2025-02-25) |
| Critical Forgetting-Based Multi-Scale Disentanglement for Deepfake Detection | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-32021-2025-02-25) |
| Frequency-Aware Deepfake Detection: Improving Generalizability through Frequency Space Learning | 2024 | [Paper](https://arxiv.org/abs/2403.07240) · [Code](https://github.com/chuangchuangtan/freqnet-deepfakedetection) |

## Image splicing and compositing

| Paper | Venue / year | Links |
|---|---|---|
| Deep Image Composition Meets Image Forgery | 2024 | [Paper](https://arxiv.org/abs/2404.02897) · [Dataset](https://github.com/99eren99/DIS25k) |
| Image Splicing Localization Using a Multi-Task Fully Convolutional Network | 2018 | [Paper](https://arxiv.org/abs/1709.02016) · [Code](https://github.com/namtpham/image_tampering_detection_references) |
| Multi-scale Attention Context-aware Network for Detection and Localization of Image Splicing | Applied Intelligence, 2023 | [Paper](https://link.springer.com/article/10.1007/s10489-022-04421-3) |

## Copy-move forgery

| Paper | Venue / year | Links |
|---|---|---|
| Copy-Move Forgery Detection and Question Answering for Remote Sensing Image | 2024 | [Paper](https://arxiv.org/abs/2412.02575) · [Code](https://github.com/shenyedepisa/RSCMQA) |
| Object-level Copy-Move Forgery Image Detection based on Inconsistency Mining | 2024 | [Paper](https://arxiv.org/abs/2404.00611) |
| CMCF-Net: An End-to-End Context Multiscale Cross-Fusion Network for Robust Copy-Move Forgery Detection | TMM, 2024 | [Paper](https://doi.org/10.1109/TMM.2023.3345160) |

## Image inpainting and local editing

| Paper | Venue / year | Links |
|---|---|---|
| Training-Free Image Manipulation Localization Using Diffusion Models | AAAI, 2025 | [Paper](https://www.paperdigest.org/paper/?paper_id=aaai-33126-2025-02-25) |
| TGIF: Text-Guided Inpainting Forgery Dataset | 2024 | [Paper](https://arxiv.org/abs/2407.11566) · [Dataset](https://github.com/IDLabMedia/tgif-dataset) |
| Image Editing Detection in the Era of Generative AI Revolution | ACM MM, 2024 | [Paper](https://arxiv.org/abs/2311.17953) · [Code](https://github.com/ICTMCG/GRE) |

## Document and tampered text detection

### Scene text manipulation

| Paper | Venue / year | Links |
|---|---|---|
| TextShield-R1: Reinforced Reasoning for Tampered Text Detection | AAAI, 2026 | [Paper](https://arxiv.org/abs/2602.19828) · [Code](https://github.com/qcf-568/TextShield) |
| Revisiting Tampered Scene Text Detection in the Era of Generative AI | ICCV, 2025 | [Paper](https://arxiv.org/abs/2407.21422) · [Code](https://github.com/qcf-568/OSTF) |
| Explainable Tampered Text Detection via Multimodal Large Models | 2024 | [Paper](https://arxiv.org/abs/2412.14816) |
| Enhancing Tampered Text Detection through Frequency Feature Fusion and Decomposition | ECCV, 2024 | [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04834.pdf) |
| Generalized Tampered Scene Text Detection in the Era of Generative AI | 2024 | [Paper](https://arxiv.org/abs/2407.21422) |
| A Two-Stage Dual-Path Framework for Text Tampering Detection and Recognition | 2024 | [Paper](https://arxiv.org/abs/2402.13545) |
| Toward Real Text Manipulation Detection: New Dataset and New Solution | Pattern Recognition, 2025 | [Paper](https://arxiv.org/abs/2312.06934) · [Code](https://github.com/DrLuo/RTM) |
| Towards Robust Tampered Text Detection in Document Image: New Dataset and New Solution | CVPR, 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Qu_Towards_Robust_Tampered_Text_Detection_in_Document_Image_New_Dataset_CVPR_2023_paper.pdf) · [Code](https://github.com/qcf-568/DocTamper) |

### Document image localization and benchmarks

| Paper | Venue / year | Links |
|---|---|---|
| DOCFORGE-BENCH: A Comprehensive Benchmark for Document Forgery Detection and Analysis | 2026 | [Paper](https://arxiv.org/abs/2603.01433) |
| RealDTT: Towards a Comprehensive Real-World Dataset for Tampered Text Detection | IJCV, 2025 | [Paper](https://link.springer.com/article/10.1007/s11263-025-02515-2) · [Dataset](https://github.com/edmundhaohao/RealDTT) |
| ADCD-Net: Robust Document Image Forgery Localization via Adaptive DCT Feature and Hierarchical Content Disentanglement | ICCV, 2025 | [Paper](https://arxiv.org/abs/2507.16397) · [Code](https://github.com/KAHIMWONG/ADCD-Net) |
| FantasyID: A Dataset for Detecting Digital Manipulations of ID Documents | IJCB, 2025 | [Paper](https://arxiv.org/abs/2507.20808) · [Dataset](https://www.idiap.ch/paper/fantasyid) |
| DITL²: Dual-Stage Invariance Transfer Learning for Generalizable Document Image Tampering Localization | ACM MM, 2025 | Paper link not provided in [reference list](https://github.com/greatzh/Papers) |
| Document Image Forgery Detection and Localization in Desensitization Scenarios | Signal Processing: Image Communication, 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S0165168425002373) |
| Cross-Attention Based Two-Branch Networks for Document Image Forgery Localization in the Metaverse | TOMM, 2025 | [Paper](https://doi.org/10.1145/3686158) |
| Delving into Adversarial Robustness on Document Tampering Localization | ECCV, 2024 | [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08224.pdf) |
| CTP-Net: Character Texture Perception Network for Document Image Forgery Localization | 2023 | [Paper](https://arxiv.org/abs/2308.02158) · [Code](https://github.com/FCTMdataset/FCTM) |
| Progressive Supervision for Tampering Localization in Document Images | ICONIP, 2023 | [Paper](https://link.springer.com/chapter/10.1007/978-981-99-8184-7_11) |
| Image Generation and Learning Strategy for Deep Document Forgery Detection | 2023 | [Paper](https://arxiv.org/abs/2311.03650) |
| Document Forgery Detection in the Context of Double JPEG Compression | ICPR, 2022 | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-37745-7_5) |

### Signatures and identity documents

| Paper | Venue / year | Links |
|---|---|---|
| Handwritten Signature Verification via Multimodal Consistency Learning | TIFS, 2025 | [Paper](https://ieeexplore.ieee.org/document/10950350/) |
| Image-based Freeform Handwriting Authentication with Energy-oriented Self-Supervised Learning | TMM, 2024 | [Paper](https://arxiv.org/abs/2408.09676) |
| SigScatNet: A Siamese + Scattering Based Deep Learning Approach for Signature Forgery Detection | 2023 | [Paper](https://arxiv.org/abs/2311.05579) |
| Forgery-free Signature Verification with Stroke-aware Cycle-consistent Generative Adversarial Network | Neurocomputing, 2022 | [Paper](https://doi.org/10.1016/j.neucom.2022.08.017) · [Code](https://github.com/KAKAFEI123/Stroke-cCycleGAN) |

## Resources

- [greatzh/Papers — Image Tampering](https://github.com/greatzh/Papers)
- [greatzh/Papers — Tamper Text in Detection](https://github.com/greatzh/Papers)
- [MIC-ImageForensics/Image-Forgery](https://github.com/MIC-ImageForensics/Image-Forgery)

Contributions and corrections are welcome. Please include the paper link, publication/preprint year, and code or dataset link when available.
