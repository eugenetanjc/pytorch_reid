<h1 align="center"> Pytorch ReID </h1>

## Choice of solution
Pytorch ReID combines the advantages of both verification models and identification models. It is also easier and faster to implement compared to other methods that require PCA to learn embeddings, or require large GPU usage. 

## Comparison with traditional trackers
DeepSort uses a simple feature extractor, which is not sufficient for capturing the different body features and regions (e.g. shoes, glasses) that help in person reidentification. FairMOT requires much greater data preprocessing due to HeatMap.

## Implementation
Code for running the model training and testing are in ReID.ipynb file.

## Evaluation Results
Rank@1:0.879157 Rank@5:0.951010 Rank@10:0.967043 mAP:0.718611

## Citation
Basic Model
```bib
@article{zheng2018discriminatively,
  title={A discriminatively learned CNN embedding for person reidentification},
  author={Zheng, Zhedong and Zheng, Liang and Yang, Yi},
  journal={ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)},
  volume={14},
  number={1},
  pages={13},
  year={2018},
  publisher={ACM}
}

@article{zheng2020vehiclenet,
  title={VehicleNet: Learning Robust Visual Representation for Vehicle Re-identification},
  author={Zheng, Zhedong and Ruan, Tao and Wei, Yunchao and Yang, Yi and Mei, Tao},
  journal={IEEE Transaction on Multimedia (TMM)},
  year={2020}
}
```
