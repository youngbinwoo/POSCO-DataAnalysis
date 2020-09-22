# POSCO-DataAnalysis  
- 고객특성을 고려한 판매전략 수립 및 배송서비스 차별화를 통한 영업이익 증대

# 과제 수행 배경
## 1. 산업의 성장성
코로나 19로 인한 정부의 사회적 거리두기 정책이 계속 되며 배달 서비스 이용률 증가와 더불어 포장 용기 시장의 규모가 급속히 증가하고 있다. 따라서 시장점유율을 확대하기 위한 새로운 성장 전략이 필요하다. 

## 2. 위험요인  
사장의 낮은 진입 장벽으로 인해 업체 수가 증가하고, 경쟁이 과열되고 있다. 이에 따라 매출 증가율이 지속적으로 하락하고 있는 경영위기를 극복할 방안이 필요하다. 

## 3. 판매 전략
코로나 19의 확산으로 간편식 선호도가 증가하고 있고, 비대면 소비가 활발해지고 있다. 이를 대비하는 마케팅 전략이 필요하다. 더불어 정부의 환경 규제가 심화되며 친환경제품의 판매를 확대해야한다. 최근에 생산 및 유통시스템을 통합하는 비즈니스 구조를 구축하여 거래비용을 줄이는 추세이다. 이러한 추세에 따라 통합형 비즈니스 벤츠마킹을 통해 물류 프로세스를 개선하고, 배송 지연의 문제를 해결한다. 

## 4. 과제 수행 목표
고객의 특성을 반영한 물품 추천과 물류 서비스 개선을 통해 영업 이익률을 향상한다. 

# Getting Started

### Prerequisites
- pandas
- numpy
- matplotlib
- keras

### Prepare Dataset
 - Log Order (주문 데이터)    
 - Master product (제품 데이터)    
 - Master Member (소비자 데이터)  


### 1. Data refinement    [CODE](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Data%20refinement)  
: 데이터 신뢰성 확인 결과, 총 578개의 이상치가 발생되어 중요한 변수에 대한 정제작업 실시

### 2. Exploratory Data Analysis    [CODE](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Exploratory%20Data%20Analysis)  
#### 2-1) 회원 수의 많은 부분을 차지하는 나이대는 30대, 40대 라는 사실 도출, 이 고객들이 유입하는 경로를 고려한 마케팅 전략 필요    
#### 2-2) 인기상품 가격 인상 후 우수고객 유지율은 64%이며 일반고객 유지율은 41%, 일반고객을 장려하고 우수 고객을 유지할 수 있는 전략 필요    
#### 2-3) 구매 고객 중 회원으로 가입된 고객이 창출한 영업이익이 전체의 92% 차지. 따라서 회원으로 유입시킬 수 있는 전략 필요  
#### 2-4) 포장 용기 배송 지연이 자주 발생하고 길게 나타남, 따라서 배송 기간의 단축 필요  
#### 2-5) 당사 자체 제작 상품의 비율이 91% 로 높고, 영업이익율도 높게 나타남, 따라서 자체 제작 상품의 판매 비중을 높일 수 있는 판매 전략 도출  
#### 2-6) 당상의 친환경 제품 판매량이 저조, 정부의 일회용품 규제에 대비하기 위해 친환경 제품에 대한 투자 시급


### 3. Modeling    [CODE](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Modeling)    

#### - 3-1) Decision Tree    [CODE](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Modeling/Decision%20Tree)  
: 신규 고객의 회원 가입 시 우수고객 가능성을 예측하기 위한 모델을 만들어 잠재 우수 고객을 관리하는 모니터링 시스템 개발
#### - 3-2) Market Basket Analsis    [CODE](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Modeling/Market%20Basket%20Analsis)     
: 장바구니 분석(연관분석)을 통해 구매 증진을 위한 추천 서비스 제공
#### - 3-3) Time Series Analysis    [CODE](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Modeling/Time%20Series%20Analysis)    
: 판매량에 대해 시계열 분석으로 예측하고, 이에 따른 효율적인 재고관리를 수행


### 4. Final [Click](https://github.com/youngbinwoo/POSCO-DataAnalysis/tree/master/Final) 
- report  
- program Demonstration Video

