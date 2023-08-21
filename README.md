# Overview of the Project
This repository reuses the state-of-the-art One Convolution Layer Neural Network (OCLNN) [1] to compare the impacts of different channel selection methods. By filtering 64 channels down to the most effective 8 channels, 4
channels, and further to a single channel, the P300 classification accuracy reduces from 92% to 89%, 88%, and 85% respectively. In terms of character spelling accuracy, reducing the number of channels to 8 did not increase the effort required to attain 100% accuracy, while reducing it to 4 channels needed two additional epochs per character to get 100%. However, reducing to only one channel fails to achieve 100% character spelling accuracy.  within 15 episodes. The dataset used in this project is [BCI Competition II - Data set IIb](http://www.bbci.de/competition/ii/). The model parameters are adjusted based on the model architecture from this [repository](https://github.com/gibranfp/P300-CNNT).

# Reference
[1] Shan, H., Liu, Y., & Stefanov, T. P. (2018, July). A Simple Convolutional Neural Network for Accurate P300 Detection and Character Spelling in Brain Computer Interface. In Proceedings of the 27th International Joint Conference on Artificial Intelligence, Stockholm, Sweden, 13-19 July 2018, 1604-1610. [[link](https://www.ijcai.org/Proceedings/2018/222)]
