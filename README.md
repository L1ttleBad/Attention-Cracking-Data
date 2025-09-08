# Attention-Cracking-Data
All data used for paper "Breaking the Attention Trap in Code LLMs: A Rejection Sampling Approach to Enhance Code Execution Prediction"

Download: https://drive.google.com/drive/folders/1aGLW8otHcFl0SguNsO0rBBQs9E5-Nd0D?usp=drive_link

------
# Models in paper are trained using:
<img width="808" height="270" alt="image" src="https://github.com/user-attachments/assets/513049ea-0162-49c9-92f4-41473b8372bc" />

Instruct Model: ``g4o_random_1w_alpaca.jsonl``
LC-Base: ``LC-Base_model_train_data.jsonl``
AC: ``AC_model_train_data.jsonl``
AC-RS: ``AC-RS_model_train_data.jsonl``

Data with "Helper" in the filename are used to train helper models: Qwen2.5-coder-7B-Instruct encountered output formatting issues when applying RS with LeetCode/Fetch/AC data, thus we combine these data with ``g4o_random_1w_alpaca.jsonl`` to train helper models to generate output for RS purpose.
