#  📊 시각화 과제
* [Data_Visualization](https://github.com/jsw6872/DataScience-ML/new/main/teamlabxinflearn/week_4/assignment) 스스로 가설을 정해서 visualization을 통한 검증
* 진행일자 : 2022-07-23 ~ 2022-07-24

---
### 데이터 출처
* DACON - (🛍쇼핑몰 지점별 매출액)[https://dacon.io/competitions/official/235942/overview/description]
* 쇼핑몰 매장별 프로모션 정보, 주변 날씨, 실업률, 연료 가격 등의 정보
### 분석 전 예상
- **가설 1** : 주변 평균 기온이 적당한 주는(섭씨 10~ 26도) 그렇지 않을 때보다 같은 쇼핑몰에서의 주간 매출액이 높았을 것이다 (매출액 상위 10개 지점)
(구간 설정이 아닌 평균치에서 멀어질수록 가중치 설정)
- **가설 2** : 프로모션 수치가 높을 수록 주간 매출액은 높을 것이다 - (비식별화된 프로모션 정보이므로 시각화를 통해 매출과의 연관성 분석)
- **가설 3** : 해당 쇼핑몰의 주변 연료 가격과 주간 매출액과의 연관성은 낮을 것이다 <-> 연료가격이 높아지는 것은 물가가 증가하는 것이므로 전체로 봤을 때 연료 가격이 증가하면 매출액이 적을 것으로 보임(구간을 설정해 rolling을 통해 물가수치와 비교해보면 좋을 듯)
- **가설 4** : 쇼핑몰 지점간 매출액은 해당 지역과 상관관계가 있을 것이다