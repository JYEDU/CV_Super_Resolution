
# 2021 Computer Vision Term Project
4개 분야 선정하여 베이스라인 찍기
## My Repository
1. [2D Objection Detection](https://github.com/JYEDU/CV_YOLOv5)
2. [Scene Text Recognition](https://github.com/JYEDU/CV_Scene_Text_Recognition)
3. [Super Resolution](https://github.com/JYEDU/CV_Super_Resolution)
4. [Image to Image(Ther2RGB)](https://github.com/JYEDU/CV_Image-To-Image)


## Super Resolution (DCSCN)

1. Challenge Leaderboard
    - [LINK](http://203.250.148.129:3088/web/challenges/challenge-page/58/overview)
    
2. Super Resolution 챌린지 개요
    - Image Enhancement / Image Restoration 작업
    - Scale Factor (x2, x4), Noise를 갖는 Low Resolution에서 High Resolution까지의 화질 복원 및 향상을 목표로 함

![image](https://user-images.githubusercontent.com/87462769/143516786-50d116ca-0ff6-498f-b9c7-3e510c1401e0.png)


3. 방법론
    - 딥러닝 기반의 Single-Image Super-Resolution (SISR) 모델인 네트워크에서 Deep CNN에 의한 빠르고 정확한 이미지 초해상도의 텐서플로 구현
    - 효율적인 네트워크 설계를 통한 화질 향상
    - Low Resolution을 Input으로 한 모델
    - Skip Connection과 Network in Network를 사용한 모델

![image](https://user-images.githubusercontent.com/87462769/143516868-b09c81e3-fadd-4628-872d-65802005b295.png)

4. 참고자료
    - [[Paper](https://arxiv.org/ftp/arxiv/papers/1707/1707.05425.pdf)] Fast and Accurate Image Super Resolution by Deep CNN with Skip Connection and Neural Network 
    - [[Github](https://github.com/chldydgh4687/09_2021-2.ComputerVision_DCSCN_pytorch)] 09_2021-2.ComputerVision_DCSCN_pytorch Repository
    - [[Github](https://github.com/jiny2001/dcscn-super-resolution))] dcscn-super-resolution
    - [[Youtube](https://www.youtube.com/watch?v=OpgsHyngR_A&list=PL1xKqHsVFgvnM3zhBkbTZy5l_13x5R3Jq&index=6)] 2021-2세종대_컴퓨터비전_SuperResolution

## 원복 과정에 대한 챌린지 제출 파일
1. eval.ai 리더보드상의 기록 캡쳐본
2. 베이스라인을 찍기 위한 나의 repository
3. 제출 과정에 대한 동영상 링크(베이스라인 알고리즘 설명 및 베이스라인을 찍기 위한 과정을 설명)
