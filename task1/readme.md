To run the code, please first create a /data folder 

`SimCLR_pretrain.ipynb` pretrains a resnet18 with SimCLR on STL10 dataset

`classification_eval.ipynb` trains and evaluates classification models with raw/pretrained resnet18. Linear classification protocol and supervised learning with finetuning are both performed.

To train the classification model with feature extractor pretrained with SimCLR, please make sure that the  `weight_path` is set to \path\to\the\saved\SimCLR\weight\path.
