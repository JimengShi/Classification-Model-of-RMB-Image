# Classification-Model-of-RMB
Based on 100 pieces of 1￥ and 100 pieces of 100￥, a classification model is built to achieve binary classification task. A couple of real life data have been tested with a good accuracy.

## Six steps for machine learning projects
- Step 1: Data (include data split, data analysis, data augmentation, data load)
- Step 2: Model (leNet is used in this project, check out `Model folder`)

<div align="center">
<img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/model.png" height="200px" alt="Model" >
</div>

- Step 3: Loss function (cross entropy is used in this project)
- Step 4: Optimizer (Stochastic Gradient Descent is used in this project)
- Step 5: Iteratively training
- Step 6: Model Estimation

<div align="center">
<img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/Six%20steps.png" height="500px" alt="Steps" >
</div>

## Model performance
The performance of this classification model is good, accuracy is about 100%, loss value is 0.0021 with 10 epoches training.

- Test Demo:
<div align="center">
<img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/100_1.png" height="300px" alt="100_1" ><img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/100_2.png" height="300px" alt="100_2" ><img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/100_3.png" height="300px" alt="100_3" ><img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/100_4.png" height="300px" alt="100_4" >    
</div>

- The change loss value:
<div align="center">
<img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/loss%20function.png" height="400px" alt="Loss" >
</div>

- The change of accuracy:
<div align="center">
<img src="https://github.com/JimengShi/Classification-Model-of-RMB/blob/master/images/accuracy.png" width="800px" alt="Accuracy" >
</div>

## How to run
**Environment:**
- Window 10
- Python 3.7.4
- Pycharm 2020.1.2
- Pytorch: 1.5.0 (Both CPU and GPU would be fine to run this project)

**Run steps:**
- set good environment
- clone this repository
- run 1_split_dataset.py at first, then you will find training set, validation set and test set in `data folder`.
- run 2_train_lenet.py to train model
- run RMB_data_augmentation.py to train model again after data augmentation
