# DATA Scientist 송은희 Portfolio

---

### 자기소개

---

안녕하세요. 데이터 사이언티스트 신입 송은희입니다.    
모두의연구소 데이터사이언스 부트캠프를 국비과정으로 우수한 성적으로 수료하였으며, 회귀 기반 주택 가격 예측 프로젝트에서 2위를 달성했습니다.    
Final Project에서는 팀장을 맡아 OSINT 뉴스 데이터를 활용한 핵심 키워드 추출 및 지도 시각화 시스템을 성공적으로 구축하였습니다.    
비전공자로서 시작했지만, 빠른 학습력과 끈기를 바탕으로 누구보다 깊이 있게 성장해왔습니다.    
앞으로도 멈추지 않는 배움으로, 데이터로 문제를 정의하고 해결하는 데이터사이언티스트로 성장하겠습니다.    

---

## 목차
### 🏠 [회귀 / Machine Learning] 모두의연구소 Mini Project – 집값 예측하기 (개인 프로젝트)

- **목표:** 주어진 주택 데이터를 분석하여 집값을 예측하는 회귀 모델 구축  
- **데이터:** [Kaggle - House Prices](https://www.kaggle.com/competitions/modu-ds-4-house-prices)  
- **주요 내용:**  
  - 결측치 및 이상치 처리, 피처 스케일링 및 인코딩 수행  
  - 여러 회귀모델(XGBoost, Lasso, Ridge 등)을 비교하여 최적 모델 선정  
  - 하이퍼파라미터 튜닝(GridSearchCV)으로 성능 개선  
- **성과:** Public Score **19,472.07710** 달성 ( 23명 중 **2위**)  
- **기술 스택:** `Python`, `pandas`, `scikit-learn`, `XGBoost`, `matplotlib`

---

### 🛒 [이커머스 / 데이터 분석] 모두의연구소 DATA Thon – 블루오션 / 레드오션 선별하기 (팀 프로젝트)

- **목표:** 브라질 전자상거래 데이터를 분석하여 셀러의 진입 카테고리를 전략적으로 구분 (Blue Ocean vs Red Ocean)  
- **데이터:** [Kaggle - Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)  
- **주요 내용:**  
  - 고객, 주문, 제품, 셀러 데이터를 통합 분석하여 카테고리별 경쟁도 평가  
  - 매출 상위 vs 하위 셀러 특성 비교로 유망 카테고리 도출  
  - Folium 지도 시각화로 지역별 셀러 분포 분석  
- **성과:** 카테고리별 셀러 진입 경쟁도 및 매출 구조를 시각적으로 분석하여, 신규 셀러의 **전략적 진입 의사결정 지원 모델** 제시  
- **기술 스택:** `Python`, `pandas`, `seaborn`, `folium`, `LightGBM`, `matplotlib`

---

### 🛰 [OSINT / NER / GEOINT] 모두의연구소 Final Project – OSINT 데이터를 활용한 GEOINT (팀 프로젝트)

- **목표:** 연합뉴스의 10년치 뉴스 데이터 중 **북한 관련 기사만 선별**하여 핵심 이슈를 도출하고, **지리정보를 기반으로 시각화**  
- **데이터:** 연합뉴스 뉴스 기사 (2016–2025, 약 10년치)  
- **주요 내용:**  
  - 자연어처리(NER) 기반으로 기사 내 지명 및 사건명 추출  
  - TF-IDF, LLM Summarization으로 월별 주요 이슈 자동 선별  
  - GeoCoding을 통해 위경도 변환 후 지도 상에 시각화 (Folium / Dash 활용)  
- **성과:**  
  - 월별 핵심 이슈 및 지역별 사건 분포를 한눈에 파악 가능한 **OSINT 분석 시스템** 구현  
  - LlamaIndex 기반 Summarization과 spaCy NER의 결합으로 **정확도 및 처리 속도 개선**  
- **기술 스택:** `Python`, `pandas`, `spaCy`, `LlamaIndex`, `MongoDB`, `GCP`, `Folium`, `Dash`

---
  
**데이터 사이언티스트 송은희**    
Email : songeh619@gmail.com    
GitHub : DS-EUNHEE
