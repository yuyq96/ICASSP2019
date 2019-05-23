# ICASSP2019

- SLP-L1: End-to-end Speech Recognition I: General Topics
  - Bo Li, Yu Zhang, Tara Sainath, Yonghui Wu, William Chan. *Bytes Are All You Need: End-to-end Multilingual Speech Recognition and Synthesis with Bytes.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682674)] [[CoRR2018](https://arxiv.org/abs/1811.09021)]
    - `Multilingual` `ASR` `TTS`
    - Use Unicode bytes instead of characters, sub-words or words as the unit of text representation.
    - ASR: outperform grapheme models in both multilingual and monolingual models.
    - TTS: match the performance of monolingual grapheme models.
    - Small vocabulary size (256 for UTF-8) helps to build compact models.
  - Shuo-Yiin Chang, Rohit Prabhavalkar, Yanzhang He, Tara N. Sainath, Gabor Simko. *Joint Endpointing and Decoding with End-to-end Models.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8683109)]
  - Changhao Shan, Chao Weng, Guangsen Wang, Dan Su, Min Luo, Dong Yu, Lei Xie. *Component Fusion: Learning Replaceable Language Model Component for End-to-end Speech Recognition System.* [[ICASSP 2019](https://ieeexplore.ieee.org/document/8682490)]
    - `ASR` `LM Fushion`
    - Use Component Fusion to incorporate externally trained LM into an attention-based ASR system.
    - Make use of the large amount of text corpora.
