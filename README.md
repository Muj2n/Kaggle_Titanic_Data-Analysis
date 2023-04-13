# 타이타닉 데이터 분석 및 전처리 - 기초

* 상관분석을 통한 PairPlot 분석
  * Target value인 Survival과 연관된 것
    * Sex - Survival의 연관 : 남성 생존자보다 여성 생존자가 많으며, 남성 사망자가 생존자의 3배 이상이다.

    * Pclass - Survival의 연관 : 1등석에 앉은사람이 가장 많이 생존 한 것을 볼 수 있으며, 3등석의 사망자가 생존자의 3배 이상인 것을 확인 할 수 있다.

  * 그 밖의 Pairplot 분석 결과.
    * Fare - Pclass의 관계에서 3등석을 받은 사람들이 사망자가 많이 나온 것을 확인 할 수 있는데, 그 중에서 Fare의 값이 3등석과 1등석이 비슷한 것도 많기 때문에 금액으로 등급을 나눈 것이 맞는지도 판단 해봐야 할 것 같다.

    * Age - Pclass의 관계를 본다면 나이에 상관없이 1등석에 있던 사람들이 많이 생존한 것을 볼 수 있다.

* 피드백
  * 히스토그램 : 정규화 하려고 보는 과정 (단위의 범주 확인 : 0~1 -1 ~1) > 정규화 해보면 될 것 같음
  * encoding > 상관분석 순서
  * 상관관계 수치에 대한 0.4 ~ 0.5 정도 되야 연관성이 있다고 판단
  * 컬럼을 버리는 근거에 대해서 확실히 판단
