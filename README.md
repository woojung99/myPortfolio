# 📋 myPortfolio
진행한 프로젝트에 대한 간략한 소개를 담고 있습니다.\
각 프로젝트의 상세 수행 과정 및 소스 코드는 [레파지토리 보러가기] 링크를 통해 확인할 수 있습니다.
### List
- shortcut_2_ur_shampoo.txt
  - 샴푸 리뷰 ABSA 딥러닝 프로젝트
- 따릉이의 봄 (따봄)
  - 따릉이 수요 분석 프로젝트
  
# Projects
## 📌 shortcut_2_ur_shampoo.txt
- 올리브영 샴푸 리뷰 ABSA 프로젝트\
🔎 [레파지토리 보러가기](https://github.com/woojung99/Shortcut_to_Your_Shampoo.txt)
  
### Period
- 2025.05.12 ~ 2025.06.13 (약 1개월)

### Motivation
- 온라인 쇼핑 시 구매 결정에 활용하는 리뷰 정보의 불충분 및 부적절
  - 쇼핑 플랫폼에서 정한 특정 속성에 대해 리뷰어가 직접 선택한 결과를 집계
  - 속성의 종류가 다양하지 않고 해당 집계 정보는 임의로 선택할 가능성이 높은 지표에 의존
  
### Goal
- 샴푸를 구매하고자 하는 소비자들의 결정에 도움이 되는 리뷰 감성 정보 제공 

### Method
- 속성 별 감성 라벨링을 위한 ABSA task 수행
  - Bert 기반의 사전 학습 모델을 통해 전이 학습
  - 최종 모델의 (macro) f1 score 0.9415 달성

### Results
  - 각 제품 별 리뷰 기반 통계 정보 및 시각 자료 제공하는 웹 서비스
    - 🔗 웹 사이트 주소: https://bert-absa-shampoo-web.onrender.com
      
  - [발표 자료](./파이널플젝_발표_최종.pdf)

### Review
  - 개선 및 발전방향
    - 샴푸 중에서 기능(ex. 염색, 탈모 샴푸 등)을 기반으로 한 세부 카테고리를 나누어, 제공할 속성 정보 구분
    - 속성 별 리뷰 요약 AI 모델을 활용한 보다 구체적인 리뷰 정보 제공
    - 소비자가 아닌 판매자를 타겟으로, 마케팅 인사이트 제공을 목적으로 한 분석 정보 도출

### Role
  - 프로젝트 기획 및 실행 전략 수립, 일정 관리 및 업무 트래킹 등 전반적인 운영
  - ABSA 모델 개발
  - 데이터 전처리 및 분석
  - 발표
    
### Tech Stack
| 분야 | 기술/도구 |
|:-:|:-:|
| 프로그래밍 언어 | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> |
| 데이터 수집 및 전처리 | <img src="https://img.shields.io/badge/BeautifulSoup-8B4513?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=Pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/>|
| 시각화 | <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Seaborn-1A5276?style=flat-square&logo=python&logoColor=white"/> |
| 모델링 | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> |
| 웹개발 | <img src="https://img.shields.io/badge/django-092E20?style=flat-square&logo=django&logoColor=white"/>|
| 환경 | <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=white"/> <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/> |
| 협업 | <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> |

## 📌 따릉이의 봄 (따봄)
- 따릉이 수요 분석 프로젝트\
🔎 [레파지토리 보러가기]()

### Period
- 2025.03.25 ~ 2025.04.01 (약 1주)

### Motivation
- 기후동행카드 도입으로 대중교통과 따릉이의 연계를 위한 제도 마련
- 평일 출퇴근 시간대, 따릉이의 높은 이용량 및 쏠림 현상 문제
  
### Goal
- 따릉이 수요가 높은 평일 출퇴근 시간대의 이용 편의 증

### Method
- 평일 출퇴근 시간의 따릉이 이용 행태 파악 및 지하철역 별 수요 공급 불균형 여부 분류
  - 다양한 시각화를 통한 따릉이 이용 행태 분석
  - GeoPandas 를 활용한 잠재 수요 인원 집계 및 적정 거치대 수 계산

### Results
  - 출퇴근 시간의 따릉이는 단거리 이동을 위한 보조적인 교통수단
  - 지하철역 주변 유동인구와 따릉이 수요량이 비례하지 않는다는 분석 결과 도출
  - [발표 자료](./0401_따릉이의봄.pdf)

### Review
  - 개선 및 발전방향
    - 각 지하철역 따릉이 수요 공급 불균형 지표의 세밀화
    - 각 지하철역 반경 내 정확한 잠재 수요 인원 추출 방법 고려

### Role
  - 프로젝트 기획 및 실행 전략 수립
  - 데이터 가공 및 분석
  - 발표
    
### Tech Stack
| 분야 | 기술/도구 |
|:-:|:-:|
| 프로그래밍 언어 | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> |
| 데이터 가공 및 전처리 | <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=GeoPandas&logoColor=white"/>  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=Pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/> |
| 시각화 | <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Seaborn-1A5276?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=Folium&logoColor=white"/>|
| 웹개발 | <img src="https://img.shields.io/badge/django-092E20?style=flat-square&logo=django&logoColor=white"/>|
| 환경 | <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/> |
