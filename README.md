# ICASSP2020

## Speech Processing

### SPE-P1: Adversarial/Discriminative Training and Spoofing for Speaker Recognition

### SPE-P5: Deep Speaker Recognition Models

- [x] Sarthak Yadav, Atul Rai. *Frequency and Temporal Convolutional Attention for Text-independent Speaker Recognition.* [[ICASP 2020](https://ieeexplore.ieee.org/document/9054440/)]
  - `TI-SV` `VoxCeleb` `CBAM`
  - CABM in CV: channel attention and spatial attention.
  - Frequency attention and temporal attention.

- [x] Naohiro Tawara, Atsunori Ogawa, Tomoharu Iwata, Marc Delcroix, Tetsuji Ogawa. *Frame-level Phoneme-invariant Speaker Embedding for Text-independent Speaker Recognition on Extremely Short Utterances.* [[ICASP 2020](https://ieeexplore.ieee.org/document/9053871/)]
  - `TI-SV` `LibriSpeech`
  - Phoneme information may help to find discriminating phonemes, but phoneme-aware training perform badly for extremely short utterances.
  - Adopt adversarial training (reverse gradient) to remove phonetic information in segment level embedding.

- [x] Tom Ko, Yangbin Chen, Qing Li. *Prototypical Networks for Small Footprint Text-independent Speaker Verification.* [[ICASP 2020](https://ieeexplore.ieee.org/document/9054471/)]
  - `TI-SV` `NIST SRE` `Switchboard` `Few-shot` `Prototypical`
  - Randomly select N classes and K+1 samples for each class, split them into the support set (K) and the query set (1).
  - The prototype of each class is defined as the mean vector of the K samples in the support set.

- [ ] Chen Chen, Jiqing Han. *TDMF: Task-driven Multilevel Framework for End-to-end Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9052957/)]

- [x] Bin Gu, Wu Guo, Lirong Dai, Jun Du. *An Improved Deep Neural Network for Modeling Speaker Characteristics at Different Temporal Scales.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054151)]
  - `TI-SV` `NIST SRE` `Multiscale` `Attentive pooling (Baum-Welch)`
  - Multiple 1D Conv with different dilation sizes (channel concatenation)
  - Utilize Baum-Welch statistics (for creating extra weights) in attentive pooling

- [ ] Zhongxin Bai, Xiao-Lei Zhang，Jingdong Chen. *Partial AUC Optimization based Deep Speaker Embeddings with Class-center Learning for Text-independent Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053674/)]

- [ ] Victoria Mingote, Antonio Miguel, Dayana Ribas, Alfonso Ortega, Eduardo Lleida. *Knowledge Distillation and Random Erasing Data Augmentation for Text-dependent Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053153)]

- [ ] Arsha Nagrani Joon Son Chung, Samuel Albanie, Andrew Zisserman. *Disentangled Speech Embeddings Using Cross-model Self-supervision.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054057)]

- [ ] Yong Zhao, Tianyan Zhou, Zhuo Chen, Jian Wu. *Improved Deep CNN Networks with Long Temporal Context for Text-independent Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053767)]

- [ ] Weiwei Lin, Man-Mai Mak, Na Li, Dan Su, Dong Yu. *Multi-level Deep Neural Network Adaptation for Speaker Verification Using MMD and Consistency Regularization.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054134)]

- [ ] Siddharth Sigtia, Erik Marchi, Sachin Kajarekar, Devang Naik, John Bridle. *Multi-task Learning for Speaker Verification and Voice Trigger Detection.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054760)]

- [x] Qian-Bei Hong, Chung-Hsien Wu, Hsin-Min Wang, Chien-Lin Huang. *Statistics Pooling Time Delay Neural Network Based on X-Vector for Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054350)]
  - `TI-SV` `VoxCeleb` `SITW`
  -  Concatenate the outputs of local statistics pooling in each TDNN layer.

### SPE-P10: Speaker Diarization and Characterization

### SPE-L13: Speech Recognition: Representations and Embeddings

- [ ] Herman Kamper, Yevgen Matusevych, Sharon Goldwater. *Multilingual Acoustic Word Embedding Models for Processing Zero-resource Languages.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054202)]

- [ ] Andy T. Liu, Shu-wen Yang, Po-Han Chi, Po-chun Hsu, Hung-yi Lee. *Mockingjay: Unsupervised Speech Representation Learning with Deep Bidirectional Transformer Encoders.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054458)]

- [ ] Öykü Deniz Köse, Murat Saraçlar. *Recurrent Neural Audiovisual Word Embeddings for Synchronized Speech and Real-Time Mri.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053322)]

- [ ] Shaoshi Ling, Yuzong Liu, Julian Salazar, Katrin Kirchhoff. *Deep Contextualized Acoustic Representations for Semi-Supervised Speech Recognition.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053176)]

- [ ] Chung-Yi Li, Pei-Chieh Yuan, Hung-Yi Lee. *What Does a Network Layer Hear? Analyzing Hidden Representations of End-to-End ASR Through Speech Synthesis.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054675)]

- [ ] Jennifer Drexler, James Glass. *Learning a Subword Inventory Jointly with End-to-End Automatic Speech Recognition.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053736)]

### SPE-L14: Speaker Recognition/Identification/Verification

- [ ] Sung-Hyun Yoon, Ha-Jin Yu. *Multiple Points Input For Convolutional Neural Networks in Replay Attack Detection.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053303)]

- [ ] Youzhi Tu, Man-Wai Mak, Jen-Tzung Chien. *Information Maximized Variational Domain Adversarial Learning for Speaker Verification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053735)]

- [ ] Yexin Yang, Shuai Wang, Xun Gong, Yanmin Qian, Kai Yu. *Text Adaptation for Speaker Verification with Speaker-Text Factorized Embeddings.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054333)]

- [x] Rongjin Li, Dongpeng Chen, Weibin Zhang. *VoiceAI Systems to NIST SRE19 Evaluation: Robust Speaker Recognition on Conversational Telephone Speech.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054624)]
  - `SI-SV` `NIST SRE` `Fusion` `Domain mismatch`
  - FBank, MFCC, PLP + pitch
  - NN-based VAD
  - E-TDNN, F-TDNN, LSTM
  - AS-Norm, adapted G-PLDA

- [x] Zhiming Wang, Kaisheng Yao, Xiaolong Li, Shuo Fang. *Multi-Resolution Multi-Head Attention in Deep Speaker Embedding.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053217)]
  - `SI-SV` `VoxCeleb` `Attentive pooling`
  - Multi-resolution: scaling the input of softmax function (which smooths the curve of attentive weights).
  - This paper points out that "Deep speaker recognition: Modular or monolithic?" (in INTERSPEECH 2019) might used the VoxCeleb1 test set in training.

- [ ] Danwei Cai, Weicheng Cai, Ming Li. *Within-Sample Variability-Invariant Loss for Robust Speaker Recognition Under Noisy Environments.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053407)]

### SPE-P18: Speaker Recognition Systems, Data and Features

- [x] Daniel Garcia-Romero, Alan McCree, David Snyder, Gregory Sell. *JHU-HLTCOE System for the VoxSRC Speaker Recognition Challenge.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053209)]
  - `SI-SV` `VoxCeleb` `Fusion`
  - FBank, MFCC
  - E-TDNN, F-TDNN
  - Softmax, AAM-Softmax, PLDA-Softmax, Meta-learning Softmax
  - Cosine, G-PLDA

- [x] Hao Lu, Jianfeng Zhou, Miao Zhao, Wendian Lei, Qingyang Hong, Lin Li. *XMU-TS Systems for NIST SRE19 CTS Challenge.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053080)]
  - `SI-SV` `NIST SRE` `Fusion` `Domain mismatch`
  - FBank, MFCC, PLP + pitch
  - TDNN, E-TDNN, F-TDNN, ResNet
  - Employ length normalization, centering, whitening and LDA before domain adapted PLDA scoring for eliminating domain mismatch.
  - AS-Norm

- [x] Qian-Bei Hong, Chung-Hsien Wu, Hsin-Min Wang, Chien-Lin Huang. *Combining Deep Embeddings of Acoustic and Articulatory Features for Speaker Identification.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9053640/)]
  - Utilize articulatory features instead of directly using phonemes.

- [x] Yue Fan, Jiawen Kang, Lantian Li, Kaicheng Li, Haolin Chen, Sitong Cheng, Pengyuan Zhang, Ziya Zhou, Yunqi Cai, Dong Wang. *CN-Celeb: A Challenging Chinese Speaker Recognition Dataset.* [[ICASSP 2020](https://ieeexplore.ieee.org/document/9054017)]
  - `SI-SV` `CN-Celeb`
  - 1,000 Chinese speakers, 130,109 utterances, 273.73 hours.
