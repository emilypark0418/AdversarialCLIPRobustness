# Final Project: Assessing CLIP Robustness on Adversarial Attacks
- COMS6998 Practical Deep Learning System Performance (Fall 2022, Prof. Parijat Dube)
- Coauthors: **Chaewon (Emily) Park**, Hnin Ookhin

## Library Requirements 

We will be using OpenAI's CLIP model from here: https://github.com/openai/CLIP. In order to use CLIP, we will need to install following libraries. 

```
$ conda install --yes -c pytorch pytorch=1.7.1 torchvision cudatoolkit=11.0
$ pip install ftfy regex tqdm pandas
$ pip install git+https://github.com/openai/CLIP.git
```

## Datasets 
Datasets used in this project can be downloaded here: TODO - add link to Google folder with our zip data 

These should all be placed in `/data/` folder.

## Inference 
For inference and cacluating top-k metric presented, please refer to `OpenAIClIP_ZeroShot_Inference.ipynb.`
