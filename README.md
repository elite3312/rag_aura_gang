# hipporag

## install

```sh
#conda bin is at:
#/home/perry/miniconda3/bin

conda create -n hipporag python=3.10 # create a venv called hipporag
conda activate hipporag
pip install hipporag
```

## running experiments

- set environment variables
  
```sh
export CUDA_VISIBLE_DEVICES=0,1,2,3 # change according to how many gpus you have
#export HF_HOME=<path to Huggingface home directory>
export OPENAI_API_KEY=<open ai key>   # if you want to use OpenAI model
conda activate hipporag
```

- run example.py

## notes

- HippoRAG/main.py has some configs that we can tune