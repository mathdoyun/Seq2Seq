## Seq2Seq

논문 링크: [Seq2Seq](https://arxiv.org/pdf/1409.3215.pdf) / [Attention Mechanism](https://arxiv.org/abs/1409.0473.pdf)

Seq2Seq (Sequence to Sequence)는 문장을 문장으로 번역하는 데 사용되는 모델로, 주로 입력과 출력의 길이가 다른 데이터에서 사용된다. 이 코드에서는 영어를 한국어로 번역하는 task를 다루고 있는데, 이 경우 encoder는 영어의 정보를 추출하고 decoder는 encoder의 마지막 상태를 이용해 영어를 한국어로 번역한다. 기존에 주어진 번역 데이터셋을 이용하여 encoder와 decoder를 학습하며, 이 과정에서 attention mechanism이 사용된다. 이 과정을 그림으로 표현하면 다음과 같다.

<img src="https://github.com/mathdoyun/Seq2Seq/assets/135238974/03803e27-9afb-485d-a96f-310e31ae4737" width="75%" height="75%"/>

> 출처: 텐초의 파이토치 딥러닝 특강
