---
title: Deep Image Prior
date: '2018-01-15'
---

## 발표자: 이용주

<center> <img src="/seminar/img/new3.PNG" style="height:400px" /></center>

딥 컨볼루션 네트워크는 Image Generation과 Image Restoration 기법에도 널리 사용되고 있습니다. 하지만 Image Generation과 Restoration을 위한 네트워크는 학습을 필요로 하며 이는 많은 양의 example image들이 필요합니다.

이 논문은 위의 기존 방식의 네트워크들을 학습하는 것과 다르게 Generator 네트워크 구조가 low-level image statistics로도 prior 정보를 얻기 충분하다는 것을 보여줍니다. 또한 무작위로 초기화된 Neural Network로도 Denoising, Super Resolution, Inpainting에 훌륭한 결과를 얻을 수 있는 것을 보여줍니다. 이에 더 나아가 같은 Prior 정보를 이용하여 Invert Deep Neural Representation과 Flash와 Flash-no 사진을 이용한 이미지의 복원에도 사용되는 것을 보입니다.

이번 세미나에서는 Deep Image Prior라는 논문에서 prior가 무엇을 의미하고 적은 양의 image로 어떻게 Denoising, Super, Resolution, Inpainting을 할 수 있는 지 그 방법에 대하여 중점적으로 발표하려고 합니다.
