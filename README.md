# AION2 Devanion Optimizer
아이온2 데바니온 최적화 프로그램입니다.

## Screenshot
<img width="451" height="474" alt="image1" src="https://github.com/user-attachments/assets/f74c7b70-77fe-4e96-9913-65df25eff498" />
<img width="451" height="474" alt="image2" src="https://github.com/user-attachments/assets/bf044411-c79a-4da9-ba27-08190132d182" />
<img width="451" height="474" alt="image3" src="https://github.com/user-attachments/assets/c4602311-f9db-4b25-880c-88f3f99a270f" />

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
