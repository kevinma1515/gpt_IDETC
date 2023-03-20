# Conceptual Design Generation Using Large Language Models\
├─ evaluations<pre>     <\pre>                          # code for computational evaluation study\
│  ├─ base_evaluation.ipynb<pre>         <\pre>         # evaluations for the "GPT-3 Base" generated design solutions\
│  ├─ few_shot_evaluation.ipynb<pre>         <\pre>     # evaluations for the "GPT-3 Zero-Shot" generated design solutions\
│  └─ zero_shot_evaluations.ipynb<pre>         <\pre>   # evaluations for the "GPT-3 Few-Shot" generated design solutions\
│ \
├─ prompt_engineering<pre>         <\pre>     # production of all GPT-3 generated solutions for each generated design solutions\
│  ├─ data<pre>         <\pre>                # CSV files of all the GPT-3 generated solutions for each generated design solutions\
│  ├─ few_shot.py<pre>         <\pre>         # code to generate design solutions using GPT-3 few shot method\
│  ├─ zero_shot.py<pre>         <\pre>        # code to generate design solutions using GPT-3 zero shot method\
│ \
├─ sentence_embeddings<pre>         <\pre>                           # scratch file (outdated) and AmazonTurk Crowdsourced design solutions\
│  ├─ data<pre>         <\pre>                                       # CSV files of all the AmazonTurk Crowdsourced design solutions\
│  ├─ scratch_file_outdated.ipynb<pre>         <\pre>                # outdated scratch notebook with miscellaneous code\
