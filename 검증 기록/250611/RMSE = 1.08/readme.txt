XGB 단일모델로 검증

결측치 : 제거

파라미터 : 
xgb_model = XGBRegressor(
    n_estimators=1000,
    learning_rate=0.01,
    max_depth=8,
    colsample_bytree=0.8,
    random_state=42
)
