# 3D-MoE: Towards Spatial Intelligence with Mixture-of-Experts for 3D Reasoning and Action Generation

Yueen Ma, Zenglin Xu, Irwin King

The Chinese University of Hong Kong · Fudan University · Shanghai Academy of AI for Science

## Introduction

Spatial intelligence, encompassing 3D perception and reasoning, is the next frontier of AI, but scaling dense 3D vision-language models (VLMs) is computationally expensive. **3D-MoE** is a 3D VLM built on an efficient mixture-of-experts (MoE) architecture:

- **Routing curriculum.** A specialist warmup phase (deterministic routing) is followed by differential boundary relaxation (probabilistic routing). It gives modality- and spatial-context-aware routing that is both stable and flexible.
- **Pose-DiT.** A diffusion-based action head that turns 3D-MoE into a 3D vision-language-action (VLA) model. It uses rectified flow to generate 6D pose actions in a single sampling step, which allows real-time inference for robot manipulation.

3D-MoE achieves strong results on diverse 3D vision-language benchmarks with far fewer activated parameters, and yields higher success rates on embodied manipulation tasks.

## Code

🚧 **Code is coming soon.** Stay tuned!
