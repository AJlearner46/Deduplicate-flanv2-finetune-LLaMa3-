# Deduplicate-flanv2-finetune-LLaMa3-

## FLAN v2 Cot Deduplicated Dataset 

## Data Preprocessing
- Remove instructions with less than 100 in 'targets'. 
- Dedepulicate Dataset using cosine similarity with a threshold of 0.95.

## Huggingface links
- Dataset : https://huggingface.co/datasets/ayushrupapara/flanv2_cot_dedepulicated
- Model :

## Acknowledgments
- The original dataset is provided by SirNeural/flan_v2.
- Tokenizer used: bert-base-uncased from Hugging Face.
