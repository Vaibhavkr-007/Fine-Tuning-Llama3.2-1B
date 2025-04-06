base_model: meta-llama/Llama-3.2-1B
library_name: peft
license: apache-2.0
datasets:
- FreedomIntelligence/medical-o1-reasoning-SFT
language:
- en
metrics:
- bleu
- bertscore
pipeline_tag: question-answering
tags:
- medical
---
# Model Card for Llama3.2-1B-FineTuned-MedicalQA

## Model Details

### Model Description

This is a fine-tuned version of the **Llama-3.2-1B** base model, optimized for **medical question answering** tasks. The model was fine-tuned using the **FreedomIntelligence/medical-o1-reasoning-SFT** dataset, which is specifically designed for reasoning in medical domains.

- **Developed by:** Meta-Llama
- **Model type:** Language Model
- **Fine-tuned from model:** meta-llama/Llama-3.2-1B
- **Fine-tuned dataset:** [FreedomIntelligence/medical-o1-reasoning-SFT](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)
- **Languages Supported:** English
- **License:** [Model License Information]

### Model Sources

- **Repository:** (https://huggingface.co/meta-llama/Llama-3.2-1B)
- **Dataset used for fine-tuning:** [FreedomIntelligence/medical-o1-reasoning-SFT](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)

## Uses

### Direct Use

This model is designed to answer questions related to medical reasoning, making it useful for applications in healthcare AI systems, medical research assistants, or clinical decision support systems.

