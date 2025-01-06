<h2 align="center"> CNN 이용한 차량 분류 모델 🚗</h2>

<p align="center">
    <img src="https://cdn.discordapp.com/attachments/1291606249141436544/1325709905331486751/cover.png?ex=677cc70f&is=677b758f&hm=af028cdfdb6937e60ddc893a994e7e26b107e252fa6e0556f76ba609146e1bd8&" style="width:60%; height:60%;" />
</p>



#### 🌱 팀원
<a href = "https://ohgiraffers.notion.site/9e6c411ea3db4bc3896afea1560ea61b?pvs=4"><img src="https://img.shields.io/badge/팀 Notion-ffffff?style=flat&logo=Notion&logoColor=black" /></a>   
[😎오현옥](https://github.com/alonee9393)&nbsp;&nbsp;&nbsp;&nbsp;[🐬유미라](https://github.com/raramii)&nbsp;&nbsp;&nbsp;&nbsp;[🦄진현석](https://github.com/culown)&nbsp;&nbsp;&nbsp;&nbsp;[🎸최동현](https://github.com/dh823)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


---
## ✨ 주제 선정 배경
음주사고, 졸음운전을 비롯한 교통사고에 의해 발생되는데, 사고 후 처리를 하지 않고 사고를 인지했음에도 도망 갔을 때 **뺑소니** 라 함   
우리는 그 동안 사고라 하면 CCTV, 블랙박스 자료를 통해 사고 차량을 잡는 경우도 있었지만 억울한 경우도 있었음   
딥러닝 기반의 CNN 모델을 비롯한 여러 모델을 활용하여 영상을 분석해, **뺑소니** 차량을 신속히 식별할 수 있을 것

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

<a href = "https://www.notion.so/ohgiraffers/VGG-aa3fbe441bf54a9e965d7b8be11cba1a"><img src="https://img.shields.io/badge/VGG16-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
<a href = "https://www.notion.so/ohgiraffers/ResNet-a830b33f1b4643aa8aa0544ec4e366d2"><img src="https://img.shields.io/badge/ResNet-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
<a href = "https://www.notion.so/ohgiraffers/InceptionV3-21f0c76b5fa84172b26471e550e79ed5"><img src="https://img.shields.io/badge/InceptionV3-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
<a href = "https://www.notion.so/ohgiraffers/EfficientNetB1-70927442a616436393c9f2450c9b94f5"><img src="https://img.shields.io/badge/EfficientNet-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
<a href = "https://www.notion.so/ohgiraffers/Xception-4755e33445d24d3098471f0b4ba8207e"><img src="https://img.shields.io/badge/Xception-ffffff?style=flat&logo=Notion&logoColor=black" /></a>
<a href = "https://www.notion.so/ohgiraffers/MobileNet-405b034cd90d47b89f85d9522155258e"><img src="https://img.shields.io/badge/MobileNet-ffffff?style=flat&logo=Notion&logoColor=black" /></a>


---

## ❗ 기대효과
- 정확한 차량 식별 - AI 기술로 브랜드, 차종, 모델 정밀 분류 및 식별
- 뺑소니 차량 추적 시스템 - 전국 CCTV 네트워크를 활용해 뺑소니 차량 식별
- 첨단 기술 통합 - CCTV에 AI 소프트웨어와 임베디드 장치 추가로 정보 저장 확대
- 사고 예방과 인식 제고 - 뺑소니 차량 식별 가능성을 알리며 사고 예방 및 사회적 인식 강화
