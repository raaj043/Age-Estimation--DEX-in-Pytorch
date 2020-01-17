# Age-Estimation--DEX-in-Pytorch
This repository is the Pytorch implementation of DEX paper: 
Deep expectation of real and apparent age from a single image without facial landmarks

How to run the code:
1. Downlaod the IMDB-WIKI dataset from https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/
2. Download this repository
3. Go to train_imdb_wiki_adience.csv file in the path IMDB_WIKI/file_paths/. Now change the root path to the downloaded images in the csv file. If you dont want to use the Adience dataset for training, just remove all the paths having Adience from the csv file.
4. Now goto IMDB_WIKI/source_code and run the code like CUDA_VISIBLE_DEVICES=0 python vgg16_imdb_train.py. Your training should start now!


>@article{Rothe-IJCV-2016,  
  author = {Rasmus Rothe and Radu Timofte and Luc Van Gool},  
  title = {Deep expectation of real and apparent age from a single image without facial landmarks},  
  journal = {International Journal of Computer Vision (IJCV)},  
  year = {2016},  
  month = {July},  
}
