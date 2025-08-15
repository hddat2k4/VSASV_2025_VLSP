# Brosch Vietnamese Spoofing-Aware Speaker Verification (VSASV) Challenge 2025

This repository contains Brosch Team's work for the VSASV Challenge 2025, where we achieved 4th place in the final leaderboard. The challenge focuses on Spoofing-Aware Speaker Verification (SASV), which requires systems to verify a speaker's identity while being robust against spoofing attack.

## Approach

To tackle this problem, I implemented and optimized multiple deep learning models specialized for both speaker verification (SV) and anti-spoofing (CM) tasks:

- ResNet34 – used as a backbone for extracting robust speaker embeddings.

- AASIST – a state-of-the-art model for spoof detection, providing discriminative countermeasure embeddings.

I also explored fusion strategies to combine information from SV and CM systems effectively:

- Score fusion – combining model output scores with weighting and normalization.

- Embedding fusion – concatenating or projecting embeddings from multiple models before classification.

## Key Results

**Final rank:** 4th place on the official leaderboard.

Significant improvement in robustness against spoofed trials through fusion-based approaches.

Demonstrated that combining specialized SV and CM models can outperform single-model baselines.
