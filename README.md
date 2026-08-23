# IIITHInternship2

Generating Images and Videos using Comfy UI.

Image generation:-
Model used - SDXL Simple
Ran using Google Collab because of Hardware limitations.

Video generation:-
Model used - grok-imagine-video-1.5
Ran using Comfy Cloud.


Legal Document Summarization using LoRA
(PEFT)

In this task, I explored domain-specific fine-tuning on legal documentation. Standard language
models often struggle with complex legal vocabulary and long, statutory sentences.
Instead of training a massive model from scratch or updating all billions of weights (which is slow
and memory-heavy), I used Parameter-Efficient Fine-Tuning (PEFT) with Low-Rank
Adaptation (LoRA) on a quantized base model (QLoRA). This allowed me to train the model
quickly on a single free Google Colab GPU (T4).
