# DACON_CV_Outlier!
![20220606_140450](https://user-images.githubusercontent.com/84311270/172098410-5aa5075f-12ec-40a5-8c47-94372d7536b1.png)


사물의 종류와 상태를 분류하는 컴퓨터 비전 알고리즘 개발

## Dataset
train_df.csv  
index : 이미지와 매칭되는 인덱스  
file_name : 이미지 파일명  
class : 사물명  
state : 사물의 상태  
label : 최종 제출 형식  

test_df.csv  
index : 이미지와 매칭되는 인덱스  
file_name : 이미지 파일명  
 

sample_submission.csv  
index : test_df.csv의 인덱스  
label : 추론값  

## Model
다양한 Data Augmentation 기법을 사용하여 데이터를 증강시키고 EfficientNetB1 모델을 사용하여 학습.
