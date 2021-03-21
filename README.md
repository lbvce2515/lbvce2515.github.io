# Language-based Video Editing via Multi-Modal Multi-Level Transformer

<img src="https://github.com/lbvce2515/lbvce2515.github.io/raw/main/imgs/fig_qual.png" style="width: 65%;" />

## Abstract
Video editing tools are widely used nowadays for digital design. Although the demand for these tools is high, the prior knowledge required makes it difficult for novices to get started. Systems that could follow natural language instructions to perform automatic editing would significantly improve accessibility. This paper introduces the language-based video editing (LBVE) task, which allows the model to edit, guided by text instruction, a source video into a target video. LBVE contains two features: 1) the scenario of the source video is preserved instead of generating a completely different video; 2) the semantic is presented differently in the target video, and all changes are controlled by the given instruction. We propose a Multi-Modal Multi-Level Transformer (M<sup>3</sup>L-Transformer) to carry out LBVE. The M<sup>3</sup>L-Transformer dynamically learns the correspondence between video perception and language semantic at different levels, which benefits both the video understanding and video frame synthesis. We build three new datasets for evaluation, including two diagnostic and one from natural videos with human-labeled text. Extensive experimental results show that M<sup>3</sup>L-Transformer is effective for video editing and that LBVE can lead to a new field toward vision-and-language research.
