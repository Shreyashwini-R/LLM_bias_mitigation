# LLM Bias Mitigation

## 📖 Overview  
This repository explores various techniques for **mitigating biases** in **Large Language Models (LLMs)** to ensure **fair and ethical AI-generated responses**. The project implements multiple debiasing strategies, including:  

- **DPO (Direct Preference Optimization)** – Bias mitigation through preference-based training.  
- **Bias evaluation metrics** – Assess fairness in models.  
- **LoRA (Low-Rank Adaptation)** – Efficient fine-tuning for bias reduction.  
- **MEMIT (Mass-Editing Memory in Transformers)** – Targeted bias correction.  
- **REPE (Retrieval-Augmented Prompt Engineering)** – Refining model responses for fairness.  

---

## 🚀 Features  

- **Comprehensive Bias Evaluation** – Tools to measure biases before and after mitigation.  
- **DPO-Based Fine-Tuning** – Preference-based training to improve fairness.  
- **LoRA Adaptation** – Lightweight, efficient fine-tuning for targeted corrections.  
- **MEMIT Editing** – Controlling memory to reduce biased outputs.  
- **REPE Strategies** – Prompt engineering to counteract model biases.  

---

## 🔧 Installation  
Clone the repository
## Usage
## 1. Evaluating Bias
Run the evaluation script to analyze the model's fairness:

```python evaluate_bias.py --model model_name```
## 2. DPO Bias Mitigation
Fine-tune a model using Direct Preference Optimization:

```python dpo_mitigation.py --model model_name --dataset dataset_path```
## 3. LoRA-Based Bias Mitigation
Apply LoRA fine-tuning to mitigate biases:

```python lora_mitigation.py --model model_name --lora_weights lora_path```
## 4. MEMIT Bias Correction
Modify memory representations to address biases:

```python memit_mitigation.py --model model_name --edit_target target_bias```
## 5. REPE Bias Mitigation
Use retrieval-augmented prompts for fairness:

```python repe_mitigation.py --model model_name --prompt_strategy strategy_type```
## Results and Benchmarking
After mitigation, run the bias evaluation script again to compare the results:

```python evaluate_bias.py --model model_name --after_mitigation```
