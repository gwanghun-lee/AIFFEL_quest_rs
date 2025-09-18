# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 이광훈
- 리뷰어 : 최정민


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="1209" height="1125" alt="image" src="https://github.com/user-attachments/assets/aa21059f-8fd6-46b3-b5e7-46acb3fca94e" />
        <img width="1671" height="1118" alt="image" src="https://github.com/user-attachments/assets/ce3da006-8ec7-4fec-b08e-410444c4d7e6" />
        <img width="1684" height="515" alt="image" src="https://github.com/user-attachments/assets/9bcc2869-3f1c-46d3-bbf7-614044b378f6" />



    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 더 작은 ViT 모델 사용을 위해 heatmap size 를 변경한 부분에 대한 주석 잘 작성함
        - <img width="1350" height="918" alt="image" src="https://github.com/user-attachments/assets/5553ea76-f109-497f-99aa-c3b48d94bbe4" />

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - GT와 외부 모델, 외부 모델 파인 튜닝 한 것에 대한 정성적 평가를 시도함
        - <img width="1786" height="805" alt="image" src="https://github.com/user-attachments/assets/bac19393-5644-43f6-9690-a119c64a3aff" />

        
- []  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 파인튜닝 실행 부분을 함수화 함
        - <img width="1413" height="988" alt="image" src="https://github.com/user-attachments/assets/24218c3a-c10a-4ba5-aeb6-80097855e0e7" />



# 회고(참고 링크 및 코드 개선)
```
외부 모델을 가져와서 파인 튜닝을 한 것과 하지 않은 것에 대한 성능 비교와 여러 기법으로 시각화가 잘 되었다.
GT에서 왼쪽 상단에 점을 찍는 경우가 있다는 사실을 시각화를 통해 발견했고 이 또한 왼쪽 위 꼭짓점이 아닌 그 근처에 찍는 경우도 있다는 점을 알게되었다.
제공된 데이터에 대해서도 전처리를 수행할 방법을 고민하게 되었다.
```
