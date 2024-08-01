# Fine-Tune a Small LLM with JSON Data
For us data nerds with limited computing power, spotty free time, and tight budgets, fine-tuning an LLM may seem daunting, even if it is relatively small (<2B).

I've done all the work for you. Using an A100 runtime in Colab, I got Deepseek Coder fine-tuning with some JSON data for under a dollar. Hopefully this helps someone else, too! Script currently supports DeepseekCoder, TinyLlama 1.1B Chat, Microsoft Phi 1.5, and Llama 2 7b.

It also supports downloading the fine-tuned model as a .zip file to your Google Drive, then opening it and using it later.
