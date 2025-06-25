# myPortfolio
# Introduction

# Projects
## 1. shortcut_2_ur_shampoo.txt
- 올리브영 샴푸 리뷰 ABSA 프로젝트
  
### Period
- 2025.05.12 ~ 2025.06.13 (약 1개월)

### Motivation
- 온라인 쇼핑 시 구매 결정에 활용하는 리뷰 정보의 불충분 및 부적절
  
### Goal
- 샴푸를 구매하고자 하는 소비자들의 결정에 도움이 되는 리뷰 정보 제공 

### Method
- 속성 별 감성 라벨링을 위한 ABSA task 수행
  - Bert 기반의 사전 학습 모델을 통해 전이 학습
  - 최종 모델의 (macro) f1 score 0.9415 달성

### Results
  - 각 제품 별 리뷰 기반 통계 정보 및 시각 자료 제공하는 웹 서비스
    - 웹 사이트 주소: https://bert-absa-shampoo-web.onrender.com
      
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
    
## Tech Stack
| 분야 | 기술/도구 |
|:-:|:-:|
| 프로그래밍 언어 | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> |
| 데이터 수집 및 전처리 | <img src="https://img.shields.io/badge/BeautifulSoup-8B4513?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=Pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/>|
| 시각화 | <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Seaborn-1A5276?style=flat-square&logo=python&logoColor=white"/> |
| 모델링 | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> |
| 웹개발 | <img src="https://img.shields.io/badge/django-092E20?style=flat-square&logo=django&logoColor=white"/>|
| 환경 | <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=white"/> <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/> |
| 협업 | <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> |

## 2. 따봄
- 따릉이 수요 분석 프로젝트
- (회귀로 수요 예측 누락부분 채우기)
- pdf 발표자료 링크
