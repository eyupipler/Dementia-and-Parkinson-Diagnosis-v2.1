# Vbai-DPA 2.1 Versions (EN)

| Model | Test Size | Params | FLOPs | mAPᵛᵃᴵ | CPU b1 | V100 b1 | V100 b32 |
|-------|-------|--------|-------|--------|--------|---------|----------|
| **Vbai-DPA 2.1f** | _224_ | 12.87M | 0.15B | %78.56 | 7.02ms | 3.51ms | 0.70ms |
| **Vbai-DPA 2.1c** | _224_ | 51.48M | 0.56B | %78.0 | 18.11ms | 9.06ms | 1.81ms |
| **Vbai-DPA 2.1q** | _224_ | 104.32M | 2.96B | %79.01 | 38.67ms | 19.33ms | 3.87ms |

## Description

The Vbai-DPA 2.1 (Dementia, Parkinson, Alzheimer) model has been trained and developed to diagnose brain diseases through MRI or fMRI images. It shows whether the patient has Parkinson's disease, dementia status and Alzheimer's risk with high accuracy. According to Vbai-DPA 2.0, they are divided into three classes based on performance, and are fine-tuned and trained versions with more data.

#### Audience / Target

Vbai models are developed exclusively for hospitals, health centres and science centres.

### Classes

 - **Alzheimer's disease**: The sick person definitely has Alzheimer's disease.
 - **Average Risk of Alzheimer's Disease**: The sick person may develop Alzheimer's disease in the near future.
 - **Mild Alzheimer's Risk**: The sick person has a little more time to develop Alzheimer's disease.
 - **Very Mild Alzheimer's Risk**: The sick person has time to reach the level of Alzheimer's disease.
 - **No Risk**: The person does not have any risk.
 - **Parkinson's Disease**: The person has Parkinson's disease.

[![Open in Hugging Face Spaces](https://huggingface.co/front/assets/huggingface_logo-noborder.svg)](https://huggingface.co/spaces/Neurazum/Vbai-DPA-2.1)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run app.py
   ```
