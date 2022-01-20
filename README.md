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
| Epoch   | Train_accuracy | Validation_accuracy |
|:----:|:--------------:|:------------:|:-----------:|
| 1  | 0.43061 | 0.87080 |
| 2  | 0.75104 | 0.85119 |
| 3  | 0.88098 | 0.90476 |
| 4  | 0.92256 | 0.95238 |
| 5  | 0.95478 | 0.93452 |
| 6  | 0.96206 | 0.94048 |
| 7  | 0.96544 | 0.94048 |  
## Report
report.pdf: The report for this project.
