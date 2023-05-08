# Pokedex

DeepLearning_FinalProject includes all the code required for training the classifier, segmentation, and final test. Please start by running the cells one by one. The non-maximum supression is also included in the code. Please remember to download the full dataset from https://www.kaggle.com/datasets/lantian773030/pokemonclassification. Or alternatively, you can skip the training process and use the best trained model (included with the report on canvas).

SAM_Pokedex includes the tests using SAM for segmentation and the best trained classifier. Please remember to download the vi_h version of SAM from https://github.com/facebookresearch/segment-anything.git and edit the path to the SAM model in the code. The dataset, test folder, and best classifier also need to be downloaded (included along with the report on canvas).

StyleTransfer_Pokedex contains the code for generating new data and adding it to the 898 class Pokemon dataset. The script can also be used to fine-tune a resnet50 on this new dataset and test it on some test images. The Complete dataset can be downloaded from https://www.kaggle.com/datasets/hlrhegemony/pokemon-image-dataset. The best trained model was included with the report on canvas.
