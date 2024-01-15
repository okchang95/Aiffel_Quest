# AIFFEL Campus Online 7th Code Peer Review Templete

- 코더 : 옥창우
- 리뷰어 : 이승제

|평가문항	|상세기준|
|---|---|
|1. 프로젝트 1의 회귀모델 예측정확도가 기준 이상 높게 나왔는가?|	MSE 손실함수값 3000 이하를 달성
|2. 프로젝트 2의 회귀모델 예측정확도가 기준 이상 높게 나왔는가?	|RMSE 값 150 이하를 달성
|3. 시각화 요구사항이 정확하게 이루어졌는가?|	각 프로젝트 진행 과정에서 요구하고 있는 데이터개수 시각화 및 예측결과 시각화를 모두 진행하였다.


🔑 **PRT(Peer Review Template)**

- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부

    ## 1. MSE 손실함수값 3000 이하를 달성
     
    ![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/0edbc923-60e5-44ab-9c45-d7bb0e15f4e2)


    ## 2. RMSE 값 150 이하를 달성

    ![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/1d4372ca-c8a5-4c98-af33-f27c8de596c8)


         
    ## 3. 각 프로젝트 진행 과정에서 요구하고 있는 데이터개수 시각화 및 예측결과 시각화를 모두 진행하였다.
    프로젝트 1.
    (10) test 데이터에 대한 성능 확인하기 - 예측결과 시각화 
   
    ![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/7d30eaf0-c6e9-4125-8842-0f981c2750e1)


    프로젝트 2.
    (3) year, month, day, hour, minute, second 데이터 개수 시각화하기
  
    ![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/b8831207-186d-4e86-8a0e-52d86e71d950)


    (7) x축은 temp 또는 humidity로, y축은 count로 예측 결과 시각화하기 x축에 X 데이터 중 temp 데이터를, y축에는 count 데이터를 넣어서 시각화하기 x축에 X 데이터 중 humidity 데이터를, y축에는 count 데이터를 넣어서 시각화하기

    ![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/71218611-122b-4043-9cf2-8cf3739a8a2f)


---


- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.

![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/49cdf4aa-c86f-47e7-b3af-6e7672a91224)

**-> 날짜를 변환하는 과정에서 int type으로 오는 부분을 주석으로 남겨놓아서 바로 이해할 수 있었다.**

![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/d1034d36-ac79-4f6c-8ea2-f4869d09bb8d)

**-> 주석으로 데이터의 column을 잘 정리해 놓았다.**


---

 
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인 또는
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.
     
![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/53f57a4d-e4ac-4c9f-a08b-e20676009d19)

**-> 해당 부분에서 train 데이터를 info를 사용해 확인하고 쓰지 않는 column을 drop하는 부분에서 좋았던 것 같다.**


![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/7babecab-bb38-4edd-92f6-d93475004078)

**-> 에러가 난 부분을 잘 표시해 놓아서 확인이 수월했다.**

---


- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 상세히 기록되어 있는지 확인
        - 딥러닝 모델의 경우,
        인풋이 들어가 최종적으로 아웃풋이 나오기까지의 전체 흐름을 도식화하여 
        모델 아키텍쳐에 대한 이해를 돕고 있는지 확인

![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/5291e18d-db4a-418f-a702-c0e82e1cb9bd)

**-> 회고를 통해 프로젝트 결과물에 대해서 느낀점이 상세히 기록이 되어있었다.**


---


- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 모듈화(함수화) 했는지
        - 잘 작성되었다고 생각되는 부분을 근거로 첨부합니다.

![image](https://github.com/happybin2013/aiffel_quest_okchang95/assets/85716670/57e6169f-4555-40cc-8c7f-7462f07a07bf)

**-> PEP8(indent & "test1, test2")을 준수하였고, 변수를 깔끔하게 선언하였다.**
