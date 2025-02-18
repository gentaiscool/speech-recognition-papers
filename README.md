# Speech Recognition Papers
List of hot directions in industrial speech recognition, i.e., **Streaming ASR** / **Non-autoregressive ASR** / **WFST based ASR** ...

If you are interested in this repo, any [pull request](https://github.com/xingchensong/speech-recognition-papers/pulls) is welcomed.

## Streaming ASR

### RNA based
- Standard RNA: [Recurrent Neural Aligner: An Encoder-Decoder Neural Network Model for Sequence to Sequence Mapping](https://pdfs.semanticscholar.org/7703/a2c5468ecbee5b62c048339a03358ed5fe19.pdf) (Interspeech 2017)
- Extended RNA: [Extending Recurrent Neural Aligner for Streaming End-to-End Speech Recognition in Mandarin](https://arxiv.org/pdf/1806.06342.pdf) (Interspeech 2018)
- Transformer equipped RNA: [Self-attention Aligner: A Latency-control End-to-end Model for ASR Using Self-attention Network and Chunk-hopping](https://arxiv.org/pdf/1902.06450.pdf) (ICASSP 2019)
- CIF: [CIF: Continuous Integrate-And-Fire for End-To-End Speech Recognition](https://arxiv.org/pdf/1905.11235.pdf) (ICASSP 2020)
- CIF: [A Comparison of Label-Synchronous and Frame-Synchronous End-to-End Models for Speech Recognition](https://arxiv.org/pdf/2005.10113.pdf) (Interspeech 2020)

### RNN-T based
- Standard RNN-T: [Streaming E2E Speech Recognition For Mobile Devices](https://arxiv.org/pdf/1811.06621.pdf) (ICASSP 2019)
- Latency Controlled RNN-T: [RNN-T For Latency Controlled ASR With Improved Beam Search](https://arxiv.org/pdf/1911.01629.pdf) (arXiv 2019)
- Transformer equipped RNN-T: [Self-Attention Transducers for End-to-End Speech Recognition](https://arxiv.org/pdf/1909.13037.pdf) (Interspeech 2019)
- Transformer equipped RNN-T: [Transformer Transducer: A Streamable Speech Recognition Model With Transformer Encoders And RNN-T Loss](https://arxiv.org/pdf/2002.02562.pdf) (ICASSP 2020)
- Transformer equipped RNN-T: [A Streaming On-Device End-to-End Model Surpassing Server-Side Conventional Model Quality and Latency](https://arxiv.org/pdf/2003.12710.pdf) (ICASSP 2020)
- Tricks for RNN-T Training: [Towards Fast And Accurate Streaming E2E ASR](https://arxiv.org/pdf/2004.11544.pdf) (ICASSP 2020)
- Knowledge Distillation for RNN-T: [Knowledge Distillation from Offline to Streaming RNN Transducer for End-to-end Speech Recognition]() (Interspeech 2020)
- Transfer Learning for RNN-T: [Transfer Learning Approaches for Streaming End-to-End Speech Recognition System](https://arxiv.org/pdf/2008.05086.pdf) (Interspeech 2020)
- Exploration on RNN-T: [Analyzing the Quality and Stability of a Streaming End-to-End On-Device Speech Recognizer](https://arxiv.org/pdf/2006.01416.pdf) (Interspeech 2020)

### Attention based
- Montonic Attention: [Montonic Chunkwise Attention](https://arxiv.org/pdf/1712.05382.pdf) (ICLR 2018)
- Enhanced Montonic Attention: [Enhancing Monotonic Multihead Attention for Streaming ASR](https://arxiv.org/pdf/2005.09394.pdf) (Interspeech 2020)
- Minimum Latency Training based on Montomic Attention: [Minimum Latency Training Strategies For Streaming seq-to-seq ASR](https://arxiv.org/pdf/2004.05009.pdf) (ICASSP 2020)
- Triggered Attention: [Triggered Attention for End-to-End Speech Recognition](https://www.merl.com/publications/docs/TR2019-015.pdf) (ICASSP 2019)
- Triggered Attention for Transformer: [Streaming Automatic Speech Recognition With The Transformer Model](https://arxiv.org/pdf/2001.02674.pdf) (ICASSP 2020)
- Block-synchronous: [Streaming Transformer ASR with Blockwise Synchronous Inference](https://arxiv.org/pdf/2006.14941.pdf) (ASRU 2019)
- Block-synchronous with chunk reuse: [Transformer Online CTC/Attention E2E Speech Recognition Architecture](https://arxiv.org/pdf/2001.08290.pdf) (ICASSP 2020)
- Block-synchronous with RNN-T like decoding rule: [Synchronous Transformers For E2E Speech Recognition](https://arxiv.org/pdf/1912.02958.pdf) (ICASSP 2020)
- Scout-synchronous: [Low Latency End-to-End Streaming Speech Recognition with a Scout Network](https://arxiv.org/pdf/2003.10369.pdf) (Interspeech 2020)
- CTC-synchronous: [CTC-synchronous Training for Monotonic Attention Model](https://arxiv.org/pdf/2005.04712.pdf) (Interspeech 2020)
- Memory Augmented Attention: [Streaming Transformer-based Acoustic Models Using Self-attention with Augmented Memory](https://arxiv.org/pdf/2005.08042.pdf) (Interspeech 2020)
- Memory Augmented Attention: [Streaming Chunk-Aware Multihead Attention for Online End-to-End Speech Recognition](https://arxiv.org/pdf/2006.01712.pdf) (Interspeech 2020)
- Optimized Beam Search: [High Performance Sequence-to-Sequence Model for Streaming Speech Recognition](https://arxiv.org/pdf/2003.10022.pdf) (Interspeech 2020)

### Unified Streaming/Non-streaming models
- [Transformer Transducer: One Model Unifying Streaming And Non-Streaming Speech Recognition](https://arxiv.org/pdf/2010.03192.pdf) (arXiv 2020)
- [Universal ASR: Unify And Improve Streaming ASR With Full-Context Modeling](https://openreview.net/pdf?id=Pz_dcqfcKW8) (ICLR 2021 under double-blind review)


## Non-autoregressive (NAR)  ASR
- MASK-Predict: [Listen and Fill in the Missing Letters: Non-Autoregressive Transformer for Speech Recognition](https://arxiv.org/pdf/1911.04908.pdf) (arXiv 2019)
- Imputer: [Imputer: Sequence modelling via imputation and dynamic programming](https://arxiv.org/pdf/2002.08926.pdf) (arXiv 2020)
- Insertion-based: [Insertion-Based Modeling for End-to-End Automatic Speech Recognition](https://arxiv.org/pdf/2005.13211.pdf) (arXiv 2020)
- MASK-CTC: [Mask CTC: Non-Autoregressive End-to-End ASR with CTC and Mask Predict](https://arxiv.org/pdf/2005.08700.pdf) (Interspeech 2020)
- Spike Triggered: [Spike-Triggered Non-Autoregressive Transformer for End-to-End Speech Recognition](https://arxiv.org/pdf/2005.07903.pdf) (Interspeech 2020)
- Similar to MASK-Predict: [Listen Attentively, and Spell Once: Whole Sentence Generation via a Non-Autoregressive Architecture for Low-Latency Speech Recognition](https://arxiv.org/pdf/2005.04862.pdf) (Interspeech 2020)

## ASR Rescoring / Spelling Correction (2-pass decoding)
- Review: [Automatic Speech Recognition Errors Detection and Correction: A Review](https://www.sciencedirect.com/science/article/pii/S1877050918302187) (N/A)
- LAS based: [A Spelling Correction Model For E2E Speech Recognition](https://arxiv.org/pdf/1902.07178.pdf) (ICASSP 2019)
- Transformer based: [An Empirical Study Of Efficient ASR Rescoring With Transformers](https://arxiv.org/pdf/1910.11450.pdf) (arXiv 2019)
- Transformer based: [Automatic Spelling Correction with Transformer for CTC-based End-to-End Speech Recognition](https://arxiv.org/pdf/1904.10045.pdf) (Interspeech 2019)
- Transformer based: [Correction of Automatic Speech Recognition with Transformer Sequence-To-Sequence Model](https://arxiv.org/pdf/1910.10697.pdf) (ICASSP 2020)
- BERT based: [Effective Sentence Scoring Method Using BERT for Speech Recognition](http://proceedings.mlr.press/v101/shin19a/shin19a.pdf) (ACML 2019)
- BERT based: [Spelling Error Correction with Soft-Masked BERT](https://arxiv.org/pdf/2005.07421.pdf) (ACL 2020)
- Parallel Rescoring: [Parallel Rescoring with Transformer for Streaming On-Device Speech Recognition](https://arxiv.org/pdf/2008.13093.pdf) (Interspeech 2020)

## Model Compression for On-device ASR
- Lightweight Low-Rank transformer: [Lightweight and Efficient End-to-End Speech Recognition Using Low-Rank Transformer](https://arxiv.org/pdf/1910.13923.pdf) (ICASSP 2020)
- Attention replacement: [How Much Self-Attention Do We Need ƒ Trading Attention for Feed-Forward Layers](https://www-i6.informatik.rwth-aachen.de/publications/download/1126/IrieKazukiGerstenbergerAlexerSchl%FCterRalfNeyHermann--HowMuchSelf-AttentionDoWeNeed%3FTradingAttentionforFeed-ForwardLayers--2020.pdf) (ICASSP 2020)