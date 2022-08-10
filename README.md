# 산탄데르 고객 만족도 예측

1. 산탄데르 고객 데이터
    * 371개의 특성
    * 76020개의 데이터 
2. 데이터 전처리(StandardScaler)
3. 변수 중요도 판별(DecisionTreeClassifier)
3. 딥러닝 모델 제작(EarlyStopping 적용)
4. 모델 최적화(optimizer 변경, L1-L2규제, dropout layer)
5. 최종 모델
    * 딥러닝 : ROC Curve 0.76
    *  DesicionTree : ROC Curve 0.82
