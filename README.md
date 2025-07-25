##  📊지역별 인구 및 CCTV 규모 시각화하기
![image](https://user-images.githubusercontent.com/82020828/222196259-37e9888d-eaa9-4982-b458-ff0be1ca21a9.png)

<br><br>

## 📝 프로젝트 개요
- 프로젝트 명 : 지역별 인구 및 CCTV 규모 시각화
- 참여 인원 : 1인
- 개발 기간 : 2021.06.15 ~ 2021.06.21

<br><br>

## 🛠️ Stacks 
### Environment
![JupyterLab](https://img.shields.io/badge/JupyterLab-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-42B13F?style=for-the-badge&logo=anaconda&logoColor=white)

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

<br><br>

## ✨ 특징
- 서울 열린 데이터 광장에서 제공하는 CSV 데이터 활용
- "서울시 자치구 년도별 CCTV 현황"
- "서울시 주민등록인구(구별) 통계"
- Pandas, Numpy, matplotlib 라이브러리 사용
- 2015년 데이터와 2020년의 데이터를 비교하여 시각화 (2015년도 = 투명도 20%, 2020년도 = 투명도 90%)
- x축 : 인규 규모, Y축 : CCTV 규모
- 텍스트 : 자치구 이름 및 년도
- 색상 : 일차원(선형) 회귀선으로부터의 오차
- "유클리드 거리"를 이용하여 2015년 위치에서 2020년 위치로 이동한 궤적 시각화
- 궤적은 최대 이동 거리에 상대적으로 비례하는 강도로 지정\
