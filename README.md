# Ship Segmentation on Satellite Images using various U-Net models

## Members
- Đào Quý An - 21020602
- Dương Quang Minh - 21020219
- Lê Văn Bảo - 21020171
- Tống Minh Trí - 21020249

## Description

Mid-Term Project for Computer Vision Class INT3412E 20

This repo was made by UET-VNU students

Topic: Semantic Segmentation on Satellite Imagery Dataset, namely Airbus Ship Detection Dataset (Dataset: https://www.kaggle.com/competitions/airbus-ship-detection/data).

Main Technologies: PyTorch, Lightning, Hydra, WanDB

Some implemented models: U-Net, U-Net with ResNet backbone, R2U-Net, Attention U-Net, R2-Attention U-Net, TransU-Net, U-Net++, U-Net3+

Some implemented loss functions: LossBinary (BCE + Jaccard), Dice Loss, Focal Loss, Mixed Loss (Dice + Focal), Lovasz Loss,...

## How to use this project

- Clone this repo: `git clone https://github.com/daoquyan2003/ship-segmentation.git`

- Make sure Python is installed (Optional: Anaconda `conda create -n airbus` and `conda activate airbus`)

- Run `pip install -r requirements.txt` to install necessary dependencies

- You can also set up on Docker using Dockerfile and docker-compose

- The configuration can be modified using [Hydra](https://hydra.cc/)

- Run `python src/train.py` to start training the model.

## Optional: Deploy with Triton and CVAT
- Checkpoints model U-Net34 + Lovasz Loss + size 768x768 + subset 12000: https://drive.google.com/file/d/1BKEtCd3AjOtt2u7DYAUlouIiYQILgCPL/view?usp=sharing
- Read README.md in folder triton/ and cvat/ for more details
