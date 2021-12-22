# PER-FORMER
This repository contains a novel self-attention based person re-identification architecture. 
The proposed architecture outperformed CNN based re-id architectures when evaluated on three public re-id benchmarks i.e. Market1501, DukeMTMC-ReID and MSMT17. 
The complete code along with pretrained models is shared via this repository.

# Datasets
Install [torchreid](https://github.com/KaiyangZhou/deep-person-reid). Person Re-id datasets can be downloaded from the links given below. Extract the datasets and place in the respective sub-folders in the "reid-data" folder.

## Market1501
Market 1501 dataset is an open-access dataset and can be downloaded from [Openlink](http://zheng-lab.cecs.anu.edu.au/Project/project_reid.html)

## DukeMTMC-reID
DukeMTMC-reID dataset is an open-access dataset, the dataset can be downloaded via GoogleDriver and BaiduYun, the [download links](https://github.com/sxzrt/DukeMTMC-reID_evaluation#download-dataset) are shared by the authors of DukeMTMC-ReID dataset via their [github repository](https://github.com/sxzrt/DukeMTMC-reID_evaluation). The authors of the dataset are very generous to handle the queries regarding dataset download links as mentioned [here](https://github.com/sxzrt/DukeMTMC-reID_evaluation#download-dataset).

## MSMT17
MSMT17 dataset can be downloaded by following the detailed instructions available [here](https://www.pkuvmc.com/dataset.html)

# Evaluation
Performer(base) and Performer(SCM) training models can be downloaded from [GoogleDriver](https://drive.google.com/drive/folders/1t5IyNFMUzmsdBqz0nyA1rjxiuaF9_kTI?usp=sharing)

Place the trained weights in the trained-models folder and update the paths in the evaluation script.

Evaluate the models using command: python eval_performer.py


# Citations
If you find this code useful to your research, please cite the following paper.

@article {**PER-FORMER: Rethinking Person Re-identification Using Transformer Augmented with Self-Attention and Contextual Mapping**, Under Review in TVCJ}
