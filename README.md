# BAT
This is the official implementation in PyTorch for BAT: Behavior-Aware Temporal Contrastive Video Representation Learning

## Build with conda
Download data from anonymous account [https://drive.google.com/drive/folders/1oXim4BxsQTq0U-fKZpX_LrL6J377WKZz?usp=share_link and unzip data.7z](https://drive.google.com/file/d/100LntnP4Qen-caWl9WsVKiOedMfQWTO8/view?usp=sharing)
Unzip under the BAT folder.
```
conda env create -f BAT.yml
conda activate BAT
```
## Train
cd BAT

```
# to train the model by BAT:
python train_BAT.py --BAT

# to train the model by TCLR:
python train_TCLR.py --TCLR
