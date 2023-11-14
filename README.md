# Conceptual Design Generation Using Large Language Models
## Paper
[Arxiv link](https://arxiv.org/abs/2306.01779)


## Repo structure
├─ evaluations &emsp; &emsp;# code for computational evaluation study\
│  ├─ base_evaluation.ipynb &emsp; &emsp;# evaluations for the "GPT-3 Base" generated design solutions\
│  ├─ few_shot_evaluation.ipynb &emsp; &emsp;# evaluations for the "GPT-3 Zero-Shot" generated design solutions\
│  └─ zero_shot_evaluations.ipynb &emsp; &emsp;# evaluations for the "GPT-3 Few-Shot" generated design solutions\
│ \
├─ prompt_engineering &emsp; &emsp;# production of all GPT-3 generated solutions for each generated design solutions\
│  ├─ data &emsp; &emsp;# CSV files of all the GPT-3 generated solutions for each generated design solutions\
│  ├─ few_shot.py &emsp; &emsp;# code to generate design solutions using GPT-3 few shot method\
│  ├─ zero_shot.py &emsp; &emsp;# code to generate design solutions using GPT-3 zero shot method\
│ \
├─ sentence_embeddings &emsp; &emsp;# scratch file (outdated) and AmazonTurk Crowdsourced design solutions\
│  ├─ data &emsp; &emsp;# CSV files of all the AmazonTurk Crowdsourced design solutions\
│  ├─ scratch_file_outdated.ipynb &emsp; &emsp;# outdated scratch notebook with miscellaneous code\

