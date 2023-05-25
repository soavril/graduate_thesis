# 포탈 뉴스 댓글 클린봇의 통계적 학습 / 저자: 최동혁

본 논문에서는 Distil-KoBERT 모델을 이용해 악플을 스크리닝하는 이진 분류 모델을 만들고자 한다. 
Ditil-KoBERT 을 이용한 방식은 현재 선행연구로 이루어져 있는 방식과는 다른 학습 모델 형태이다. 
이는 비교하였을 때 몇가지 장점을 가지기에 이를 연구하고 발전시키는 과정을 담고 있다. 전체적인 과정은 자연어처리의 지도학습을 바탕으로 진행된다. 
세부적으로는 BERT 모델에서 데이터셋의 특수성과 한국어의 고유 특성을 반영하여 학습을 진행한다. 
이 과정에서 불균형 데이터 처리에 큰 노력을 기울여 해결하는 여러가지 방법을 담고 있다. 
기존의 단순 크롤링 된 데이터의 분석보다 악플이라는 주제성이 뚜렷한 텍스트 데이터에 대한 유의한 분석으로 시사점과 향후 연구 주제를 제시한다.
