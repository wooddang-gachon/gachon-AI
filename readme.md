# AI - Class

---

가천대학교 인공지능 개론 (2026-1)
본 저장소는 2026학년도 1학기 가천대학교 인공지능 개론 강의의 실습 자산 및 학술적 분석 기록을 보관한다. 선형 회귀(Linear Regression)와 분류(Classification) 모델을 중심으로 한 지도 학습 알고리즘의 구현과 데이터셋 분석을 포함한다.

📂 Repository Structure
Plaintext
.
├── 99. archive/ # 과거 실험 모델 및 레거시 코드 (LR1 ~ LR4)
├── week1/ # 주차별 실습 및 분석 과제
│ ├── BreastCancer/ # 유방암 데이터셋 기반 이진 분류 및 회귀 분석
│ └── Diabete/ # 당뇨병 데이터셋 기반 수치 예측 및 분류 모델
└── readme.md # 프로젝트 개요 및 명세


🛠 Tech Stack
- Language: Python 3.x
- Environment: Jupyter Notebook (.ipynb)
- Primary Libraries:
- scikit-learn: 머신러닝 알고리즘 구현 및 데이터 전처리
- pandas / numpy: 수치 해석 및 데이터 구조화
- matplotlib / seaborn: 모델 성능 및 데이터 분포 시각화

🔬 Core Implementations

1. Regression Analysis
   DiabeteRegression: 당뇨병 수치 예측을 위한 선형 회귀 모델 구현

BreastCancerRegression: 종양 특성 데이터에 기반한 연속적 변수 추론

2. Classification Tasks
   BreastCancerClassifier: 악성/양성 종양 판별을 위한 이진 분류 알고리즘

DiabeteClassifier: 특정 임계값 기준의 당뇨 발병 여부 분류

3. Archive (Historical Models)
   LR 1-4 Series: 단일/다중 선형 회귀의 단계별 고도화 및 파라미터 최적화 실험 기록

📝 Usage notes
모든 .ipynb 파일은 독립적인 실행 환경을 보장하며, scikit-learn 내장 데이터셋을 로드하여 즉시 재현 가능하다.

archive 디렉토리 내의 파일은 모델 성능 향상을 위한 귀납적 시도들의 로그로 활용된다.
