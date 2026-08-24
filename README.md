# penr-oz-llm-qlora-finetune

Fine-tunes an imported LLM base model using QLoRA on limited hardware. It follows the
method laid out in
[How to Fine-Tune an LLM: An End-to-End Guide](https://towardsdatascience.com/how-to-fine-tune-an-llm-an-end-to-end-guide/)
(Sam Black, Towards Data Science, Aug 2026), and borrows its service shape — FastAPI
app, background jobs, structured logging — from
[penr-oz-neural-network-v3-torch-ddp](https://github.com/derinworks/penr-oz-neural-network-v3-torch-ddp).

## Target Hardware

| Resource | Minimum |
|----------|---------|
| GPU VRAM | 16 GB   |
| RAM      | 32 GB   |
| Disk     | 300 GB  |
