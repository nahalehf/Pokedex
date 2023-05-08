# Pokedex

DeepLearning_FinalProject includes all the code required for training the classifier, segmentation, and final test. Please start by running the cells one by one. The non-maximum supression is also included in the code. Please remember to download the full dataset from https://www.kaggle.com/datasets/lantian773030/pokemonclassification. 

SAM_Pokedex includes the tests using SAM for segmentation and the best trained classifier. Please remember to download the vi_h version of SAM from https://github.com/facebookresearch/segment-anything.git and edit the path to the SAM model in the code. The best classifier, dataset, and test folder also need to be downloaded from this repository.

StyleTransfer_Pokedex contains the code for generating new data and adding it to the 898 class Pokemon dataset. The script can also be used to fine-tune a resnet50 on this new dataset and test it on some test images. The Complete dataset can be downloaded from https://www.kaggle.com/datasets/hlrhegemony/pokemon-image-dataset.
