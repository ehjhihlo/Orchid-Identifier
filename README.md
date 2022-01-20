# Orchid-Identifier
A Deep Learning Model to Identify Wild Orchids of Taiwan

## Dataset
Dataset can be downloaded from:  
https://drive.google.com/drive/folders/1tfILR7tSIv_5PV8HaUa7yx7F8jUPkYv8?usp=sharing  
The dataset file including train(Including 935 pictures), test(Including 166 pictures), and
label_versus_Orchid_name.xlsx, the label and the corresponding Orchid name.  

### **Training Dataset**  
![image](https://github.com/ehjhihlo/Orchid-Identifier/blob/main/image/train_set.png?raw=true)  
### **Testing Dataset**  
![image](https://github.com/ehjhihlo/Orchid-Identifier/blob/main/image/test_set.png?raw=true)  
  
## Code
train.py & train.ipynb: The python code for training.

### **The input image after normalization**  
![image](https://github.com/ehjhihlo/Orchid-Identifier/blob/main/image/1_batch_normalized.png?raw=true)  
  
## Training result
The training result folder includes the training result of the project.  
The csv file includes image filename, true label and predicted label.  
The training accuracy are shown below:

| Epoch   | Train_accuracy | Validation_accuracy | Train_loss | Validation_loss |
|:----:|:-----:|:-------:|:-------:|:-------:|
| 001  | 0.43061 | 0.87080 | 2.00532 | 0.84623 |
| 002  | 0.75104 | 0.85119 | 0.93089 | 0.37949 |
| 003  | 0.88098 | 0.90476 | 0.48639 | 0.31409 |
| 004  | 0.92256 | 0.95238 | 0.31368 | 0.15387 |
| 005  | 0.95478 | 0.93452 | 0.20603 | 0.19232 |
| 006  | 0.96206 | 0.94048 | 0.15989 | 0.29069 |
| 007  | 0.96544 | 0.94048 | 0.13352 | 0.23897 |
## Report
report.pdf: The report for this project.
