# Fine-Tuning LLM

![image](https://github.com/user-attachments/assets/a200c62f-b3d0-4c44-a956-f19f268fc543)

This repository contains the process of fine-tuning the **Meta-Llama-3.2-1B** model using a custom dataset to improve its performance for specific instructions.

## Fine-Tuning Process

1. **Load the dataset:** The dataset `JulianVelandia/unal-repository-dataset-train-instruct` is loaded from Hugging Face.
2. **Prepare the model:** The `meta-llama/Meta-Llama-3-8B` model is loaded and configured with LoRA (Low-Rank Adaptation) to enable parameter-efficient fine-tuning.
3. **Training:** The model is trained on the dataset with specific training arguments, including gradient accumulation and checkpoint saving.
4. **Saving and uploading:** The fine-tuned model is saved and uploaded to Hugging Face for reuse.

This approach enables efficient adaptation of large language models for specific tasks while optimizing computational resources.
