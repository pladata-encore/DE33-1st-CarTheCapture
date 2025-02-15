<h2 align="center"> CNN 이용한 차량 분류 모델 🚗</h2>

<p align="center">
    <img src="https://cdn.discordapp.com/attachments/1291606249141436544/1325709905331486751/cover.png?ex=677cc70f&is=677b758f&hm=af028cdfdb6937e60ddc893a994e7e26b107e252fa6e0556f76ba609146e1bd8&" style="width:60%; height:60%;" />
</p>



#### 🌱 팀원
<a href = "https://ohgiraffers.notion.site/9e6c411ea3db4bc3896afea1560ea61b?pvs=4"><img src="https://img.shields.io/badge/팀 Notion-ffffff?style=flat&logo=Notion&logoColor=black" target="_blank"/></a>&nbsp;&nbsp;
<a href = "https://onedrive.live.com/:p:/g/personal/5620B07780B8C77B/EVSZTio2bnpGuxALd4gTVy8Bj-AhG0Y8rMaO_m1QhRQeSQ?resid=5620B07780B8C77B!s2a4e99546e36467abb100b778813572f&ithint=file%2Cpptx&e=y89k5K&migratedtospo=true&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3AvYy81NjIwYjA3NzgwYjhjNzdiL0VWU1pUaW8yYm5wR3V4QUxkNGdUVnk4QmotQWhHMFk4ck1hT19tMVFoUlFlU1E_ZT15ODlrNUs"><img src="https://img.shields.io/badge/PPT자료-B7472A?style=flat&logo=microsoft-powerpoint" target="_blank"/></a>

[😎오현옥](https://github.com/alonee9393)&nbsp;&nbsp;&nbsp;&nbsp;[🐬유미라](https://github.com/raramii)&nbsp;&nbsp;&nbsp;&nbsp;[🦄진현석](https://github.com/culown)&nbsp;&nbsp;&nbsp;&nbsp;[🎸최동현](https://github.com/dh823)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


---
## ✨ 주제 선정 배경

- 뺑소니 사고는 책임 소재 규명이 어려워 가해 차량을 찾는 것이 중요함. 이를 해결하기 위해 신속, 정확한 차량 식별 기술이 요구됨에 따라
CNN 기반의 딥러닝 모델들을 사용하여 차종의 특성을 학습시켜 높은 정확도 차량을 분류하는 것을 목표로 함
---

## 🖥️ 데이터 수집 및 전처리

> ### [사용 데이터셋](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=172)   
- 국산차 위주의 데이터 구성과, 적절한 크기의 데이터로 활용하기에 적합하다 판단하여 선택
> ### 데이터 전처리
- SUV, Sedan, Truck, Van 네가지 라벨로 분류
- train 데이터를 train, validation으로 나눔
- 사용하는 모델에 따라 input size 조절
- ImageDataGenerator 사용하여 스케일링

---
## 👤 사용 모델

> ### 프로젝트에 적용한 CNN 모델

- <a href = "https://www.notion.so/ohgiraffers/VGG-aa3fbe441bf54a9e965d7b8be11cba1a"><img src="https://img.shields.io/badge/VGG16-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
- <a href = "https://www.notion.so/ohgiraffers/ResNet-a830b33f1b4643aa8aa0544ec4e366d2"><img src="https://img.shields.io/badge/ResNet-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
- <a href = "https://www.notion.so/ohgiraffers/InceptionV3-21f0c76b5fa84172b26471e550e79ed5"><img src="https://img.shields.io/badge/InceptionV3-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
- <a href = "https://www.notion.so/ohgiraffers/EfficientNetB1-70927442a616436393c9f2450c9b94f5"><img src="https://img.shields.io/badge/EfficientNet-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
- <a href = "https://www.notion.so/ohgiraffers/Xception-4755e33445d24d3098471f0b4ba8207e"><img src="https://img.shields.io/badge/Xception-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
- <a href = "https://www.notion.so/ohgiraffers/MobileNet-405b034cd90d47b89f85d9522155258e"><img src="https://img.shields.io/badge/MobileNet-ffffff?style=flat&logo=Notion&logoColor=black" /></a>


---

## ❗ 기대효과
- 정확한 차량 식별 - AI 기술로 브랜드, 차종, 모델 정밀 분류 및 식별
- 뺑소니 차량 추적 시스템 - 전국 CCTV 네트워크를 활용해 뺑소니 차량 식별
- 첨단 기술 통합 - CCTV에 AI 소프트웨어와 임베디드 장치 추가로 정보 저장 확대
- 사고 예방과 인식 제고 - 뺑소니 차량 식별 가능성을 알리며 사고 예방 및 사회적 인식 강화
