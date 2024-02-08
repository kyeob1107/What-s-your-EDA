# What-s-your-EDA
세번째 팀의 심화 프로젝트이다

2024-02-07
ver 설명드리기 직전 버전
X,y 초기화기능 함수로 구현하여 추가 reset_X_y(data:pd.DataFrame = train_df, y_col='대출등급')
이상치 제거 함수로 구현

결측치 처리 함수 부분 아직 작업중

ver 설명드리고 직후 b_ksy1      
Train data Train과 Test로 데이터 분리 추가      
(추가로 y_train 인코딩해준 것 확인하는 부분 추가)

ver 설명드리고 직후 b_ksy2
0인경우 에대해 범주형으로 추가해준것 비교
    + 해당하는 row 데이터 조회할 수있게 아래 코드로 구현해뒀음 
~train과 test 데이터 분리후 reset_index기능 추가 ~ -> 꼭 사용해야할까 생각이 되어 일반 주석처리
df에서 ID부분 제외시키던 것 다시 주석처리해서 포함시킴
인코딩하는 부분 일단 전부 get_dummies로 인코딩하게 주석해제시켜놓음