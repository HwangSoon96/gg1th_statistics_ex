<div align="center">

# gg1th_statistics_ex

**기술통계부터 가설검정까지 — SciPy · statsmodels 기초 통계 실습**

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![uv](https://img.shields.io/badge/uv-package%20manager-DE5FE9?logo=uv&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5)

</div>

<br>

## 실습 구성

### 1. 기술통계

| 파일 | 내용 |
|---|---|
| `1-1 통계 대표통계량.ipynb` | 산술 · 조화 · 절사 평균, 최빈값, 대푯값 비교 |
| `1-2 통계 산포통계량.ipynb` | 분산, 표준편차, 변동계수, 스케일링 |
| `1-3 통계 분포통계량.ipynb` | 백분위수 · 사분위수, 왜도, 첨도 |

### 2. 가설검정

| 파일 | 내용 |
|---|---|
| `2-1 단일 표본 t검정과 독립 표본 t검정.ipynb` | 정규성 검정 → 가설 설정 → t검정, 결과 해석 |
| `2-2 쌍체 표본 t검정.ipynb` | 같은 대상의 전 · 후 비교 |
| `2-3 일원 분산 분석.ipynb` | 정규성 · 등분산성 검정 → ANOVA → 사후분석 |
| `2-4 상관분석.ipynb` | 피어슨 · 스피어만 상관계수 |
| `2-5 카이제곱 검정.ipynb` | 교차표 기반 독립성 검정, 기대빈도 |

### 3. 종합 문제

| 파일 | 내용 |
|---|---|
| `3.가설검정_test.ipynb` | 취업준비생 25명 AI 면접 코칭 전 · 후 점수 비교 — 검정 방법 선택(쌍체 표본 t검정) → 정규성 검정 → 검정 → 결론 |

실습 데이터는 `datas2/`에 포함

<br>

## 시작하기

```bash
git clone https://github.com/HwangSoon96/gg1th_statistics_ex.git
cd gg1th_statistics_ex

uv sync
```

VS Code 또는 Jupyter에서 `.venv` 커널을 선택해 노트북 실행
