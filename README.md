# CNN 이미지 분류 실험 데이터셋

## 설명
고등학교 탐구 활동 및 실험에 사용한 이미지 데이터셋을 정리하였습니다.
- 목표: 학습 데이터 규모에 따른 CNN 이미지 분류 성능 변화 분석

Oxford-IIIT Pet Dataset에서 Samoyed와 British Shorthair 품종의 이미지를 선별하여 실험에 사용하였습니다.

데이터는 다음과 같이 구성하였습니다.

- 분류 대상: Samoyed, British Shorthair
- 학습 데이터: 클래스별 50장, 100장, 150장
- 평가 데이터: 별도로 선별하여 동일한 조건에서 사용
- 이미지 분류 도구: Google Teachable Machine

본 저장소에는 실험에 사용한 데이터를 공개하였으며, 보고서에서는 이를 활용한 실험 과정과 결과를 분석하였습니다.

## 사용 언어 및 도구
- Google Teachable Machine
- Oxford-IIIT Pet Dataset

## 데이터 출처
Oxford-IIIT Pet Dataset에서 실험에 사용할 이미지를 선별하였습니다.

출처: https://www.robots.ox.ac.uk/~vgg/data/pets/
제공: Visual Geometry Group, University of Oxford

## 데이터 구성
각 품종의 이미지를 학습 데이터와 평가 데이터로 구분하여 사용하였습니다.

### Samoyed
학습 데이터: 50장 / 100장 / 150장
평가 데이터: 별도 선별

### British Shorthair
학습 데이터: 50장 / 100장 / 150장
평가 데이터: 별도 선별

## 실험 방법
1. Oxford-IIIT Pet Dataset에서 Samoyed와 British Shorthair의 이미지를 선별합니다.
2. 각 품종의 이미지를 학습 데이터와 테스트 데이터로 구분합니다.
3. 클래스별 학습 이미지 수를 50장, 100장, 150장으로 설정합니다.
4. 각 데이터셋을 Google Teachable Machine에 입력하여 이미지 분류 모델을 학습합니다.
5. 동일한 테스트 데이터를 사용하여 각 모델의 분류 성능을 측정합니다.
6. 학습 데이터 규모에 따른 분류 성능의 변화를 비교합니다.

## 결과
학습 데이터 규모에 따른 분류 성능을 비교한 결과는 다음과 같습니다.

| 클래스별 학습 데이터 |	분류 성능 |
|---|---|
| 50장 | 실험 후 작성 |
| 100장 | 실험 후 작성 |
| 150장 | 실험 후 작성 |
