# OSLMRec: Is It Sufficient to Harness Only Small Language Models for Recommendation?

# Train and Test OSLMRec:

## glm3
### ml
- incremental pre-training
  - llamafactory-cli train examples/zone/glm3/lora_pt_ml.yaml
- fine tuning
  - llamafactory-cli train examples/zone/glm3/lora_sft_ml.yaml
- test
  - llamafactory-cli train examples/zone/glm3/lora_pd_ml.yaml
### yelp
- incremental pre-training
  - llamafactory-cli train examples/zone/glm3/lora_pt_yelp.yaml
- fine tuning
  - llamafactory-cli train examples/zone/glm3/lora_sft_yelp.yaml
- test
  - llamafactory-cli train examples/zone/glm3/lora_pd_yelp.yaml


## llama2
### ml
- incremental pre-training
  - llamafactory-cli train examples/zone/llama2/lora_pt_ml.yaml
- fine tuning
  - llamafactory-cli train examples/zone/llama2/lora_sft_ml.yaml
- test
  - llamafactory-cli train examples/zone/llama2/lora_pd_ml.yaml
### yelp
- incremental pre-training
  - llamafactory-cli train examples/zone/llama2/lora_pt_yelp.yaml
- fine tuning
  - llamafactory-cli train examples/zone/llama2/lora_sft_yelp.yaml
- test
  - llamafactory-cli train examples/zone/llama2/lora_pd_yelp.yaml


## gemma2
### ml
- incremental pre-training
  - llamafactory-cli train examples/zone/gemma2/lora_pt_ml.yaml
- fine tuning
  - llamafactory-cli train examples/zone/gemma2/lora_sft_ml.yaml
- test
  - llamafactory-cli train examples/zone/gemma2/lora_pd_ml.yaml
### yelp
- incremental pre-training
  - llamafactory-cli train examples/zone/gemma2/lora_pt_yelp.yaml
- fine tuning
  - llamafactory-cli train examples/zone/gemma2/lora_sft_yelp.yaml
- test
  - llamafactory-cli train examples/zone/gemma2/lora_pd_yelp.yaml

## llama-factory ([here](src/README.md))