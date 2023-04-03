# MIT 6.S191 Lab 1: TensorFlow 소개 및 RNNs으로 음악 생성

![alt text](https://github.com/moka-ayumu/introtodeeplearning-kr/raw/master/lab1/img/music_waveform.png)

## 파트 1: TensorFlow 소개

TensorFlow는 기계 학습에 광범위하게 사용되는 소프트웨어 라이브러리입니다. 여기서 우리는 계산이 어떻게 표현되는지 그리고 TensorFlow에서 간단한 신경망을 정의하는 방법을 배웁니다. TensorFlow는 딥러닝 모델을 구축하고 교육하기 위한 강력하고 직관적인 프레임워크를 제공하는 [Keras](https://www.tensorflow.org/guide/keras)라는 고급 API를 사용합니다. 이 섹션에서는 TensorFlow, Keras API 및 [Eager](https://research.googleblog.com/2017/10/eager-execution-imperative-define-by.html)에서 지원하는 TensorFlow의 새로운 명령형 실행 스타일의 기본 계산에 대해 알아봅니다.

## 파트 2: RNNs으로 음악 생성

랩의 두 번째 부분에서는 음악 생성을 위한 RNN(Recurrent Neural Network)을 구축하는 방법을 알아봅니다. ABC 표기법으로 악보의 다음 문자를 예측하기 위해 "문자 RNN(character RNN)"을 사용할 것입니다. 마짖막으로 이 모델에서 샘플링하여 이전에 들어본 적이 없는 완전히 새로운 음악 파일을 생성합니다!
