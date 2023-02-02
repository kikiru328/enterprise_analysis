# Enterprise_analysis
![image](https://user-images.githubusercontent.com/60537388/143975906-d065dc4a-770c-44e8-b162-af7f12b35526.png)
[발표자료](https://github.com/kikiru328/enterprise_analysis/files/7786007/5._.pdf)  
[발표영상](https://youtu.be/GAzX1vdpVyQ)

 L사의 데이터를 활용하여 고객의 구매 패턴을 파악한 후, 구매 감소 고객 예측 모델을 구축하여 특정 패턴을 보이는 고객에게 맞는 마케팅을 제언합니다.
 사용한 모듈을 다음과 같습니다.
 
	Language : python
	DB : oracle sql developer
	Environment : google Colab
	
## 과정
 제공 받은 데이터를 분석하여 pain point를 찾고, 이에 대한 해결이 가능한지 통계 및 시각적으로 분석하였습니다.
 또한 기존 고객에 대해서 정의를 내리고, 분석에 필요한 데이터를 추출해내어 분석을 진행했습니다.
 
### 사용 변수
![image](https://user-images.githubusercontent.com/60537388/216247619-3c251a5b-e76a-48e6-9f74-06fb7c67b9f2.png)

### 모델링 결과
위 변수를 이용하여 여러 모델을 사용, 최적화된  모델 및 결과는 다음과 같습니다
 
	Machine Learning Model : Logistic Regression (acc : 0.7129 ) , Random Forest (acc : 0.7255 )	
 
### 군집분석
![image](https://user-images.githubusercontent.com/60537388/216247891-8172852a-2545-4026-9069-b763b954eda4.png)
Feature importance를 통해 중요변수 22개를 선정하였고, `elbow method = 4 (최적화)`를 기준으로 군집을 분석하였습니다.

### 마케팅 제언 부분
![image](https://user-images.githubusercontent.com/60537388/216248246-1185b2d3-d8d8-4c65-b3bf-3c98a4f13400.png)
군집분석한 내용을 토대로 Decision Tree에 따라 특성을 파악했습니다.  
이후 중요도에 맞게 마케팅을 제언했습니다.

## 어려웠던 점
 데이터내의 기준이 명확하지 않아, 기준을 세우고, 그에 맞는 데이터의 기준을 세우는데에 시간이 많이 소비되었습니다.
 또한 추가적인 파생변수를 만들어내기 위해서 여러가지의 마케팅 정보를 습득하는데에 있어서 어려움을 겪었습니다.
 
### 팀원 Github
 - 팀장 : 채승혜 https://github.com/SeunghyeChae
 - 팀원 : 권준기 https://github.com/pkwon35
 - 팀원 : 김광훈 https://github.com/kikiru328
 - 팀원 : 진유훈 https://github.com/JINYUHOON
