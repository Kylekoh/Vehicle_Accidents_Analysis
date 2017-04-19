## Vehicle_Accidents_Analysis
패스트 캠퍼스 데이터 사이언스 스쿨 3기를 수강하면서 진행한 팀프로젝트입니다

> #### 프로젝트 주제  
  서울시 자동차 교통 사고량 예측

> #### 프로젝트 예측 모델 유형 
  Regression Model

> #### 데이터 설명
1. Target value : 서울시 일 평균 교통 사고수
1. Features : 교통사고와 관련되었을것이라 예상되는 변수들(기상조건, 유류 소비량, 운전자수, 인구 변동 등)


> #### 프로젝트 내용
1. Data preprocessing : 기본적인 회귀 분석, featuring selection using statsmodel
1. Regularization : L2(Lasso) 모델을 이용한 
1. 아웃라이어 테스트 (Leverage vs Normalized residuals squared)
1. StratifiedKFold 통한 모델 검증 


> #### 참고 링크
1. 교통사고수 - 도로교통공단(http://taas.koroad.or.kr/web/shp/sbm/initStatsAnals.do?menuId=WEB_KMP_STA)
2. 택시운전자수 - 전국택시운송사업조합연합회(http://www.taxi.or.kr/04/01_view.php?no=95)
3. 기온 - 기상청 기상정보(http://www.kma.go.kr/weather/main.jsp)
4. 유류량 - KOSIS(http://kosis.kr/statisticsList/statisticsList_01List.jsp?vwcd=MT_ZTITLE&parentId=I#SubCont)
5. 인구 - 서울 통계 DB 인구(http://stat.seoul.go.kr/jsp3/stat.db.jsp?cot=017&srl_dtl=10001)
6. 자동차 등록대수 - 국가지표체계(http://www.index.go.kr/potal/main/EachDtlPageDetail.do?idx_cd=1257)
