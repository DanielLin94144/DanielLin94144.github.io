---
title: "Analyzing the Robustness of Unsupervised Speech Recognition"
collection: publications
# permalink: /publication/2021-10-07-paper-title-number-1
# excerpt: 'Analyze the training robustness of the state-of-the-art unsupervised ASR Wav2vec-U.'
# date: 2021-10-07
venue: 'ICASSP 2022'
paperurl: 'https://arxiv.org/pdf/2110.03509.pdf'
# citation: ''
---
**Author**: Guan-Ting Lin<sup>*</sup>, Chan-Jan Hsu<sup>*</sup>, Da-Rong Liu, Hung-Yi Lee, Yu Tsao\\
**Abstract**:\\
Unsupervised speech recognition (unsupervised ASR) aims to learn the ASR system with non-parallel speech and text corpus only. Wav2vec-U has shown promising results in unsupervised ASR by self-supervised speech representations coupled with Generative Adversarial Network (GAN) training, but the robustness of the unsupervised ASR framework is unknown. In this work, we further analyze the training robustness of unsupervised ASR on the domain mismatch scenarios in which the domains of unpaired speech and text are different. Three domain mismatch scenarios include: (1) using speech and text from different datasets, (2) utilizing noisy/spontaneous speech, and (3) adjusting the amount of speech and text data. We also quantify the degree of the domain mismatch by calculating the JS-divergence of phoneme n-gram between the transcription of speech and text. This metric correlates with the performance highly. Experimental results show that domain mismatch leads to inferior performance, but a self-supervised model pre-trained on the targeted speech domain can extract better representation to alleviate the performance drop. \\

[paper](https://arxiv.org/pdf/2110.03509.pdf)
