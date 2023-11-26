# Ship Segmentation on Satellite Images using various U-Net models

## Members
- Đào Quý An - 21020602
- Dương Quang Minh - 21020219
- Lê Văn Bảo - 21020171
- Tống Minh Trí - 21020249

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

## Optional: Deploy with Triton and CVAT
- Checkpoints: https://drive.google.com/file/d/1BKEtCd3AjOtt2u7DYAUlouIiYQILgCPL/view?usp=sharing
- Read README.md in folder triton/ and cvat/ for more details
