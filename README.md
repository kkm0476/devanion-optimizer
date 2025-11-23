# AION2 Devanion Optimizer
아이온2 데바니온 최적화 프로그램입니다.

## Screenshot
<img width="451" height="474" alt="스크린샷 2025-11-23 111820" src="https://github.com/user-attachments/assets/0ec7485f-16fb-4f15-a504-2a4b507f636b" />
<img width="451" height="474" alt="스크린샷 2025-11-23 111723" src="https://github.com/user-attachments/assets/26c33e45-916f-4ec9-905a-7f5609c85191" />
<img width="451" height="474" alt="스크린샷 2025-11-23 111704" src="https://github.com/user-attachments/assets/d7d333f8-9b7e-48e0-b271-93ac7e921d68" />
<img width="451" height="474" alt="스크린샷 2025-11-23 111645" src="https://github.com/user-attachments/assets/69260b48-c488-41da-955c-57e4bc915e6a" />

## Algorithm
이 문제는 가중치가 존재하는 Steiner tree 문제에 해당합니다.

NP-hard에 해당하는 문제이므로, greedy 알고리즘을 사용하여 근사해를 계산합니다.

탐색 과정에서는 두 가지 전략을 시도합니다.
1. 첫 번째 방문 노드 지정
각 목표 노드를 첫 번째 방문 노드로 강제하여 그리디 알고리즘을 시행합니다.
2. 랜덤 순서 탐색
목표 노드를 무작위로 셔플링 한 뒤 탐색합니다.

이후 사이클이나 불필요한 노드를 탐지하여 제거합니다.

추후 다른 알고리즘 적용 예정입니다.
