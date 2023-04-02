[![banner](assets/banner.png)](http://introtodeeplearning.com)

이 리포지토리에는 [MIT Introduction to Deep Learning](http://introtodeeplearning.com)에 대한 모든 코드 및 소프트웨어 랩이 포함되어 있습니다! 모든 강의 슬라이드와 비디오는 프로그램 웹 사이트에서 사용할 수 있습니다.

(개인 공부 목적으로 번역하기 때문에 올바르지 못한 번역이 있을 수 있습니다. [원본 리포지토리](https://github.com/aamini/introtodeeplearning)를 확인해주세요. 번역자: [MOKA-AYUMU](https://github.com/moka-ayumu))

# 지침

MIT 딥 러닝 소개 소프트웨어 랩은 자신의 진도에 맞춰 완료하도록 설계되었습니다. 각 랩이 끝날 때 랩 경쟁의 일부로 자료를 제출하는 방법에 대한 지침이 있습닌다. 이러한 지침에는 제출해야 하는 정보와 형식이 포함됩니다.

## Google Colaboratory 에서 랩 열기:

2023년 딥러닝 입문 랩은 모두 클라우드에서 실행되는 Jupyter 노트북 환경인 Google Colaboratory에서 실행되므로 아무 것도 다운받을 필요가 없습니다. 이 랩을 실행하려면 Google 계정이 있어야 합니다.

깃허브 레포에서 실행하고 싶은 랩 폴더(`lab1`, `lab2`, `lab3`)로 가고 적절한 파이썬 노트북(\*.ipynb)를 엽니다. 그리고, 랩 상단에 있는 "Colab 실행"을 클릭하면 됩니다!

## 랩 진행하기

이제 랩을 진행하려면 Colab에서 Jupyter 노트북을 엽니다. "런타임" 탭에서 "런타임 유형 변경"으로 이동합니다. 팝업 창에서 "런타임 유형"에서 "Python3"을 선택하고 "하드웨어 가속기"에서 "GPU"를 선택합니다. 노트북을 살펴보고 `#TODO` 부분을 채우면 코드를 직접 컴파일 할 수 있습니다!

### MIT Deep Learning 패키지

랩 내에서 Python 패키지 리포지토리에서 `mitdeeplearning`이라는 Python 패키지를 설치한다는 것을 알 수 있습니다.

`pip install mitdeeplearning`

이 패키지는 코스 전체에서 사용하는 편의 기능이 포함되어 있으며 다른 Python 패키지처럼 가져올 수 있습니다.

`>>> import mitdeeplearning as mdl`

각 랩에서 이 작업을 수행하지만 패키지도 동일한 라이선스에 따라 오픈 소스이므로 클래스 외부에서도 사용할 수 있습니다.

## 강의 비디오

[<img src="assets/video_play.png" width="500">](https://www.youtube.com/watch?v=njKP3FqW3Sk&list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI&index=1)

모든 강의 비디오는 온라인에서 공개적으로 사용할 수 있으며 위에 링크되어 있습니다! MIT Deep Learning 소개 이외의 강의 슬라이드 사용 및 수정은 다음을 참조해야합니다.

> © MIT Introduction to Deep Learning
>
> http://introtodeeplearning.com

## License

All code in this repository is copyright 2023 [MIT Introduction to Deep Learning](http://introtodeeplearning.com). All Rights Reserved.

Licensed under the MIT License. You may not use this file except in compliance with the License. Use and/or modification of this code outside of MIT Introduction to Deep Learning must reference:

> © MIT Introduction to Deep Learning
>
> http://introtodeeplearning.com
