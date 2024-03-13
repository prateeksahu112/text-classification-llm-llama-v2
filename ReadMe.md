# Text Classification with LLM - LLAMA-v2

#### Weights Conversion - [3] Convert llama weights to binaries 

    python3 convert_llama_weights_to_hf.py --input_dir binary/llama-v2/llama-2-7b --model_size 7B --output_dir binary

#### Referances:
1. https://www.kaggle.com/code/lucamassaron/fine-tune-llama-2-for-sentiment-analysis 
2. https://reneelin2019.medium.com/mac-m1-m2-gpu-support-in-pytorch-a-step-forward-but-slower-than-conventional-nvidia-gpu-40be9293b898
3. https://huggingface.co/docs/transformers/main/en/model_doc/llama
4. https://github.com/facebookresearch/llama/blob/main/download.sh
5. https://llama.meta.com/llama-downloads/