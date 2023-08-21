# Overview of the Project
This repository reuses the state-of-the-art One Convolution Layer Neural Network (OCLNN) [1] to compare the impacts of different channel selection methods. Reducing channels from 64 to 8, 4, and 1 results in decreasing P300 accuracy (92%, 89%, 88%, and 85% respectively). While 8 channels maintain character accuracy, 4 channels require two more epochs per character for 100% accuracy. However, one channel doesn't achieve 100% accuracy in 15 episodes. The dataset used in this project is [BCI Competition II - Data set IIb](http://www.bbci.de/competition/ii/). Part of the code from this [repository](https://github.com/gibranfp/P300-CNNT) is used.

# Reference
[1] Shan, H., Liu, Y., & Stefanov, T. P. (2018, July). A Simple Convolutional Neural Network for Accurate P300 Detection and Character Spelling in Brain Computer Interface. In Proceedings of the 27th International Joint Conference on Artificial Intelligence, Stockholm, Sweden, 13-19 July 2018, 1604-1610. [[link](https://www.ijcai.org/Proceedings/2018/222)]
