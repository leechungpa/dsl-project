# 뉴스 빅데이터를 통한 부동산 흐름 읽기

DataScienceLab project by 김승규, 김정환, 안지민, 이청파

![flow chart](./docs/flowchart.png)

> 부동산 관련 뉴스 빅데이터 분석 결과를 알기 쉽게 제공해 정보의 비대칭을 완화하여 부동산 실수요자의 문턱을 낮추는 모바일 플랫폼 구축.

## 목적

주식 시장과 부동산 시장은 과거부터 많은 금융 자금이 유입되고 있다. 이로 인해 긍정적인 측면도 있지만, 일부의 경우 자본의 증가 속도가 일반적인 물가상승보다 압도적으로 커지는 등 투기적 요소도 발생하고 있다. 금융감독원은 금융소비자를 보호하기 위해 은행, 보험회사, 증권회사 등 주식 시장과 관련된 다양한 행위자들에 대한 감독을 진행한다. 반면 부동산업의 경우 이를 검사 및 감독할 컨트롤 타워가 없다. 이로 인해 다른 금융소비자처럼 부동산 소비자를 보호해야 할 필요성이 지속해서 제기되고 있다.

이런 흐름에 따라 최근 정부는 가칭 '부동산감독원'을 신설하고자 추진 중이다. 부동산감독원을 통해 부동산 시장에 존재하는 투기세력으로부터 부동산 소비자를 보호하기 위함이다. 특히 이러한 투기세력이 미디어 등을 통하여 시장 분위기를 악의적으로 조장한다면, 소비자가 입는 피해가 막대해질 것이다. 정부의 흐름에 더불어, 소비자가 직접 데이터에 기반한 부동산 분석 정보에 접근한다면 현명한 부동산 매매를 하는 데에 도움이 될 것이다.

부동산은 대표적인 정보 비대칭 시장이라고 불린다. 부동산 시장의 건전성을 위한 정부의 노력과 더불어, 부동산 소비자에게 필요하고 적합한 부동산 뉴스를 골라 제공한다면, 소비자는 비대칭적인 부동산 정보를 다소 해소하고 올바른 거래행위를 하는 데 크게 도움이 될 것이다. 구체적인 예로, 각 뉴스 기사별로 해당 기사가 부동산 추세를 긍정적으로 또는 부정적으로 작성했는지를 보여주고, 당일 전체 기사의 세분된 긍·부정 비율을 보여준다면, 기사 하나의 이해와 더불어 종합적인 이해를 얻을 수 있을 것이다. 또한, 범주화된 긍·부정에 뉴스 기사를 종합적으로 고루 읽으면서 전반적인 시장 추세를 이해할 수 있을 것이다.

## 세부 내용
 
2013년도 9월부터 2020년 8월까지의 뉴스 빅데이터들의 키워드들과, 같은 기간 서울 내 3종류(아파트, 오피스텔, 연립다세대)의 부동산 실거래 정보를 같이 사용하여 부동산 추세예측지수 모델링이 주요 기술이다.

해당 모델을 이용하여 변화하는 언론 보도에 따라 서울 자치구, 법정동 그리고 유명 부동산브랜드까지 좀 더 세분화한 분석을 통하여 평균 가격에 대한 지수 등을 제공하여 부동산 시장 가격에 대한 추이를 제시한다. 또한 지수가 형성이 된 근거를 제시하고 소비자들에게 필요한 정보를 제공하기 위해서 현 시장에 대해서 긍정적이거나 부정적인 판단을 내린 기사들을 원하는 대로 모아볼 수 있도록 한다.

부동산 시장은 많은 사람의 지속적인 관심을 받은 시장이기에 미래의 부동산 가격에 관한 관심을 가지고 해당 정보를 얻으려는 사람이 고객이 될 것이다. 특히 부동산의 가격과 뉴스의 상관관계에 대한 인사이트를 얻고자 하는 사람들에게 효과적인 서비스를 제공할 수 있을 것이다.

정확한 정보에 대한 접근성을 높이기 위하여 많은 플랫폼이 만들어지고 한국감정원에서도 부동산 거래위험 자동분석시스템을 만드는 등의 노력을 기하고 있으나 여전히 부정확한 정보들이 많은 사람에게 노출되어 있다. 또한 ‘예측 시스템’이라는 것이 사업화를 하는 데 있어서 책임감을 부여하기 때문에 사업화가 거의 진행되지 않았다. 반면, 이 서비스는 국토교통부에서 제공한 정확한 정보를 사용하며 뉴스에 따른 정확한 ‘가격’예측이 아닌 고객들이 활용할만한 다양한 지수들을 제공한다. 이는 고객 본인들의 인사이트를 함양하는 데에 큰 도움을 줄 수 있을 것이다. 또한, 모델이 파악한 근거 그리고 기사들의 판단에 대한 정보를 제공함으로써 고객들에게 선택권을 부여하여 사업화를 근본적으로 가능하게 한다.
