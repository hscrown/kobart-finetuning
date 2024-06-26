# kobart-finetuning

# 프로젝트 개요
이 프로젝트는 한국어 텍스트 데이터를 기반으로 KoBART 모델을 파인튜닝하는 과정을 다룹니다. 주요 목표는 형사사건에 최적화 된 한국어 자연어 요약 모델을 만드는 것 입니다.

# 기술 스택
- 프로그래밍 언어: Python
- 딥러닝 프레임워크: PyTorch, Hugging Face Transformers
- 기타 라이브러리: Pandas, NumPy, Matplotlib, NLTK, ROUGE

# 프로젝트 세부 사항
- 초기 설정: 필요한 라이브러리를 설치하고, Google Colab 환경에서 Google 드라이브를 마운트하여 데이터를 저장 및 불러옵니다.
- CUDA 설정: GPU 사용 가능 여부를 확인하여 모델 학습 속도를 최적화합니다.
- 데이터 전처리: 텍스트 데이터를 토크나이저를 사용하여 토큰화하고, 학습 및 검증 데이터셋을 생성합니다.
- 모델 파인튜닝: 사전 학습된 KoBART 모델을 불러와서, 준비된 데이터셋을 사용하여 모델을 파인튜닝합니다.
- 모델 평가: ROUGE 점수와 같은 성능 지표를 사용하여 모델의 성능을 평가하고, 결과를 시각화합니다.
- 모델 저장 및 불러오기: 학습된 모델을 저장하고, 필요 시 불러와서 사용할 수 있도록 준비합니다.
