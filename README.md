# tensorflow_learning
실전! 텐서플로 2를 활용한 딥러닝 컴퓨터 비전 책을 공부하면서 배운 지식을 기록

# 컴퓨터비전과 신경망
컴퓨터 비전이란?
컴퓨터 과학(알고리즘, 데이터처리, 그래픽), 물리학, 수학, 생물학같은 여러 연구 개발 분야의 교차점에 있어서 핵심만 꼽자면 "디지털 이미지에서 자동으로 정보를 추출하는 것"으로 요약

# Effective Receptive Field(ERF)
ERF는 입력 이미지에서 거리가 먼 요소를 상호 참조하고 결합하는 네트워크 능력에 영향을 줄 수 있어서 딥러닝에서 중요한 개념이다
입력이미지의 영역을 정의해 주어진 계층을 위한 뉴런의 활성화에 영향을 미친다
RF가 단순히 필터의 크기나 윈도우의 크기로 불리기 때문에 ERF대신 RF로 불리기도 한다. 
5X5 kernel에서 특정 셀에 영향을 준 실제 kernel size
인간은 시야가 넓은 것 같지만 실제로 집중하여 쳐다보고 있는 곳 말고는 제대로 인지하지 못한다. 인간의 인공와에 해당하는 부분 

# CNNs with Tensorflow
LeNet5 구조 - 코랩 작성중

# 현대적인 최적화 기법
Gradient Descent -> 3가지 주의점 

# 고급 최적화 기법
momentum -> NAG -> Ada Famliy 

# 정규화 기법
Early stopping -> L1, L2 -> Dropout


# YOLO의 주요개념

Backbone - CNN cell을 거쳐 feature맵을 생성하는 과정 
Input image -> 2개의 conv layers -> feature map을 생성하는 이미지
<img width="40%" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREgHNabnzopsK37QKvjnNERDZQ0nDT3wAfqQ&usqp=CAU"/>
