# ICASSP 2019

## SLP-L1: End-to-end Speech Recognition I: General Topics

Bo Li, Yu Zhang, Tara Sainath, Yonghui Wu, William Chan. *Bytes Are All You Need: End-to-end Multilingual Speech Recognition and Synthesis with Bytes.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682674)] [[CoRR2018](https://arxiv.org/abs/1811.09021)]
- `Multilingual` `ASR` `TTS`
- Use Unicode bytes instead of characters, sub-words or words as the unit of text representation.
- ASR: outperform grapheme models in both multilingual and monolingual models.
- TTS: match the performance of monolingual grapheme models.
- Small vocabulary size (256 for UTF-8) helps to build compact models.

Shuo-Yiin Chang, Rohit Prabhavalkar, Yanzhang He, Tara N. Sainath, Gabor Simko. *Joint Endpointing and Decoding with End-to-end Models.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683109)]

Changhao Shan, Chao Weng, Guangsen Wang, Dan Su, Min Luo, Dong Yu, Lei Xie. *Component Fusion: Learning Replaceable Language Model Component for End-to-end Speech Recognition System.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682490)]
- `ASR` `LM Fushion` `Component Fushion`
- Use Component Fusion to incorporate externally trained LM into an attention-based ASR system.
- Make use of the large amount of text corpora.
- Concatenate the hidden states of ASR model and LM (unlike Cold Fushion: first, train the ASR model jointly with a fixed LM pre-trained on transcript text, then replace the LM with another one which is trained on a larger text corpora or out-of-domain text during decoding).
- Achieve better performance in both in-domain and out-of-domain senary.

Stefan Braun, Shih-Chii Liu. *Parameter Uncertainty for End-to-end Speech Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683066)]

Shane Settle, Kartik Audhkhasi, Karen Livescu, Michael Picheny. *Acoustically Grounded Word Embeddings for Improved Acoustics-to-Word Speech Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682903)] [[CoRR 2019](http://arxiv.org/abs/1903.12306)]

Murali Karthick Baskar, Lukás Burget, Shinji Watanabe, Martin Karafiát, Takaaki Hori, Jan Honza Cernocký. *Promising Accurate Prefix Boosting for sequence-to-sequence ASR.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682782)] [[CoRR 2018](http://arxiv.org/abs/1811.02770)]

## SLP-P2: Speaker Verification and Identification I

Mahesh Kumar Nandwana, Mitchell McLaren, Luciana Ferrer, Diego Castan, Aaron Lawson. *Analysis and Mitigation of Vocal Effort Variations in Speaker Recognition.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683881)]

Johan Rohdin, Themos Stafylakis, Anna Silnova, Hossein Zeinali, Lukáš Burget, Oldřich PlchotSpeaker. *Verification Using End-to-End Adversarial Language Adaptation.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683616)]

Gautam Bhattacharya, Jahangir Alam, Patrick Kenny. *Adapting End-to-End Neural Speaker Verification to New Languages and Recording Conditions with Adversarial Training.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682611)] [[CoRR 2018](http://arxiv.org/abs/1811.03055)]

Ya-Qi Yu, Lei Fan, Wu-Jun Li. *Ensemble Additive Margin Softmax for Speaker Verification.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683649)]
