# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 최범용
- 리뷰어 : 최정민


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - Diabetes(MSE<3000)
<img width="1200" height="879" alt="image" src="https://github.com/user-attachments/assets/4c8f0941-386d-4255-b9c8-2ed035e6ff77" />

        - Bike-sharing-demand(RMSE<150)
<img width="701" height="421" alt="image" src="https://github.com/user-attachments/assets/e57cec2c-c4ab-49b4-a74b-150021d503fc" />


    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - PCA 기법을 추가할 때 주성분 몇 개로 축소할 지, learning rate 가 기존에서 어떻게 변경되었는지 주석으로 설명함
<img width="1305" height="1076" alt="image" src="https://github.com/user-attachments/assets/dab50624-7eab-4434-a3d7-c96b7b4a1922" />

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 시각화에서 새로운 방법을 시도
<img width="1880" height="886" alt="image" src="https://github.com/user-attachments/assets/b9b55825-52ee-40ea-baea-6ecd7a581adf" />

        
- []  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 출 퇴근 시간 데이터 전처리 함수화
<img width="1403" height="957" alt="image" src="https://github.com/user-attachments/assets/a188a164-691b-4b5f-a14d-a1bd4c37a564" />



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- Diabetes 데이터셋에서는 PCA를 활용하여 차원을 축소한 후 학습을 진행함으로써, MSE를 효과적으로 낮춘 점이 인상 깊었습니다.

- Bike Sharing Demand 데이터셋에서는 시간 데이터를 workingday와 holiday로 나누어 처리함으로써, RMSE를 낮추는 데 기여한 점이 인상적이었습니다.

- 또한, windspeed 변수의 결측치를 적절히 보완한 후 다시 학습한다면, RMSE가 더 낮아질 수 있을 것으로 기대됩니다.
