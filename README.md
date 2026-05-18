# RAPID: Layer-Wise Redundancy-Aware Pruning and Importance-Driven Token Merging for Efficient ViT

Kyumin Choi, Ikbeom Jang†  
Hankuk University of Foreign Studies  
† Corresponding author

Official repository for the paper:

**RAPID: Layer-Wise Redundancy-Aware Pruning and Importance-Driven Token Merging for Efficient ViT**

## Abstract

Vision Transformers (ViTs) achieve strong performance but suffer from high computational costs due to quadratic self-attention complexity. Although token reduction techniques such as pruning and merging mitigate this, they typically overlook how representations evolve across network depth. We propose **RAPID**, a depth-aware token reduction framework that adapts reduction strategies to the layer-wise characteristics of token representations. The primary methodological contribution is a bifurcated strategy: in shallow-to-middle layers, RAPID employs a redundancy-similarity aware pruning metric to eliminate over-represented local patterns. As features transition to global semantic concepts in deeper layers, the framework shifts to an importance-similarity aware merging mechanism. This stage leverages classification (CLS) token attention weights to protect semantically critical tokens while fusing less important but similar neighbors. Empirical validation on ImageNet-1K using ViT and DeiT architectures demonstrates that RAPID establishes a superior accuracy-compression Pareto frontier compared to plug-and-play baselines such as ToMe and ToFu. RAPID is particularly robust in aggressive compression regimes, achieving up to 4.29% higher accuracy than ToMe at extreme reduction rates. Our framework provides a training-free template for optimizing vision models by aligning reduction strategies with hierarchical feature evolution.

🚀 Code will be updated and released soon.
