## SOIL: Contrastive Second-Order Interest Learning for Multimodal Recommendation



## Datasets

The processed datasets can be downloaded from [Google Drive](https://drive.google.com/drive/folders/13Mv_5Y5yLuOScEr8d4Z9Y6vMzjRry5TO?usp=drive_link).

You can put the downloaded datasets in `./data/`.

## Requirements

* Python 3.7.11
* PyTorch 1.11.0
* numpy 1.21.5

You can create the environment with conda:

```
conda env create -f environment.yml
```


## Run

You can train the model by running:

```bash
python main.py -m SOIL -d baby
or
bash train.sh
```

The results are saved in `./log`. We also provide training logs in `./log`.
## Acknowledgement

The structure of this code is largely based on [MMRec](https://github.com/enoche/MMRec) and [MGCN](https://github.com/demonph10/MGCN). Thanks for their excellent work!
