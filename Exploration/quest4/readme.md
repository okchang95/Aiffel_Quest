# AIFFEL Campus Online 7th Code Peer Review Templete

- 코더 : 옥창우
- 리뷰어 : 윤빛나

### 루브릭
평가문항 |	상세기준 |
|---|---|
|1. 다양한 방법으로 Text Classification 태스크를 성공적으로 구현하였다.	|3가지 이상의 모델이 성공적으로 시도됨|
|2. gensim을 활용하여 자체학습된 혹은 사전학습된 임베딩 레이어를 분석하였다.	|gensim의 유사단어 찾기를 활용하여 자체학습한 임베딩과 사전학습 임베딩을 비교 분석함|
|3. 한국어 Word2Vec을 활용하여 가시적인 성능향상을 달성했다.	|네이버 영화리뷰 데이터 감성분석 정확도를 85% 이상 달성함|

🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부

1. 3개 이상의 LSTM, RNN, CNN, 그리고 Transformer 모델들을 사용하여 성공적으로 학습을 구현시켰다.
   
<img width="785" alt="스크린샷 2023-11-24 12 47 41" src="https://github.com/okchang95/aiffel_quest/assets/100587126/149c34be-593e-414d-9d05-66be2ba601d3">
<img width="797" alt="스크린샷 2023-11-24 12 46 43" src="https://github.com/okchang95/aiffel_quest/assets/100587126/a23a5893-8eb0-4e4e-9d0f-5f2d37decdc8">
<img width="768" alt="스크린샷 2023-11-24 12 48 32" src="https://github.com/okchang95/aiffel_quest/assets/100587126/1c67aaff-a116-4b12-b8a7-3dabd8b5952d">


2. gensim의 유사단어 찾기를 활용하여 임베딩 레이어를 분석하였다.
   
<img width="354" alt="스크린샷 2023-11-24 12 56 11" src="https://github.com/okchang95/aiffel_quest/assets/100587126/0e44094e-285b-4375-90b1-c31515780269">

3. 두가지 이상의 모델에서 감정분석 정확도(accuracy)를 85% 이상 달성하였다.

   <img width="437" alt="스크린샷 2023-11-24 13 00 01" src="https://github.com/okchang95/aiffel_quest/assets/100587126/e306820e-9f06-4be8-b36a-5fbd032d0379">
<img width="448" alt="스크린샷 2023-11-24 13 00 15" src="https://github.com/okchang95/aiffel_quest/assets/100587126/03afeb05-6aa6-41b3-86d7-d1df68cf7367">



- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

적절한 주석을 사용으로 코드를 이해하기가 쉬웠으며 또한 모델 학습을 위한 코드를 사용할 때 가독성이 좋게 짜여져 있다.

<img width="759" alt="스크린샷 2023-11-24 13 02 29" src="https://github.com/okchang95/aiffel_quest/assets/100587126/a6d10444-b597-425c-8930-2e00f1d62772">
<img width="502" alt="스크린샷 2023-11-24 13 02 16" src="https://github.com/okchang95/aiffel_quest/assets/100587126/bd85531b-663a-4d7c-b2b5-2a38ab629baf">

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**

여러 학습을 통한 결과로 느낀들이나 여러 시도를 해보았다는 것을 자세하게 알 수 있게 작성했다.

<img width="873" alt="스크린샷 2023-11-24 13 26 06" src="https://github.com/okchang95/aiffel_quest/assets/100587126/d30b0cb2-6c7b-421b-a603-3af911c0d0d5">
<img width="642" alt="스크린샷 2023-11-24 13 26 26" src="https://github.com/okchang95/aiffel_quest/assets/100587126/c3395480-ac9c-46b3-96d3-3d421440a2e9">

        
- [x]  **4. 회고를 잘 작성했나요?**

<img width="895" alt="스크린샷 2023-11-24 13 27 37" src="https://github.com/okchang95/aiffel_quest/assets/100587126/5b896aea-a5f6-476d-9b9f-882fc806763a">

이번 프로젝트를 수행하면서 어떤것이 더 효율적이였는지 성능이 좋았는지에 대한 기록과 이로 인해 알게된 점이 자세하게 기술되어 있고 어떤 모델로 학습했을 때 제일 성능이 좋을 지 예상해보는 회고도 함께 적혀 있었다.

- [x]  **5. 코드가 간결하고 효율적인가요?**

    코드가 보기좋게 잘 작성되어 있으며 파라미터들을 따로 정리해놓고 어떠한 코드인지 가독성 좋게 함수명을 잘 설정해놓은 것 같다.

<img width="204" alt="스크린샷 2023-11-24 13 30 48" src="https://github.com/okchang95/aiffel_quest/assets/100587126/d4de895a-6ad2-4a2a-8d7b-40ed110dc2af">

항상 화이팅하세요!


