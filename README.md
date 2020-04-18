# ICASSP2020

## Speech Processing

### TU1.Poster A: Adversarial/Discriminative Training and Spoofing for Speaker Recognition

### WE1.Poster A: Deep Speaker Recognition Models

- [x] Qian-Bei Hong, Chung-Hsien Wu, Hsin-Min Wang, Chien-Lin Huang. *Statistics Pooling Time Delay Neural Network Based on X-Vector for Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054350)]
  - `TI-SV` `VoxCeleb` `SITW`
  -  Concat the outputs of local statistics pooling in each TDNN layer.

### TH1.Poster A: Speaker Diarization and Characterization

### TH3.Lecture 3: Speech Recognition: Representations and Embeddings

- [ ] Herman Kamper, Yevgen Matusevych, Sharon Goldwater. *Multilingual Acoustic Word Embedding Models for Processing Zero-resource Languages.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054202)]

- [ ] Andy T. Liu, Shu-wen Yang, Po-Han Chi, Po-chun Hsu, Hung-yi Lee. *Mockingjay: Unsupervised Speech Representation Learning with Deep Bidirectional Transformer Encoders.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054458)]

- [ ] Öykü Deniz Köse, Murat Saraçlar. *Recurrent Neural Audiovisual Word Embeddings for Synchronized Speech and Real-Time Mri.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053322)]

- [ ] Shaoshi Ling, Yuzong Liu, Julian Salazar, Katrin Kirchhoff. *Deep Contextualized Acoustic Representations for Semi-Supervised Speech Recognition.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053176)]

- [ ] Chung-Yi Li, Pei-Chieh Yuan, Hung-Yi Lee. *What Does a Network Layer Hear? Analyzing Hidden Representations of End-to-End ASR Through Speech Synthesis.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054675)]

- [ ] Jennifer Drexler, James Glass. *Learning a Subword Inventory Jointly with End-to-End Automatic Speech Recognition.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053736)]

### TH3.Lecture 6: Speaker Recognition/Identification/Verification

- [ ] Sung-Hyun Yoon, Ha-Jin Yu. *Multiple Points Input For Convolutional Neural Networks in Replay Attack Detection.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053303)]

- [ ] Youzhi Tu, Man-Wai Mak, Jen-Tzung Chien. *Information Maximized Variational Domain Adversarial Learning for Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053735)]

- [ ] Yexin Yang, Shuai Wang, Xun Gong, Yanmin Qian, Kai Yu. *Text Adaptation for Speaker Verification with Speaker-Text Factorized Embeddings.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054333)]

- [x] Rongjin Li, Dongpeng Chen, Weibin Zhang. *VoiceAI Systems to NIST SRE19 Evaluation: Robust Speaker Recognition on Conversational Telephone Speech.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054624)]
  - `SI-SV` `SRE` `Fusion` `Domain mismatch`
  - FBank, MFCC, PLP + pitch
  - NN-based VAD
  - E-TDNN, F-TDNN, LSTM
  - AS-Norm, adapted G-PLDA

- [ ] Zhiming Wang, Kaisheng Yao, Xiaolong Li, Shuo Fang. *Multi-Resolution Multi-Head Attention in Deep Speaker Embedding.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053217)]

- [ ] Danwei Cai, Weicheng Cai, Ming Li. *Within-Sample Variability-Invariant Loss for Robust Speaker Recognition Under Noisy Environments.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053407)]

### FR1.Poster C: Speaker Recognition Systems, Data and Features

- [x] Daniel Garcia-Romero, Alan McCree, David Snyder, Gregory Sell. *JHU-HLTCOE System for the VoxSRC Speaker Recognition Challenge.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053209)]
  - `SI-SV` `VoxCeleb` `Fusion`
  - FBank, MFCC
  - E-TDNN, F-TDNN
  - Softmax, AAM-Softmax, PLDA-Softmax, Meta-learning Softmax
  - Cosine, G-PLDA

- [x] Hao Lu, Jianfeng Zhou, Miao Zhao, Wendian Lei, Qingyang Hong, Lin Li. *XMU-TS Systems for NIST SRE19 CTS Challenge.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053080)]
  - `SI-SV` `NIST` `Fusion` `Domain mismatch`
  - FBank, MFCC, PLP + pitch
  - TDNN, E-TDNN, F-TDNN, ResNet
  - Employ length normalization, centering, whitening and LDA before domain adapted PLDA scoring for eliminating domain mismatch.
  - AS-Norm

- [x] Yue Fan, Jiawen Kang, Lantian Li, Kaicheng Li, Haolin Chen, Sitong Cheng, Pengyuan Zhang, Ziya Zhou, Yunqi Cai, Dong Wang. *CN-Celeb: A Challenging Chinese Speaker Recognition Dataset.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054017)]
  - `SI-SV` `CN-Celeb`
  - 1,000 Chinese speakers, 130,109 utterances, 273.73 hours.
