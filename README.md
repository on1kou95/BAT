# BAT
This is the official implementation in PyTorch for BAT: Behavior-Aware Temporal Contrastive Video Representation Learning

## Build with conda
Download data from anonymous account https://drive.google.com/drive/folders/1oXim4BxsQTq0U-fKZpX_LrL6J377WKZz?usp=share_link and unzip data.7z
```
conda env create -f BAT.yml
conda activate BAT
```
## Train
cd BAT/video_cls

```
# to train the model by BAT:
python train.py --BAT

# to train the model by TCLR:
python train.py --TCLR
