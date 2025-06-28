# [ICCV25] Autoregressive Denoising Score Matching is a Good Video Anomaly Detector

**[[Paper]](https://arxiv.org/)**

This repository is the official release code for our ICCV25 paper ADSM.

**We propose autoregressive denoising score matching (ADSM), which contains a novel model, a novel score function, and a novel autoregressive mechanism to not only utilize the efficiency of likelihood estimation but also take characteristics of video anomalies into account.** We first design a novel noise-conditioned score transformer (NCST), which is **the first score-based transformer for VAD**, combining the efficiency of denoising score matching with the powerful diffusion probabilistic transformers. Next, we embed the scene condition and assign motion weights based on inputs to form **a scene-dependent and motion-aware score function**. Last but not least, we propose **a novel mechanism** to autoregressively approximate the score function and combine visual details based on the corresponding denoised data for anomaly accumulation and vision enhancement. Extensive experiments on three datasets verify the effectiveness of our method.



