# Trust and Safety with Llama

The [Purple Llama](https://github.com/meta-llama/PurpleLlama/) project provides tools and models to improve LLM security. This folder contains examples to get started with PurpleLlama tools.

| Tool/Model | Description | Get Started
|---|---|---|
[Llama Guard](https://llama.meta.com/docs/model-cards-and-prompt-formats/llama-guard-3) | Provide guardrailing on inputs and outputs | [Inference](./llama_guard/inference.py), [Finetuning](./llama_guard/llama_guard_customization_via_prompting_and_fine_tuning.ipynb)
[Prompt Guard](https://llama.meta.com/docs/model-cards-and-prompt-formats/prompt-guard) | Model to safeguards against jailbreak attempts and embedded prompt injections | [Notebook](./prompt_guard/prompt_guard_tutorial.ipynb)
[Code Shield](https://github.com/meta-llama/PurpleLlama/tree/main/CodeShield) | Tool to safeguard against insecure code generated by the LLM | [Notebook](https://github.com/meta-llama/PurpleLlama/blob/main/CodeShield/notebook/CodeShieldUsageDemo.ipynb)



### Running on hosted APIs
The notebooks [input_output_guardrails.ipynb](./input_output_guardrails_with_llama.ipynb),  [Purple_Llama_Anyscale](Purple_Llama_Anyscale.ipynb) & [Purple_Llama_OctoAI](Purple_Llama_OctoAI.ipynb) contain examples for running Meta Llama Guard on cloud hosted endpoints.
