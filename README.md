# G_ML-AI_ScalpingMachineProject

제가 참여한 스캘핑 머신 프로젝트입니다.

스캘핑 머신 중 Confidence Estimation Module을 담당하여 작업했습니다.

# 1. Regression Ver.
Regression한 값과 attention, 그리고 정답 label을 이용하여 confidence score를 계산합니다
CEM(Confidence Estimation Module)은 이 confidence score를 예측하도록 학습됩니다
CEM의 값이 클수록, regression한 결과의 신뢰도가 낮습니다

# 2. Binary Classification Ver.
Binary하게 분류(상승하면 1, 하강하면 0)한 결과와 attention, 그리고 정답 label을 custom sigmoid 함수를 이용하여 confidence score를 계산합니다
이 때의 score는 0~1 의 범위를 가지며
1에 가까울수록 분류 결과의 신뢰도가 높습니다.
confidence score를 계산하는 방법은 pdf/이미지 파일을 참고해주세요
