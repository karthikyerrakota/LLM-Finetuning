# LLM-Finetuning

This repository contains code for finetuning of LLMs using QLORA method.

In this we took the MEDQUAD dataset to finetune the LLAMA model. A sample of 1000 training examples are used to fien tune the model.
After the finetuning of the model, we created a new model and saved this into Huggingface.

Below are the results for a medical prompt

The first image shows the result after querying the foundation model. While the second image shows the result of finetuned model.

Image 1
<img width="1283" alt="Screenshot 2024-03-20 at 7 19 44 PM" src="https://github.com/karthikyerrakota/LLM-Finetuning/assets/54073737/82e2da11-7bdd-4903-a1de-259b09ad10c3">

Image 2
<img width="1307" alt="Screenshot 2024-03-20 at 7 20 03 PM" src="https://github.com/karthikyerrakota/LLM-Finetuning/assets/54073737/b558edda-f1d5-4e29-b2ea-4b8638b743f6">

we can clearly see after the finetuning the model is able to output the desired result.
