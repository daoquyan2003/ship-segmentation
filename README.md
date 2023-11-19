# Ship Segmentation on Satellite Images using various U-Net models

## Description

Mid-Term Project for Computer Vision Class INT3412E 20

Topic: Semantic Segmentation on Satellite Imagery Dataset, namely Airbus Ship Detection Dataset.

Main Technologies: PyTorch, Lightning, Hydra, WanDB

Some implemented models: U-Net, U-Net with ResNet backbone, R2U-Net, Attention U-Net, R2-Attention U-Net, TransU-Net U-Net++, U-Net3+

Some implemented loss functions: LossBinary (BCE + Jaccard), Dice Loss, Focal Loss, Mixed Loss (Dice + Focal), Lovasz Loss,...

## How to use this project

- Make sure Python is installed

- Run `pip install -r requirements.txt` to install necessary dependencies

- You can also set up on Docker using Dockerfile and docker-compose

- The configuration can be modified using [Hydra](https://hydra.cc/)

- Run `python src/train.py` to start training the model.
