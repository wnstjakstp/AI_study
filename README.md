이 저장소는 다양한 딥러닝 모델을 구현하고 비교하는 실습 내용을 포함하고 있습니다. 각 과제에서는 특정 데이터셋을 활용하여 다양한 모델을 학습하고 평가하며, 그 과정에서 모델 구조를 깊이 이해하고자 합니다.

📝 진행한 과제

FC (Fully Connected Neural Networks)
	•	사용 데이터셋: STL-10
	•	주요 목표:
	•	다층 퍼셉트론(MLP) 설계
	•	학습 및 평가 진행
	•	torch.utils.data.Dataset 활용하여 데이터셋 클래스 구현

CNN (Convolutional Neural Networks)
	•	사용 데이터셋: Oxford Pets
	•	주요 목표:
	•	Conv2D 기반 커스텀 CNN 아키텍처 구축
	•	Batch Normalization(BN), Dropout, Skip-connection 적용
	•	torch.utils.data.Dataset 활용하여 데이터셋 클래스 구현

SeNet & ResNet 비교
	•	사용 데이터셋: Caltech 101
	•	주요 목표:
	•	SeNet 및 ResNet 모델 구현 및 비교
	•	학습 경향성과 평가 결과 분석

 RNN, LSTM, GRU 비교
	•	사용 데이터셋: StockLlama - ETH/USD
	•	주요 목표:
	•	RNN, LSTM, GRU 모델 구현
	•	학습 및 평가 결과 비교 분석
