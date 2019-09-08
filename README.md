# ICASSP 2019

## Speech Language Processing

### Lecture 1: End-to-end Speech Recognition I: General Topics

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

### Lecture 2: End-to-end Speech Recognition II: New Models

### Lecture 6: Systems for Speaker Recognition and Identification

### Poster 2: Speaker Verification and Identification I

- [ ] Mahesh Kumar Nandwana, Mitchell McLaren, Luciana Ferrer, Diego Castan, Aaron Lawson. *Analysis and Mitigation of Vocal Effort Variations in Speaker Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683881)]

- [x] Johan Rohdin, Themos Stafylakis, Anna Silnova, Hossein Zeinali, Lukáš Burget, Oldřich PlchotSpeaker. *Speaker Verification Using End-to-End Adversarial Language Adaptation.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683616)]
  - `TI-SV` `Domain Adaption` `GAN` `Maximum Mean Discrepancy (MMD)` `Wasserstein Distance`
  - Generator: minimize Wasserstein distance and classification loss.
  - Discriminator: maximize Wasserstein distance (and minimize gradient penalty loss for 1-Lipschitz constraint).

- [ ] Buddhi Wickramasinghe, Eliathamby Ambikairajah, Julien Epps, Vidhyasaharan Sethu, Haizhou Li. *Auditory Inspired Spatial Differentiation for Replay Spoofing Attack Detection.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683693)]

- [ ] Roberto Font. *A Denoising Autoencoder for Speaker Recognition. Results on the MCE 2018 Challenge.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683525/)]

- [ ] Shuai Wang, Yexin Yang, Tianzhe Wang, Yanmin Qian, Kai Yu. *Knowledge Distillation for Small Foot-print Deep Speaker Embedding.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683443/)]
  - `TI-SV` `Knowledge Distillation` `Teacher-Student`
  - Optimize in both label level (posterior distribution, by KL-divergence) and embedding level (by cosine distance).

- [ ] Liang He, Xianhong Chen, Can Xu, Jia Liu. *Multi-objective Optimization Training of PLDA for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683295/)]

- [ ] Ondřej Novotný, Oldřich Plchot, Ondřej Glembek, Lukáš Burget, Pavel Matějka. *Discriminatively Re-trained i-vector Extractor for Speaker Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682590/)] [[CoRR 2018](http://arxiv.org/abs/1810.13183)]

- [ ] Lantian Li, Zhiyuan Tang, Ying Shi, Dong Wang. *Gaussian-constrained Training for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683245/)] [[CoRR 2018](http://arxiv.org/abs/1811.03258)]

- [ ] Gautam Bhattacharya, Jahangir Alam, Patrick Kenny. *Adapting End-to-End Neural Speaker Verification to New Languages and Recording Conditions with Adversarial Training.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682611)] [[CoRR 2018](http://arxiv.org/abs/1811.03055)]

- [x] Ya-Qi Yu, Lei Fan, Wu-Jun Li. *Ensemble Additive Margin Softmax for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683649)]
  - `TI-SV` `Additive Margin Softmax` `Hilbert-Schmidt Independence Criterion`

### Poster 4: Speaker Verification and Identification II

- [ ] Fei Zhao, Hao Li, Xueliang Zhang. *A Robust Text-independent Speaker Verification Method Based on Speech Separation and Deep Speaker.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683762/)]

- [ ] Gajan Suthokumar, Kaavya Sriskandaraja, Vidhyasaharan Sethu, Chamith Wijenayake, Eliathamby Ambikairajah. *Phoneme Specific Modelling and Scoring Techniques for Anti Spoofing System.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682411/)]

- [ ] Phani Sankar Nidadavolu, Vicente Iglesias, Jesús Villalba, Najim Dehak. *Investigation on Neural Bandwidth Extension of Telephone Speech for Improved Speaker Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682992/)]

- [ ] Yun Tang, Guohong Ding, Jing Huang, Xiaodong He, Bowen Zhou. *Deep Speaker Embedding Learning with Multi-level Pooling for Text-independent Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682712/)] [[CoRR 2018](http://arxiv.org/abs/1902.07821)]

- [ ] Sandro Cumani, Pietro Laface. *Tied Normal Variance–Mean Mixtures for Linear Score Calibration.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683379/)]

- [ ] Insoo Kim, Kyuhong Kim, Jiwhan Kim, Changkyu Choi. *Deep Speaker Representation Using Orthogonal Decomposition and Recombination for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683332/)]

- [ ] Yichi Zhang, Meng Yu, Na Li, Chengzhu Yu, Jia Cui, Dong Yu. *Seq2Seq Attentional Siamese Neural Networks for Text-dependent Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682676/)]

- [ ] Tharshini Gunendradasan, Saad Irtza, Eliathamby Ambikairajah, Julien Epps. *Transmission Line Cochlear Model Based AM-FM Features for Replay Attack Detection.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682771/)]

- [ ] Hossein Zeinali, Luka Burget, Johan Rohdin, Themos Stafylakis, Jan Honza Cernocky. *How to Improve Your Speaker Embeddings Extractor in Generic Toolkits.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683445/)] [[CoRR 2018](http://arxiv.org/abs/1811.02066)]

- [ ] Tomi Kinnunen, Rosa González Hautamäki, Ville Vestman, Md Sahidullah. *Can We Use Speaker Recognition Technology to Attack Itself? Enhancing Mimicry Attacks Using Automatic Target Speaker Selection.* [[ICASSP 2019]()] [[CoRR 2018](http://arxiv.org/abs/1811.03790)]

### Poster 6: Features and Robustness for Speaker Identification

### Poster 8: Features and Learning for Speaker Identification and Diarization

### Lecture 8: Speech Synthesis I

- [x] Jean-Marc Valin, Jan Skoglund. *LPCNET: Improving Neural Speech Synthesis through Linear Prediction.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682804/)] [[CoRR 2018](LPCNET: Improving Neural Speech Synthesis through Linear Prediction)]
  - `TTS` `Spectrogram-to-waveform` `LPCNet`
  - Use linear predictor to simplify the prediction, so that the network directly predict the excitation (residual).

- [ ] Jungbae Park, Kijong Han, Yuneui Jeong, Sang Wan Lee. *Phonemic-level Duration Control Using Attention Alignment for Natural Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683827/)]

- [ ] Wei-Ning Hsu, Yu Zhang, Ron J. Weiss, Yu-An Chung, Yuxuan Wang, Yonghui Wu, James Glass. *Disentangling Correlated Speaker and Noise for Speech Synthesis via Data Augmentation and Adversarial Factorization.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683561/)]

- [x] Kyle Kastner, João Felipe Santos, Yoshua Bengio, Aaron Courville. *Representation Mixing for TTS Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682880/)] [[CoRR 2018](http://arxiv.org/abs/1811.07240)]
  - `TTS` `Text-to-spectrogram` `Representation Mixing`
  - Single word can have different pronunciation.
  - Combine grapheme and phoneme inputs in a single encoder flexibly (with mask).

- [ ] Younggun Lee, Taesu Kim. *Robust and Fine-grained Prosody Control of End-to-end Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683501/)] [[CoRR 2018](http://arxiv.org/abs/1811.02122)]

- [x] Xin Wang, Shinji Takaki, Junichi Yamagishi. *Neural Source-filter-based Waveform Model for Statistical Parametric Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682298/)] [[CoRR 2018](http://arxiv.org/abs/1810.11946)]
  - `TTS` `Spectrogram-to-waveform`
  - Use source module to generate sine-based excitation signal, then use filter module to transform excitation signal into waveform.
  - Faster than autoregressive models (e.g., WaveNet).
  - Simpler than non-autoregressive models (e.g., Parallel WaveNet), since it does not need to employ complicated training method (e.g., distilling).

### Poster 20: Speech Synthesis II

- [ ] Yusuke Yasuda, Xin Wang, Shinji Takaki, Junichi Yamagishi. *Investigation of Enhanced Tacotron Text-to-speech Synthesis Systems with Self-attention for Pitch Accent Language.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682353/)] [[CoRR 2018](http://arxiv.org/abs/1810.11960)]

- [ ] Shan Yang, Heng Lu, Shiying Kang, Lei Xie, Dong Yu. *Enhancing Hybrid Self-attention Structure with Relative-position-aware Bias for Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682861/)]

- [ ] Lauri Juvela, Bajibabu Bollepalli, Junichi Yamagishi, Paavo Alku. *Waveform Generation for Text-to-speech Synthesis Using Pitch-synchronous Multi-scale Generative Adversarial Networks.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683271/)] [[CoRR 2018](http://arxiv.org/abs/1810.12598)]

- [ ] Kohki Mametani, Tsuneo Kato, Seiichi Yamamoto. *Investigating Context Features Hidden in End-to-end TTS.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683857/)] [[CoRR 2018](http://arxiv.org/abs/1811.01376)]

- [ ] Éva Székely, Gustav Eje Henter, Joakim Gustafson. *Casting to Corpus: Segmenting and Selecting Spontaneous Dialogue for TTS with a CNN-LSTM Speaker-dependent Breath Detector.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683846/)]

- [ ] Ruibo Fu, Jianhua Tao, Zhengqi Wen, Yibin Zheng. *Phoneme Dependent Speaker Embedding and Model Factorization for Multi-speaker Speech Synthesis and Adaptation.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682535/)]

- [ ] Yuewen Cao, Xixin Wu, Songxiang Liu, Jianwei Yu, Xu Li, Zhiyong Wu, Xunying Liu, Helen Meng. *End-to-end Code-switched TTS with Mix of Monolingual Recordings.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682927/)]

- [ ] Yu-An Chung, Yuxuan Wang, Wei-Ning Hsu, Yu Zhang, RJ Skerry-Ryan. *Semi-supervised Training for Improving Data Efficiency in End-to-end Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683862/)] [[CoRR 2018](http://arxiv.org/abs/1808.10128)]

- [ ] Ya-Jie Zhang, Shifeng Pan, Lei He, Zhen-Hua Ling. *Learning Latent Representations for Style Control and Transfer in End-to-end Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683623/)] [[CoRR 2018](http://arxiv.org/abs/1812.04342)]

- [ ] Heejin Choi, Sangjun Park, Jinuk Park, Minsoo Hahn. *Multi-speaker Emotional Acoustic Modeling for CNN-based Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683682/)]

- [ ] Yukiya Hono, Kei Hashimoto, Keiichiro Oura, Yoshihiko Nankaku, Keiichi Tokuda. *Singing Voice Synthesis Based on Generative Adversarial Networks.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683154/)]

- [ ] Kantapon Kaewtip, Fernando Villavicencio, Fang-Yu Kuo, Mark Harvilla, Iris Ouyang, Pierre Lanchantin. *Enhanced Virtual Singers Generation by Incorporating Singing Dynamics to Personalized Text-to-speech-to-singing.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682968/)]

- [ ] Takuma Okamoto, Tomoki Toda, Yoshinori Shiga, Hisashi Kawai. *Investigations of Real-time Gaussian Fftnet and Parallel Wavenet Neural Vocoders with Simple Acoustic Features.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682320/)]

### Poster 22: Speech Synthesis III

- [ ] Yang Ai, Jing-Xuan Zhang, Liang Chen, Zhen-Hua Ling. *DNN-based Spectral Enhancement for Neural Waveform Generators with Low-bit Quantization.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683016/)]

- [ ] Miraç Göksu Öztürk, Okan Ulusoy, Cenk Demiroglu. *DNN-based Speaker-adaptive Postfiltering with Limited Adaptation Data for Statistical Speech Synthesis Systems.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683714/)]

- [ ] Chunhui Lu, Pengyuan Zhang, Yonghong Yan. *Self-attention Based Prosodic Boundary Prediction for Chinese Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682770/)]

- [ ] François Marelli, Bastian Schnell, Hervé Bourlard, Thierry Dutoit, Philip N. Garner. *An End-to-end Network to Synthesize Intonation Using a Generalized Command Response Model.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683815/)]

- [ ] Oliver Watts, Cassia Valentini-Botinhao, Simon King. *Speech Waveform Reconstruction Using Convolutional Neural Networks with Noise and Periodic Inputs.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683398/)]

- [ ] Yanfeng Lu, Minghui Dong, Ying Chen. *Implementing Prosodic Phrasing in Chinese End-to-end Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682368/)]

- [ ] Mu Wang, Xixin Wu, Zhiyong Wu, Shiyin Kang, Deyi Tuo, Guangzhi Li, Dan Su, Dong Yu, Helen Meng. *Quasi-fully Convolutional Neural Network with Variational Inference for Speech Synthesis.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682528/)]

- [ ] Shinji Takaki, Toru Nakashika, Xin Wang, Junichi Yamagishi. *STFT Spectral Loss for Training a Neural Speech Waveform Model.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683791/)] [[CoRR 2018](http://arxiv.org/abs/1810.11945)]

- [ ] Hiroki Tamaru, Yuki Saito, Shinnosuke Takamichi, Tomoki Koriyama, Hiroshi Saruwatari. *Generative Moment Matching Network-based Random Modulation Post-filter for DNN-based Singing Voice Synthesis and Neural Double-tracking.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683476/)] [[CoRR 2019](http://arxiv.org/abs/1902.03389)]

- [ ] Javier Latorre, Jakub Lachowicz, Jaime Lorenzo-Trueba, Thomas Merritt, Thomas Drugman, Srikanth Ronanki, Viacheslav Klimkov. *Effect of Data Reduction on Sequence-to-sequence Neural TTS.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682168/)] [[CoRR 2018](http://arxiv.org/abs/1811.06315)]
