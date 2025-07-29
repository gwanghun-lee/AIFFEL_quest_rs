# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 이광훈
- 리뷰어 : 김재성


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**

<img width="345" height="435" alt="Image" src="https://github.com/user-attachments/assets/be69eaed-75d7-4fcb-b876-8df73e6d4f94" />

주어진 문제를 해결하는 완성된 코드를 제출하여, 이미지와 같은 결과물을 제출함.

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

<img width="600" height="234" alt="Image" src="https://github.com/user-attachments/assets/33a7ac65-76bd-4293-9592-e68ee608a2a4" />

문제 해결을 위해서 SAM(Segmentation Anything Model)을 사용하였고, 이를 호출하는 부분의 이미지가 핵심적이라고 판단됐다.

deep lab v3 모델로 해결되지 않은 경계선의 디테일이 떨어지는 문제를 잘 해결하였다.

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**

<img width="983" height="444" alt="Image" src="https://github.com/user-attachments/assets/7bd47694-0ae4-40ba-a3d3-9d39fc88711b" />

행글라이더 같은 어려운 이미지를 segmentation하는 추가 실험을 진행하였다.

사람과 행글라이더 사이의 빈 공간의 여백은 segmentation이 되지 않았고, 이를 해결하기 위한 고민이 잘 진행되었다고 느꼈다.

리뷰어에게도 고민하게 되고, 어떻게 하면 좋을 지 궁금해져서 인상깊은 실험이었다.

        
- [X]  **4. 회고를 잘 작성했나요?**
    
<img width="924" height="181" alt="Image" src="https://github.com/user-attachments/assets/ccbde4ed-acdd-43b9-bf7e-f1c7b4f7336a" />

회고가 잘 작성되어 있으며, 코드의 전체 흐름도와 겪었던 문제점 및 해결 방식이 잘 작성되어 있다.

특히 마우스 클릭 기준으로 Segmentation이 진행되는 SAM 모델을 사용하기 위해 클릭 대신 경계가 명확해지는 점을 찾는 코드를 구현한 점이 인상깊다.

- [X]  **5. 코드가 간결하고 효율적인가요?**

코드가 간결하고, 결과물 시각화도 잘 되어 있다.

여러가지 시행착오(이미지, 고양이, 행글라이더)를 2가지 모델로 모두 다 잘 정리되어 있다.


# 회고(참고 링크 및 코드 개선)
```
# 다른 모델을 찾아서 문제를 해결한 것이 인상 깊었습니다.
# 클릭이 가능하지 않은 환경에서 해결책을 찾은 것이 인상 깊었습니다.
# SAM 모델이 궁금해서 찾아보았는데, 참고할 수 있는 이미지를 아래 첨부했습니다.

<img width="1226" height="615" alt="Image" src="https://github.com/user-attachments/assets/9400339b-3d5b-4110-b657-7e71d1324d2b" />

```
