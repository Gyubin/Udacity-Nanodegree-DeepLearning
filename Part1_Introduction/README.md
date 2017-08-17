# Part 1, Introduction

## 1. 환경 설정

- 개발 환경 세팅: Anaconda 혹은 pip를 이용한 가상환경, 라이브러리 설치
- Jupyter notebook 사용법 정리

## 2. Deep Learning Application

- [Style Transfer](https://github.com/lengstrom/fast-style-transfer)
    + dependencies: `pip install tensorflow scipy pillow`
    + pretrained weights: [Google Drive](https://drive.google.com/drive/folders/0B9jhaT37ydSyRk9UX0wwX3BpMzQ)
    + Transfer: `python evaluate.py --checkpoint ./rain-princess.ckpt --in-path <path_to_input_file> --out-path ./output_image.jpg`
- [DeepTraffic](http://selfdrivingcars.mit.edu/deeptrafficjs/)
    + Neural Networks를 이용한 자율 주행 시뮬레이션 사이트.
    + 초기 자동차의 움직임은 safety 기반으로 학습된 상태
    + input: 주변 차량의 상태
    + output: 좌우로 이동, 속력 증감, 무반응
- [Flappy Bird](https://github.com/yenchenlin/DeepLearningFlappyBird)

    ```
    conda install -c menpo opencv3
    pip install pygame tensorflow
    git clone https://github.com/yenchenlin/DeepLearningFlappyBird.git
    cd DeepLearningFlappyBird
    python deep_q_network.py
    ```

## 3. Recommend books

- [Neural Networks And Deep Learning](http://neuralnetworksanddeeplearning.com/)
- [The Deep Learning Textbook](http://www.deeplearningbook.org/)
- [Grokking Deep Learning](https://www.manning.com/books/grokking-deep-learning)
