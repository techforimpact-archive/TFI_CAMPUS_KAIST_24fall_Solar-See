# Solar-See 2024

## Overview
**Solar-See**는 비계량 태양광 패널을 발견하고, 이를 통해 전력 수요 예측의 정확도를 높이기 위해 개발된 AI 기반 게임 및 지도 서비스입니다.  
- **비계량 태양광 패널 지도**  
- **태양광 패널 찾기 게임**  
  *유저의 게임 데이터를 기반으로 AI가 놓친 태양광 패널을 추가적으로 발견합니다.*  

### 빠르게 시작하기
모바일에서 **[Solar-See 바로가기](https://solar-see.site)**  
QR 코드를 스캔하여 접속할 수 있습니다.  
<img src="https://github.com/user-attachments/assets/5f1a69bf-6aa5-48fe-ace0-e10757c47aea" alt="QR Code" style="width:25%"/>

---

## 솔루션 한줄 요약
**태양광 패널 찾기 게임**을 통해 AI의 패널 탐지 능력을 개선합니다.

---

## 풀고자 하는 사회 문제 정의

1. **신재생에너지는 필수적인 에너지원입니다.**  
   - 지속가능한 발전과 환경오염 감소를 위해 필요합니다.  

2. **전력 수요 예측 실패로 신재생 에너지 발전소가 가동 중단되는 문제가 있습니다.**  
   - 화력 및 원자력 발전소는 가동 중단이 어려워 신재생에너지가 주로 희생됩니다.  

3. **비계량 태양광 패널은 전력 수요 예측을 어렵게 만듭니다.**  
   - 계측되지 않은 태양광 발전량은 전력 피크 시간대의 11%를 차지합니다.  

4. **Solar-See는 비계량 태양광 패널을 발견해 문제를 해결합니다.**  
   - 전국의 모든 비계량 패널을 찾고, 전력 수요 예측의 정확도를 높여 신재생 에너지의 확산을 돕습니다.  

---

## 솔루션 개요

### 1. **항공사진과 AI를 활용한 태양광 패널 탐색**  
   - 기존 위성사진보다 화질이 좋은 항공사진을 사용하여 AI를 학습시킵니다.  

### 2. **비계량 태양광 패널 지도 서비스 제공**  
   - AI로 발견한 태양광 패널을 지도에서 확인할 수 있습니다.  

### 3. **크라우드소싱을 통한 데이터 확보**  
   - 패널 찾기 게임을 통해 유저 데이터를 수집, AI의 정확도를 지속적으로 개선합니다.  

### 4. **사회적 문제로의 확산과 관심 증대**  
   - 유저 참여를 유도하여 지속적인 논의와 해결 방향을 제시합니다.  

---

## 설치 및 실행방법

### 실행 방법
1. **모바일에서 접속**  
   - QR 코드를 스캔하거나 [solar-see.site](https://solar-see.site)로 접속하세요.  
2. **소스 코드 클론**  
   ```bash
   git clone --recurse-submodules https://github.com/tech-for-impact/Solar-See_2024.git
   cd frontend && git pull && cd ../backend && git pull && cd ..
   ```
3. **설치**  
   - 각 레포지토리의 설치 가이드를 참고하세요.  

---

## Demo Video
[데모 영상 보기](#)

---

## 레퍼런스

### AI 개발 시 참고 자료
- [YOLO11 🚀 신규](https://docs.ultralytics.com/ko/models/yolo11/)  
- [Mask R-CNN (TensorFlow 2.14)](https://github.com/z-mahmud22/Mask-RCNN_TF2.14.0)  

### 항공 사진 및 학습 데이터 출처  
- **항공사진:** 국토지리정보원  
- **학습 데이터:** [AIHub 태양광 패널 데이터셋](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71348)  

### 관련 자료 
- [조선일보: 전력 수요 예측 문제](https://biz.chosun.com/policy/policy_sub/2023/08/14/3BSO4UXWRJB5LNNHYN6WCY3ODM/)  
- [뉴시스: 신재생에너지의 도전](https://www.newsis.com/view/NISX20240814_0002850758)  
- [경향신문: 비계량 태양광 문제](https://www.khan.co.kr/economy/industry-trade/article/202108042040015)  

### 발표 자료 및 펠로우 조직 사이트 
- **최종 발표 자료:** [Figma Deck](https://www.figma.com/deck/TuZtQY16UshgZwb02bLiwv)  
- **펠로우 조직:** [60Hz](https://60hz.io/)  

---

## 팀원 소개

| 이름 | 소속 | 이메일 | Github ID | 역할 |
|---------|------|--------|-----------|------|
| 이중권 | EE, KAIST | 2jungg@kaist.ac.kr | 2jungg | 지도 패널 정보, 게임 인트로, 게임 플레이 기능 |
| 김현수 | SoC, KAIST | skykhs3@kaist.ac.kr | skykhs3 | AI, YOLO11 기반 Image Segmentation 모델 학습,  RESTful API 설계, 데이터베이스 스키마 설계, DNS 설정, 항공사진 이미지 가공, Django RESTful API 서버 구현, Frontend 디자인 수정 및 버그 수정, Frontend CI/CD 구축, Frontend 배포, Backend 배포 |
| 박은비 | SoC, KAIST | kelly030813@kaist.ac.kr | qkrdmsql | 지도 설계, 게임 클레임, API 통신, UX 개선 |
| 유권우 | SoC, KAIST | rnjsdn1003@kaist.ac.kr | KingsFavor | - |
| 이혜리 | SoC, KAIST | harriet@kaist.ac.kr | hye-ilee | 항공사진 수집, 지도 이동, 게임 채점 및 랭킹, UX 개선 |
| 임채민 | SoC, KAIST | killerwhalee@kaist.ac.kr | [killerwhalee](https://github.com/killerwhalee) | AI, Mask-RCNN 기반 Image Segmentation 모델 학습, 학습 결과 데이터 수집 및 가공, 배포 환경 구축 및 설정, 서버 데이터 관리 |
| 표승화 | ID, KAIST | shpyo@kaist.ac.kr | hu9eswan | 로고 제작, 모바일 UI, UX Writing, 발표 자료 제작 |
