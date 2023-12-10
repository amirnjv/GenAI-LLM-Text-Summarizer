# GenAI LLM For Summarizing The Target Text

This project focuses on the exploration and practical application of generative AI using Large Language Models (LLMs). It includes a detailed examination of the generative AI lifecycle, from data collection and model selection to performance evaluation and deployment. The initiative provides an in-depth look at transformer architecture, the intricacies of LLM training processes, and the application of fine-tuning to adapt these models for specific tasks.

Additionally, the project involves using empirical scaling laws to optimize model objectives and implementing advanced training, tuning, and deployment techniques to enhance model performance within the constraints of specific projects. 

### Notebook 1
This notebook involves exploring the dialogue summarization capabilities of generative AI. The focus is on understanding how different input texts shape the model's output, and on employing prompt engineering techniques to tailor the AI's response to specific tasks. The experiment will include zero-shot, one-shot, and few-shot inferences, providing insights into how prompt engineering can optimize the performance of Large Language Models in generating concise summaries of conversations.

### Notebook 2
This notebook is dedicated to fine-tuning an existing Large Language Model from Hugging Face to enhance its dialogue summarization capabilities. The chosen model for this task is [FLAN-T5](https://huggingface.co/docs/transformers/model_doc/flan-t5), known for its high-quality, instruction-tuned ability to summarize text. The process will involve a comprehensive fine-tuning approach, with the performance of the fine-tuned model being assessed using ROUGE metrics. Additionally, the notebook will explore Parameter Efficient Fine-Tuning (PEFT), comparing its advantages against the trade-off of marginally lower performance metrics.

### Notebook 3
This notebook involves fine-tuning a FLAN-T5 model to lower its tendency to produce toxic content, leveraging Meta AI's hate speech reward model. This reward model operates as a binary classifier, distinguishing text as either "not hate" or "hate." The fine-tuning process will be carried out using Proximal Policy Optimization (PPO), with the objective of significantly reducing the toxicity in the model's outputs.
