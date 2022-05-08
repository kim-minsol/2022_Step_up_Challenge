## Step_up Challenge

+ 2022_1st_AI_practical_course 마지막 주차에 진행한 프로젝트   
+ Mediapipe 및 OpenCv 활용

+ 주제: Face ID

### 🚩 순서
1) 얼굴 데이터셋 수집
2) 모델 학습
3) 📷 웹캠 -> 얼굴 찾기
4) 얼굴 인식


+ 얼굴 인식 과정에서 OpenCv에서 제공하는 얼굴 분류 모델인 LBPH를 사용하였지만 정확도가 너무 낮았음

   -> Face recognition 라이브러리 사용

### 🧑 Face recognition
+ HOG 추출하여 얼굴 찾음
+ dlib 활용하여 얼굴의 랜드마크 추출
+ 눈, 코, 입이 이미지의 가운데로 오도록 조정
+ 얼굴 이미지를 128 차원의 벡터로 임베딩
+ 선형 분류기로 얼굴 분류


*[Face_recognition.pdf](https://github.com/kim-minsol/2022_Step_up_Challenge/blob/main/Face_recognition.pdf) 참고하시면 프로젝트 전반적인 과정에 대해 알 수 있으실 거에요 !* 
