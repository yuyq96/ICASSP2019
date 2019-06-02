# ICASSP 2019

## SLP-L1: End-to-end Speech Recognition I: General Topics

- [x] Bo Li, Yu Zhang, Tara Sainath, Yonghui Wu, William Chan. *Bytes Are All You Need: End-to-end Multilingual Speech Recognition and Synthesis with Bytes.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682674)] [[CoRR2018](https://arxiv.org/abs/1811.09021)]
  - `ASR` `TTS` `Multilingual`
  - Use Unicode bytes instead of characters, sub-words or words as the unit of text representation.
  - ASR: outperform grapheme models in both multilingual and monolingual models.
  - TTS: match the performance of monolingual grapheme models.
  - Small vocabulary size (256 for UTF-8) helps to build compact models.

- [ ] Shuo-Yiin Chang, Rohit Prabhavalkar, Yanzhang He, Tara N. Sainath, Gabor Simko. *Joint Endpointing and Decoding with End-to-end Models.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683109)]

- [x] Changhao Shan, Chao Weng, Guangsen Wang, Dan Su, Min Luo, Dong Yu, Lei Xie. *Component Fusion: Learning Replaceable Language Model Component for End-to-end Speech Recognition System.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682490)]
  - `ASR` `LM Fushion` `Component Fushion`
  - Use Component Fusion to incorporate externally trained LM into an attention-based ASR system.
  - Make use of the large amount of text corpora.
  - Concatenate the hidden states of ASR model and LM (unlike Cold Fushion: first, train the ASR model jointly with a fixed LM pre-trained on transcript text, then replace the LM with another one which is trained on a larger text corpora or out-of-domain text during decoding).
  - Achieve better performance in both in-domain and out-of-domain senary.

- [ ] Stefan Braun, Shih-Chii Liu. *Parameter Uncertainty for End-to-end Speech Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683066)]

- [ ] Shane Settle, Kartik Audhkhasi, Karen Livescu, Michael Picheny. *Acoustically Grounded Word Embeddings for Improved Acoustics-to-Word Speech Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682903)] [[CoRR 2019](http://arxiv.org/abs/1903.12306)]

- [ ] Murali Karthick Baskar, Lukás Burget, Shinji Watanabe, Martin Karafiát, Takaaki Hori, Jan Honza Cernocký. *Promising Accurate Prefix Boosting for sequence-to-sequence ASR.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682782)] [[CoRR 2018](http://arxiv.org/abs/1811.02770)]

## SLP-P2: Speaker Verification and Identification I

- [ ] Mahesh Kumar Nandwana, Mitchell McLaren, Luciana Ferrer, Diego Castan, Aaron Lawson. *Analysis and Mitigation of Vocal Effort Variations in Speaker Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683881)]

- [x] Johan Rohdin, Themos Stafylakis, Anna Silnova, Hossein Zeinali, Lukáš Burget, Oldřich PlchotSpeaker. *Speaker Verification Using End-to-End Adversarial Language Adaptation.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683616)]
  - `TI-SV` `Domain Adaption` `GAN` `Maximum Mean Discrepancy (MMD)` `Wasserstein Distance`
  - Generator: minimize Wasserstein distance and classification loss.
  - Discriminator: maximize Wasserstein distance (and minimize gradient penalty loss for 1-Lipschitz constraint).

- [ ] Buddhi Wickramasinghe, Eliathamby Ambikairajah, Julien Epps, Vidhyasaharan Sethu, Haizhou Li. *Auditory Inspired Spatial Differentiation for Replay Spoofing Attack Detection.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683693)]

- [ ] Roberto Font. *A Denoising Autoencoder for Speaker Recognition. Results on the MCE 2018 Challenge.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683525/)]

- [ ] Shuai Wang, Yexin Yang, Tianzhe Wang, Yanmin Qian, Kai Yu. *Knowledge Distillation for Small Foot-print Deep Speaker Embedding.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683443/)]

- [ ] Liang He, Xianhong Chen, Can Xu, Jia Liu. *Multi-objective Optimization Training of PLDA for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683295/)]

- [ ] Ondřej Novotný, Oldřich Plchot, Ondřej Glembek, Lukáš Burget, Pavel Matějka. *Discriminatively Re-trained i-vector Extractor for Speaker Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682590/)] [[CoRR 2018](http://arxiv.org/abs/1810.13183)]

- [ ] Lantian Li, Zhiyuan Tang, Ying Shi, Dong Wang. *Gaussian-constrained Training for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683245/)] [[CoRR 2018](http://arxiv.org/abs/1811.03258)]

- [ ] Gautam Bhattacharya, Jahangir Alam, Patrick Kenny. *Adapting End-to-End Neural Speaker Verification to New Languages and Recording Conditions with Adversarial Training.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682611)] [[CoRR 2018](http://arxiv.org/abs/1811.03055)]

- [x] Ya-Qi Yu, Lei Fan, Wu-Jun Li. *Ensemble Additive Margin Softmax for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683649)]
  - `TI-SV` `AM-Softmax` `HSIC`

## SLP-L2: End-to-end Speech Recognition II: New Models

## SLP-P4: Speaker Verification and Identification II

## SLP-L8: Speech Synthesis I

- [ ] Jean-Marc Valin, Jan Skoglund. *LPCNET: Improving Neural Speech Synthesis through Linear Prediction.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682804/)] [[CoRR 2018](LPCNET: Improving Neural Speech Synthesis through Linear Prediction)]

- [ ] Jungbae Park, Kijong Han, Yuneui Jeong, Sang Wan Lee. *Phonemic-level Duration Control Using Attention Alignment for Natural Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683827/)]

- [ ] Wei-Ning Hsu, Yu Zhang, Ron J. Weiss, Yu-An Chung, Yuxuan Wang, Yonghui Wu, James Glass. *Disentangling Correlated Speaker and Noise for Speech Synthesis via Data Augmentation and Adversarial Factorization.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683561/)]

- [x] Kyle Kastner, João Felipe Santos, Yoshua Bengio, Aaron Courville. *Representation Mixing for TTS Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682880/)] [[CoRR 2018](http://arxiv.org/abs/1811.07240)]
  - `TTS` `Representation Mixing`
  - Single word can have different pronunciation.
  - Combine grapheme and phoneme inputs in a single encoder flexibly (with mask).

- [ ] Younggun Lee, Taesu Kim. *Robust and Fine-grained Prosody Control of End-to-end Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683501/)] [[CoRR 2018](http://arxiv.org/abs/1811.02122)]

- [ ] Xin Wang, Shinji Takaki, Junichi Yamagishi. *Neural Source-filter-based Waveform Model for Statistical Parametric Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682298/)] [[CoRR 2018](http://arxiv.org/abs/1810.11946)]
