# XGB + LGBM 앙상블 모델로 검증

결측치 : 미처리(XGB, LGBM에서 자동으로 처리)

파라미터 : 
# XGBoost
xgb_model = XGBRegressor(
    n_estimators=1000,
    learning_rate=0.01,
    max_depth=8,
    colsample_bytree=0.8,
    random_state=42
)

# LightGBM
lgbm_model = LGBMRegressor(
    n_estimators=1000,
    learning_rate=0.01,
    max_depth=10,
    min_child_samples=10,
    min_split_gain=0.0,
    colsample_bytree=0.8,
    random_state=42
)

앙상블 모델 가중치: LGBM 1.0, XGB 0.2
