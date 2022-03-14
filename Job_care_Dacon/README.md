최종 성적
- 전체 참가 팀 : 728 팀
- Leaderboard: 22 등
- 2차 평가: 8 등

발표 영상
:https://youtu.be/v02lxHB0BEo

비고
- 독립변수에 범주형 변수만 존재할 때, 분류 모형은 catboost의 성능이 뛰어남
- optuna를 통해 하이퍼 파라미터 최적화 가능, GridSearch보다 시간이 덜 걸리나 최적값이 아닌 그에 근사한 수치를 제공
- 교차 검증을 통해 다수의 모델을 생성한 뒤 이를 앙상블로 엮을 시 유의미한 성능 향상을 기대할 수 있음
- binary classification 시 predictproba를 통해 기존 threshold=0.5 가 아닌 다른 최적 threshold를 적용 시 성능 향상 가능 
