# Modeling-using-CNN
코랩 링크
https://colab.research.google.com/drive/1t4HoFewHoklFDGEMaVe4hDqAQuPyTh4C#scrollTo=kFGe2FJanqY0

Batch Size=64, 128, 512로 바꾸며 훈련 및 비교
결과: https://docs.google.com/document/d/1_6HHEhcqWNPHAq7I4C4uYHT0ED9NscgPdNtESfzNmvo/edit?usp=sharing

### 라이브러리 설치
`
!pip install pillow
!pip install numpy
!pip install tensorflow==1.14.0
!pip install Keras==2.2.5
`

### 코드 수정 부분
`
y_vloss = history.history['val_loss']
y_loss = history.history['loss']
y_vacc = history.history['val_acc']
y_acc = history.history['acc']
`
 history에서 사용하는 key에 맞게 수정 (Keras 버전 == 2.2.5)