# 세션 2: BCI 기초와 데이터 시뮬레이션

## BCI 데이터 시뮬레이션 (session_02_bci_simulation.py)

1. 필요한 라이브러리 불러옴
   - random, numpy, matplotlib.pyplot, sklearn

2. BCI 데이터 생성하는 함수 만듦 (generate_bci_data)
   - 왼손, 오른손 움직임 상상할 때 뇌 신호 가정해서 만듦
   - 레이블 0(왼손), 1(오른손) 랜덤으로 선택
   - 각 채널마다 가우시안 분포로 신호 생성

3. 데이터 생성하고 출력해봄
   - 100개 샘플, 3개 채널로 만들어봄

4. 데이터 시각화함
   - matplotlib 써서 각 채널 데이터 그래프로 그림
   - 'bci_simulation_visualization.png'로 저장

5. 특징 추출함
   - 각 샘플의 채널 평균값을 특징으로 씀

6. 분류기 학습시킴
   - 데이터 훈련/테스트 세트로 나눔
   - 로지스틱 회귀 모델 써서 학습하고 정확도 계산

간단한 BCI 데이터 만들고 분석하는 과정 가상으로 해보기 완료
