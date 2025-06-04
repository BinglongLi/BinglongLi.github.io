---
title: "Efficient RAW Image Deblurring with Adaptive Frequency Modulation."
collection: Preprint publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about raw image deblurring.'
date: 2025-05-15
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2505.24407'
citation: 'Binglong Li, et al. Efficient RAW Image Deblurring with Adaptive Frequency Modulation. arxiv. 2505.24407.'
---

Image deblurring plays a crucial role in enhancing visual clarity across various applications. Although most deep learning approaches primarily focus on sRGB images, which inherently lose critical information during the image signal processing pipeline, RAW images, being unprocessed and linear, possess superior restoration potential but remain underexplored. Deblurring RAW images presents unique challenges, particularly in handling frequency-dependent blur while maintaining computational efficiency. To address these issues, we propose Frequency Enhanced Network (FrENet), a framework specifically designed for RAW-to-RAW deblurring that operates directly in the frequency domain. We introduce a novel Adaptive Frequency Positional Modulation module, which dynamically adjusts frequency components according to their spectral positions, thereby enabling precise control over the deblurring process. Additionally, frequency domain skip connections are adopted to further preserve high-frequency details. Experimental results demonstrate that FrENet surpasses state-of-the-art deblurring methods in RAW image deblurring, achieving significantly better restoration quality while maintaining high efficiency in terms of reduced MACs. Furthermore, FrENet's adaptability enables it to be extended to sRGB images, where it delivers comparable or superior performance compared to methods specifically designed for sRGB data. The code will be available at https://github.com/WenlongJiao/FrENet .
