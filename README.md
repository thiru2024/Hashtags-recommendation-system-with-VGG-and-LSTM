# Hashtags-recommendation-system-with-VGG-and-LSTM

This is a PyTorch implementation of a hashtag generator. The generator takes in an input image and tries to generate associated hashtags. The generator is based off a sequence to sequence model and is trained on the HARRISON datset.

## Prerequisites
Python 2.7
PyTorch 0.4
tqdm 4.2.3
## Installation
Clone the repository
git clone https://github.com/thiru2024/Hashtags-recommendation-system-with-VGG-and-LSTM
Setup Data
Download and extract the HARRISON dataset.
git clone https://github.com/minstone/HARRISON-Dataset
Download a torrent service such as Deluge. Then torrent the HARRISON-Dataset/HARRISON/HARRISON_dataset.torrent file.
Extract the images by untarring the result of the torrent, HARRISON_full.tar.
tar xzf HARRISON_full.tar
Create a soft link to the data.
