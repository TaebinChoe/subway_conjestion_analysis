# 지하철 혼잡도 측정을 위한 객체 탐지 모델 실험 (Faster R-CNN 기반)
<img src="https://i.namu.wiki/i/W2eZzV90oBH8BJOtDStobGTsG1s1FeB0X-alj828UqUgA4zVYKZV7hoVS9nZPkYf0tD6gYtTwjx7R191bTh8DBMEISGVs9m-FgmRAFeYt01S2EqoSswrAvo4n3hxOg-Bbbg7lvmL9Fa7GY0EKZKOPg.svg" alt="KRRI Logo" width="300"/>
본 프로젝트는 2024년 여름방학 동안 **한국철도기술연구원(KRRI, Korea Railroad Research Institute)** 에서 근무하면서 수행한 연구 과제의 일환으로 진행되었습니다.

---

## 프로젝트 개요

지하철 내 **실시간 혼잡도 측정 시스템**을 구축하기 위한 사전 연구로서, 다양한 **객체 탐지(Object Detection)** 모델을 실험적으로 테스트하였습니다.  
본 저장소에는 그중에서 **Faster R-CNN** 기반 실험 코드가 포함되어 있습니다.

> **주의:** 실제 데이터 및 시연 결과는 개인정보 및 저작권 이슈로 인해 외부에 공개되지 않습니다.

---

## 연구 목적

- 다양한 **Computer Vision 모델 후보군**을 비교하여 지하철 혼잡도 측정에 가장 적합한 모델을 선정.
- 복잡한 환경(조명 변화, 다양한 사람 수, 카메라 위치 등)에서도 **정확한 탐지 성능**을 발휘하는 모델 탐색.
- **Faster R-CNN**이 보이는 높은 정확도와 유연한 구조를 활용하여, 향후 실서비스에 적용 가능한 기초 성능 평가 수행.

---

## 사용된 모델: Faster R-CNN

Faster R-CNN은 R-CNN 계열의 세 번째 모델로, 속도와 정확도 사이에서 균형을 이룬 대표적인 객체 탐지 알고리즘입니다.
