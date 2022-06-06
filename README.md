# DACON_CV_Outlier!
[20220606_140450](https://user-images.githubusercontent.com/84311270/172098250-286f78cf-d5b0-432d-9a74-f9f230be89f4.png)

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
