# 🧠 Finetuning Qwen2-VL-7B-Instruct for Arabic OCR using Unsloth

This project focuses on fine-tuning [Qwen2-VL-7B-Instruct](https://huggingface.co/Qwen/Qwen2-VL-7B-Instruct) — a vision-language transformer model — on an Arabic OCR (Optical Character Recognition) task using the [Unsloth](https://github.com/unslothai/unsloth) framework.

---

## 🔍 Objective

To create a custom fine-tuned version of Qwen2-VL capable of interpreting images of Arabic text and producing accurate textual output.

---

## 🛠️ Tools & Frameworks

- **Unsloth**: Efficient LLM fine-tuning library with support for vision-language models.
- **Qwen2-VL-7B-Instruct**: Multimodal model supporting text and image inputs.
- **Hugging Face Datasets & Transformers**: For model and tokenizer management.
- **BitsAndBytes**: For 8-bit quantization support during training.
- **PyTorch**: As the deep learning backend.

---

## 📁 Dataset
For this project, we used the [MohamedRashad/arabic-img2md](https://huggingface.co/datasets/MohamedRashad/arabic-img2md) dataset a synthetic dataset containing around 15,000 examples of PDF pages paired with their Markdown counterparts. As mentioned on the HuggingFace plateform, it contains mostly Arabic text but also includes examples with English text created to enable OCR and Markdown extraction from Arabic documents
