# NLP_2조


[NLP] 청와대 청원 : 청원의 주제가 무엇일까?
Python, Deeplearning Classification, NLP, 청와대, 청원


청와대 청원 데이터는 4.5만개 문자 데이터셋입니다.

딥러닝 모델로 문자를 분석하여 청원 클래스를 분류해보세요!


# Data

① train.csv(53MB) : 청원의 카테고리와 내용	→  4.5만

② test.csv(7MB) : 청원 내용			      →  0.5만

③ sample_submission.csv(1MB) : submission 파일의 예시

④ 라벨

	0 : 인권/성평등
	
	1 : 문화/예술/체육/언론
	
	2 : 육아/교육


Baseline Code로만 학습시켜서 제출했더니 65등(90명 중)  0.8396

![image](https://user-images.githubusercontent.com/16568200/146928086-2a79b4d8-df91-4a18-a25d-ac5ef8dbf7fa.png)
