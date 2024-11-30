# DyMO: Training-Free Diffusion Model Alignment with Dynamic Multi-Objective Scheduling

<p>
Text-to-image diffusion model alignment is critical for improving the alignment between the generated images and human preferences. While training-based methods are constrained by high computational costs and dataset requirements, training-free alignment methods remain underexplored and are often limited by inaccurate guidance. 
</p>

<p>
To address these limitations above, we propose a plug-and-play training-free alignment method, DyMO, for aligning the generated images and human preferences during inference. Apart from text-aware human preference scores, we introduce a semantic alignment objective for enhancing the semantic alignment in the early stages of diffusion, relying on the fact that the attention maps are effective reflections of the semantics in noisy images. We propose dynamic scheduling of multiple objectives and intermediate recurrent steps to reflect the requirements at different steps. 
</p>

<p>
We conduct validation of the proposed DyMO with diverse pre-trained diffusion models, e.g., SD V1.5, SDXL, etc. DyMO outperforms different pre-trained baseline models and other state-of-the-art training-based and training-free methods significantly on different metrics, demonstrating effectiveness and superiority. Code and model: https://shelsin.github.io/dymo.github.io/
</p>
