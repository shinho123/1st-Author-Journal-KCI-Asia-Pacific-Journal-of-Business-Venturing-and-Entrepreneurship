# 논문 제목 : Covid-19에 따른 글로벌 창업 트렌드 분석: Crunchbase를 중심으로
# 저자 : 1저자

## Ⅰ. 서론

### 연구 배경
* Covid-19는 전세계에서 유례없는 팬데믹(Pandemic)으로 국내 외 산업 및 생활 전반에 큰 변화를 가져옴
* 많은 기업에서 오프라인에서 온라인 중심으로 고객 채널을 확장하였을 뿐 아니라 비대면 비즈니스가 크게 성장하는 등 다양한 산업 분야에 Covid-19로 인한 혁신이 일어나고 있음
* 이렇듯 Covid-19의 영향이 사회 전반에 크게 작용하는 상황에서 많은 기업이 비즈니스 방식 및 내용을 크게 변화시켜 왔으며, 새로운 비즈니스 접근법에 대한 지속적인 고민이 요구되고 있음

### 연구 동기
* 특정 산업 분야에 대한 Covid-19의 영향을 분석하는 동향 분석 연구는 다수 수행됐으나, 기존 연구들은 거시적 관점에서 산업의 신규 유망 분야, 쇠퇴 분야 등을 파악하고 새로운 비즈니스의 성장을 추적하기에는 어려움이 존재함
* 따라서 산업 전체를 포괄할 수 있도록 거시적 측면에서의 체계적 분석이 요구됨

## Ⅱ. 프레임워크

![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/6c1191bf-20b8-432b-b2d6-5e35b2c6636f)

## Ⅲ. 연구 방법

### 1. 데이터 수집

![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/b82ad52c-f468-4282-ad66-08e06bedc4a9)

### 2. Descriptive analysis
* Covid-19 전후로 창립연도별 기업 수 변화 분석 및 산업별 기업 수의 변화를 분석하여 Covid-19가 산업 전반에 미친 영향을 분석
  
### 3. Network analysis
* Gephi를 활용하여 키워드를 활용한 키워드 네트워크 분석을 수행

### 4. Topic modeling
* LDA 토픽 모델링 기법을 통해 산업들이 소유한 기술 토픽을 추출하고 Covid-19 기간 동안 어떠한 기술의 변화가 있는지, 유망·쇠퇴한 기술의 양상이 어떠한지 분석
  
### 5. Doc2vec & Clustering
* 기업의 설명을 담고 있는 요약 설명 속성에 임베딩을 수행하고 K-Means 알고리즘으로 군집화를 통해 Covid-19 이전과 이후 기술 키워드의 변화를 분석

## Ⅳ. 연구 결과

### Descriptive analysis

#### 창립연도별 기업 수 변화 분석

![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/26decd08-2f30-462f-bc9b-fe8af2b1395c)

* Covid-19 이전 시기인 2019년의 기업 감소율은 2018년에 설립된 스타트업 수와 비교할 때 전년 대비 –29.9% 감소율을 보임
* Covid-19가 본격적으로 유행한 시점인 2020년부터 –31.4%로 2019년보다 -1.5% 더 감소한 것을 확인할 수 있음
* Covid-19가 장기화된 시점인 2021년에는 –58.3%로 전년대비 -26.9% 감소하여 가장 큰 감소세를 보임
  
#### 산업별 기업 수 변화 분석

##### Covid-19 이전 상위 10개 산업의 기업 수 비율 변화

![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/90af1f24-a82b-4c68-bcc7-88c01e8c1ad8)

##### Covid-19 이후 상위 10개 산업의 기업 수 비율 변화

![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/feac1a5e-a0b2-4ae5-805c-dd4a66abfacd)

* 1순위~5순위 산업을 살펴보면 ‘Health Care’, ‘Software’, ‘Commerce and Shopping’, ‘Financial Services’, ‘Biotechnology’가 대부분을 차지하고 있음
* 의료, 소프트웨어, 온라인 쇼핑, 금융 서비스, 생명공학의 경우 고정적으로 창업이 활발한 산업임을 확인할 수 있음
* Covid-19 이후 ‘Software’, ‘Commerce and Shopping’, ‘Financial Services’, ‘Education, Software’ 순서로 비대면 기술 및 개개인의 금융과 관련된 산업이 상위 산업을 차지하고 있음
* Covid-19 이후 소프트웨어 기반의 교육산업(Education, Software)이 새로 출현하였음
* Covid-19의 장기화로 교육도 점차 비대면으로 진행하는 상황이 많이 발생함에 따라 자연스럽게 온라인에 기반한 교육 산업에도 그 영향을 끼친 것으로 보임

### Network analysis

#### Industry groups network analysis

##### Covid-19 이전 산업군 네트워크 시각화
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/a4e939db-fd95-4e3e-a749-ea730747eaff)

##### Covid-19 이후 산업군 네트워크 시각화
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/51b037c0-82c8-489d-b73a-5b7e20affa2b)

* Covid-19 이후 모바일, 문화와 관련된 산업들은 IT, 소프트웨어 그룹에 포함되면서 온라인이나 비대면의 성격을 띠는 형태로 변화하였고, 경제침체가 진행됨에 따라 금융과 관련한 산업들의 비중은 자연스럽게 증가한 것을 확인할 수 있음

#### Industries network analysis

##### Covid-19 이전 산업 네트워크 시각화
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/bd626fe3-fa0b-4936-b521-bb9b84ddcfe2)

##### Covid-19 이후 산업 네트워크 시각화
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/6af3db76-72fd-4918-9049-13e5b36785bc)

* IT 산업에 소속되어 있던 머신러닝, 인공지능, 하드웨어, 컴퓨터비전, 로봇, IoT 산업이 독립적인 새 그룹을 이루어 등장하였음
* AI/ML 기반 첨단기술 클러스터의 비율은 11.51%로 적지 않은 수치를 기록하였고, 농업, 산업 자동화 같은 다른 산업과의 융합 가능성을 고려할 때, Covid-19 이후에도 다른 산업과 융합하여 AI가 적용된 새로운 형태의 신산업 등장을 기대할 수 있음
* 교육산업에도 많은 변화가 일어났는데 Covid-19 이전에는 교육의 비율이 9.35%로 군집중에서는 가장 적은 비중을 차지하고 있었는데 Covid-19 이후 9.35%→15.95%로 증가한 것을 확인할 수 있음
* 7개의 군집 중에서도 3순위를 차지할 만큼 중요도가 높아졌다고 볼 수 있으며, 이는 곧 대면으로 진행되어야 할 교육산업에 많은 변화가 일어나고 있음을 짐작할 수 있음
* 특히 가상현실, 증강현실 산업과 융합되는 양상을 보여 기존 대면 교육의 시·공간 제약에 대한 한계점을 극복하기 위한 기업들의 혁신적인 시도가 지속되고 있음을 알 수 있음

### Topic modeling
#### Covid-19 이전 토픽별 상위 10개 키워드
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/832eed5f-5465-4023-a2dc-277551c77b0e)

#### Covid-19 이후 토픽별 상위 10개 키워드
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/1d8e3a1a-7525-4c92-93d3-bf26b6f546b8)

* _미디어 산업_
  + 미디어 산업의 경우 Covid-19 이후의 토픽 4에서 nft와 게임 키워드와 묶여 주제로 출현이 되었고, nft의 경우 Covid-19 이후 토픽 1의 가상화폐와 독립적으로 구분되어 토픽 4에 출현이 되었는데 이는 Covid-19 이후 유튜브와 같은 1인 미디어 플랫폼이 활성화되면서 미디어 기업들이 자신들의 콘텐츠 IP로 캐릭터 nft를 만들어내면서 미디어, nft, 게임과 같은 키워드와 토픽 4의 주로 나타나고 있음을 확인할 수 있음
    
* _의료 산업_
  + Covid-19 이전의 토픽 7과 이후 토픽6에 각각 꾸준하게 출현 되고 있다. 다만 Covid-19 이전의 의료 산업 분야의 경우 주로 특정 질병·질환에 대한 치료 및 치료제 개발 자체를 목적으로 하는 스타트 업들이 대부분 이었다면, Covid-19 이후 치료 자체의 목적보다는 의료·원격 서비스와 같이 환자와 비대면 서비스를 제공하는 스타트업 들이 대거 등장하였음을 시사하고 있음
    
* _배달 산업_
  + Covid-19 이후에는 배달 대행이라는 산업이 활발해지기 시작했는데 Covid-19 이전에도 음식을 의미하는 food 키워드는 online 키워드와 결합하면서 Covid-19 이전 토픽 4에도 출현되었음
  + 식료품을 온라인으로 주문하는 서비스를 제공하는 스타트 업들이 존재하였으나, Covid-19 장기화가 진행됨에 따라 식료품뿐만 아니라 외식이 줄어들면서 집에서 배달할 수 있는 배달 대행 관련 서비스 산업이 활발해지면서 배달 대행 산업에 가속화가 붙기 시작하였음

* _교육 산업_
  + Covid-19 이전 토픽 6과 Covid-19 이후 토픽 7에서 각각 교육산업이 등장하였으나 Covid-19 이후에는 주로 온라인 금융, 온라인 앱과 관련한 키워드와 묶여 토픽 7에 출현하고 있음
  + 이를 Covid-19 이전 시기와 비교할 때, 주로 온라인, 모바일, 앱과 같은 키워드와 묶여 온라인 교육 및 앱을 이용한 교육 방법은 동일하나 교육을 받는 대상과 범위가 확장되면서 금융 및 투자와 관련한 금융 교육 서비스를 제공하는 스타트업들이 등장하기 시작한 것을 확인할 수 있음

#### Doc2vec & Clustering

##### Covid-19 이전 군집별 대표되는 상위 10개 키워드
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/727e3361-9e22-483a-afa5-4c3f66ead014)

##### Covid-19 이후 군집별 대표되는 상위 10개 키워드
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/e6f8099a-a859-402b-bd10-0f9562f11d14)

* _식품 산업_
  + Covid-19 이후 cluster3의 배달 대행, 패션 키워드와 함께 묶여 주제로 출현하였고, cluster 5에서는 생명공학, 디지털마케팅, 웹 개발 키워드와 묶여 주제로 출현 되었음
  + 식품 키워드는 Covid-19 이후 2개의 cluster에서 서로 다른 키워드들과 묶여 있는데 cluster 3 주제인 식품, 배달 대행, 패션, 농업에서의 식품 키워드는 주로 사람들의 여가·편의 서비스와 관련된 주제와 묶여 온라인으로식품·음식·의료 등을 주문·배달할 수 있는 서비스를 제공하는 스타트 업들이 다수 등장한다는 점, 그리고 cluster 5의 주제인 식품, 생명공학, 디지털마케팅, 웹 개발에서는 식품의 키워드가 식품 자체를 제조하는 스타트 업들이 등장한다는 점에서 서로 다른 차이를 보임

* _의료 산업_
  + 의료 산업에서는 Covid-19 이전의 경우 특정 질환·질병에 대해 1차원적 치료를 목적으로 하는 스타트 업들이 대부분 설립되었으나, Covid-19 이후 DTx(Digital Therapeutics)와 같이 치료를 보조하는 역할을 수행하는 웨어러블 디바이스 및 의료진·환자들에게 의료서비스(의료 스케줄)를 제공하는 스타트업들이 등장함을 확인하였음

* _엔터테인먼트 산업_
  + 엔터테인먼트로 정의되는 음악(music), 게임(game), 비디오(video)와 같은 키워드의 경우 Covid-19 이전에는 주로 여가·편의 서비스 키워드와 묶여 cluster 2와 cluster 7에 등장하였음
  + 음악, 게임, 비디오 키워드는 Covid-19 이전에는 단순 여가·편의를 위한 산업 일부였으나 디지털 활동이 활발해지는 Covid-19 이후 시기부터 음악, 게임, 비디오 등을 포괄하는 엔터테인먼트 산업이 소셜네트워크 키워드와 함께 묶이면서 특히 VR(Virtual Reality), AR(Augmented Reality), Metaverse와 같이 시·공간 제약이 없는 온라인 플랫폼 산업의 활성화를 의미하고 있음
    
### LDA, Doc2vec & Clustering 비교 분석
![image](https://github.com/shinho123/1st-Author-Journal-KCI-Asia-Pacific-Journal-of-Business-Venturing-and-Entrepreneurship/assets/105840783/5233c65a-f277-46f5-a8cb-f25013aaff5f)

* 공통점
  + LDA와 Doc2vec에서 의료, 배달, 교육산업에서 공통점을 보임
  + 사람을 대면해야 하는 서비스 산업들이 Covid-19 이후 비대면 서비스로 전환되는 산업 분야에서 공통점을 보임
  + 의료 산업도 비슷한 성격을 가지는데 Covid-19 이전 환자를 대면하는 1차원적 치료 서비스를 제공하는 형태에서 원격 서비스와 같은 비대면 서비스의 활성화가 진행되어 환자가 병원을 방문하지 않고도 원격으로 치료가 가능한 산업의 형태로 변화하였음
  + 기존 산업이 더 크게 확장되는 형태로 교육산업의 경우 원래 단순히 학생들의 교육자체에 초점을 맞춘 산업이 주를 이루었다면, Covid-19 이후 금융 산업 등과 연계하면서 교육의 범위와 받는 대상에 대한 다양화가 진행되는 관점에서 공통점을 보임
 
* 차이점
  + 특정 산업 키워드가 속한 그룹 간의 차이가 발생하고 있음
  + 엔터테인먼트 산업의 경우 토픽 모델링에서는 콘텐츠(미디어), nft 키워드와 묶이면서 콘텐츠(미디어)와 엔터테인먼트를 통한 nft 산업의 확장을 의미하고 있고, Doc2vec 방법에서는 엔터테인먼트 산업이 소셜네트워크 산업
과 묶이면서 디지털 산업의 확장을 의미한다는 점에서 다소 차이를 보임


## Ⅴ. 결론

### 연구 동기

* 본 연구는 Covid-19 이후 산업을 거시적 관점에서 동향 변화를 살펴보고 체계적으로 분석하기 위해 Crunchbase를 통해 산업 수준의 동향 분석을 수행함
* 먼저 네트워크 분석을 통해서 전체적인 산업 변화의 흐름을 관찰하였고, 토픽 모델링과 Doc2vec 방법을 통해 해당 산업들이 보유한 기술 콘텐츠를 분석하는 과정을 거침

### 연구 결과

* Covid-19 이후 소프트웨어, 전자상거래, 금융 서비스, 교육 서비스가 크게 성장하였으며, 특히 소프트웨어 기반 교육산업이 새로 출현하여 크게 성장하였음
* 에너지, IT 산업에서도 많은 변화가 나타났으며, 에너지 산업은 Covid-19 이후 독립적인 그룹을 형성하였고 IT 산업의 경우 IT 산업 내에 존재하던 AI 관련 산업이 독립적인 그룹을 형성함
* 의료, 배달, 교육 산업에서는 비대면 서비스 전환으로 인해 기존 산업이 확장되는 양상이 뚜렷히 관측되었으며 엔터테인먼트 산업 역시 콘텐츠 측면에서 변화를 보이며 새로운 혁신을 주도해가는 것으로 보임
* 이를 정리하면 Covid-19는 기존 산업의 확장·다양화(식품, 교육), 디지털화(엔터테인먼트, 미디어), 비대면 서비스화(의료, 배달 대행) 등 여러 가지 산업의 형태를 변화시켜 왔고 이를 통해 기존 산업의 장벽을 뛰어넘는 새로운 기회를 가져다준 것으로 파악되었음

### 결론
* Covid-19 이전과 이후 산업의 동향 변화는 단순 시간 변화에 따른 산업 동향 분석과는 많은 차이를 보임
* 특히 비대면과 관련한 기술·산업에서 뚜렷한 성장을 나타내고 있으며 그 외에 의료 및 개인의 생활과 관련된 산업이 활발한 창업이 이루어지고 있는 것을 확인할 수 있음
* 특히 비대면, 온라인 기술들이 이전보다 더 전문성을 갖추고 있으며 단일 기술의 발전이 아닌 융합 기술에 초점을 두고 많은 산업이 성장하고 있는 것으로 확인되었음
