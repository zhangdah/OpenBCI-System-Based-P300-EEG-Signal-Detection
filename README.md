# Overview of the Project
This repository reuses the state-of-the-art One Convolution Layer Neural Network (OCLNN) to compare the impacts of different channel selection methods. By filtering 64 channels down to the most effective 8 channels, 4
channels, and further to a single channel, the P300 classification accuracy reduces from 92% to 89%, 88%, and 85% respectively. In terms of character spelling accuracy, reducing the number of channels to 8 did not increase the effort required to attain 100% accuracy, while reducing it to 4 channels needed two additional epochs per character to get 100%. However, reducing to only one channel fails to achieve 100% character spelling accuracy.  within 15 episodes.

# Reference
The dataset used in this project is BCI Competition II - Data set IIb
The model architecture is borrowed from this link, and the channel reduction methods are implemented on the model structure.

Article citation:
@Article{p300cnnt_2021,
  author = {Montserrat Alvarado-González and Gibran Fuentes-Pineda and Jorge Cervantes-Ojeda},
  title = {A few filters are enough: Convolutional neural network for P300 detection},
  journal = {Neurocomputing},
  volume = {425},
  pages = {37--52},
  year = {2021},
}
