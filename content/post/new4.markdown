---
title: Edge-Guided Single Depth Image Super Resolution
date: '2018-01-15'
---

## 발표자: 이현성

<center> <img src="/seminar/img/new4.PNG" style="height:400px" /></center>

최근 Depth Map은 물체와 배경을 인식 및 이해하기 위하여 많은 Application에 널리 사용되고 있습니다. 그러나 Depth 카메라(e.g. Microsoft Kinect, 3D-ToF Cameras)에서 제공되는 Depth Map은 그 품질과 해상도가 제한되므로 Depth Map Super Resolution이 필요하게 됩니다.

이번 세미나에서는 MRF(Markov Random Field) 모델 기반의 Single Depth Image Super Resolution 논문 중 하나인 `Edge-Guided Single Depth Image Super Resolution, IEEE Transactions on Image Processing, 2016`을 리뷰하려 합니다. 이 논문에서는 MRF Optimization을 사용하여 기존처럼 Depth Value를 직접 추정하는 것이 아닌, 고해상도의 Depth Edge를 찾는 것에 초점을 맞추었습니다.

본 세미나에서는 HR Depth Edge를 찾는데 사용한 MRF Energy Function과 Optimization을 통해 찾아낸 Edge를 기반으로 Depth값을 채우는 `Edge Assisted Depth Interpolation`에 대하여 살펴보겠습니다.
