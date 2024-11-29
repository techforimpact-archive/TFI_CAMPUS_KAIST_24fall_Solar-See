
# Solar-See 2024

## 개요 📝
**Solar-See**는 비계량 태양광 패널을 발견하고, 이를 통해 전력 수요 예측의 정확도를 높이기 위해 개발된 AI 기반 게임 및 지도 서비스입니다.  
- **🗺️ 비계량 태양광 패널 지도**  
- **🎮 태양광 패널 찾기 게임**  
  *유저의 게임 데이터를 기반으로 AI가 놓친 태양광 패널을 추가적으로 발견합니다.*  

---

## 솔루션 한줄 요약 🌞
- AI의 패널 탐지 능력 개선을 위한 **태양광 패널 찾기 게임** 

---

## 풀고자 하는 사회 문제 정의 🖋️

1. 🌍 **신재생에너지는 필수적인 에너지원입니다.**  
   - 지속가능한 발전과 환경오염 감소를 위해 필요합니다.  

2. ⚡ **전력 수요 예측 실패로 신재생 에너지 발전소가 가동 중단되는 문제가 있습니다.** 
   - 화력 및 원자력 발전소는 가동 중단이 어려워 신재생에너지가 주로 희생됩니다.  

3. 🌤️ **비계량 태양광 패널은 전력 수요 예측을 어렵게 만듭니다.** 
   - 계측되지 않은 태양광 발전량은 전력 피크 시간대의 11%를 차지합니다.  

4. 💡 **Solar-See는 비계량 태양광 패널을 발견해 문제를 해결합니다.** 
   - 전국의 모든 비계량 패널을 찾고, 전력 수요 예측의 정확도를 높여 신재생 에너지의 확산을 돕습니다.  

---

## 솔루션 개요 ⚡

### 1. **📷 항공사진과 AI를 활용한 태양광 패널 탐색**  
   - 기존 위성사진보다 화질이 좋은 항공사진을 사용하여 AI를 학습시킵니다.  

### 2. **🗺️ 비계량 태양광 패널 지도 서비스 제공**  
   - AI로 발견한 태양광 패널을 지도에서 확인할 수 있습니다.  

### 3. **🤝 크라우드소싱을 통한 데이터 확보**  
   - 패널 찾기 게임을 통해 유저 데이터를 수집, AI의 정확도를 지속적으로 개선합니다.  

### 4. **🌐 사회적 문제로의 확산과 관심 증대**  
   - 유저 참여를 유도하여 지속적인 논의와 해결 방향을 제시합니다.  

---

## 설치 및 실행방법 🚀

### 실행 방법
1. **📱 모바일에서 접속**  
   - QR 코드를 스캔하거나 [solar-see.site](https://solar-see.site)로 접속하세요.  
   ![QR Code](https://github.com/user-attachments/assets/5f1a69bf-6aa5-48fe-ace0-e10757c47aea)  

2. **💻 소스 코드 클론 후 로컬에서 실행**  
   ```bash
   git clone --recurse-submodules https://github.com/tech-for-impact/Solar-See_2024.git
   cd frontend && git pull && cd ../backend && git pull && cd ..
   ```
  - 각 레포지토리의 설치 가이드를 참고하세요.  

---

## Demo Video 🎥  
[데모 영상 보기](https://github.com/tech-for-impact/Solar-See_2024/raw/refs/heads/main/demo/solar-see-demo-video.mp4)

---

## 레퍼런스 📚  

### AI 개발 시 참고 자료  
- [YOLO11 🚀 신규](https://docs.ultralytics.com/ko/models/yolo11/)  
- [Mask R-CNN (TensorFlow 2.14)](https://github.com/z-mahmud22/Mask-RCNN_TF2.14.0)  

### 항공 사진 및 학습 데이터 출처  
- **📸 항공사진:** 국토지리정보원  
- **🗂️ 학습 데이터:** [AIHub 태양광 패널 데이터셋](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71348)  

### 관련 자료  
- [📰 조선일보: 전력 수요 예측 문제](https://biz.chosun.com/policy/policy_sub/2023/08/14/3BSO4UXWRJB5LNNHYN6WCY3ODM/)  
- [📰 뉴시스: 신재생에너지의 도전](https://www.newsis.com/view/NISX20240814_0002850758)  
- [📰 경향신문: 비계량 태양광 문제](https://www.khan.co.kr/economy/industry-trade/article/202108042040015)  

### 발표 자료 및 펠로우 조직 사이트  
- **📊 최종 발표 자료:** [Figma Deck](https://www.figma.com/deck/TuZtQY16UshgZwb02bLiwv)  
- **🧑‍🤝‍🧑 펠로우 조직:** [60Hz](https://60hz.io/)  

---

## 팀원 소개 👥  

| 이름       | 소속       | 이메일                | Github ID                         | 역할                     |  
|------------|------------|-----------------------|-----------------------------------|--------------------------|  
| 이중권      | EE, KAIST  | 2jungg@kaist.ac.kr   | [2jungg](https://github.com/2jungg) | 프론트엔드 개발          |  
| 김현수      | SoC, KAIST | skykhs3@kaist.ac.kr  | [skykhs3](https://github.com/skykhs3) | 프론트엔드, 백엔드 개발  |  
| 박은비      | SoC, KAIST | kelly030813@kaist.ac.kr | [qkrdmsql](https://github.com/qkrdmsql) | 프론트엔드 개발          |  
| 유권우      | SoC, KAIST | rnjsdn1003@kaist.ac.kr | [KingsFavor](https://github.com/KingsFavor) | 좌표변환기 개발          |  
| 이혜리      | SoC, KAIST | harriet@kaist.ac.kr  | [hye-ilee](https://github.com/hye-ilee) | 프론트엔드 개발          |  
| 임채민      | SoC, KAIST | killerwhalee@kaist.ac.kr | [killerwhalee](https://github.com/killerwhalee) | 백엔드 개발              |  
| 표승화      | ID, KAIST  | shpyo@kaist.ac.kr    | [hu9eswan](https://github.com/hu9eswan) | UI/UX Writing, 발표 자료 제작 |  

<br>

---

# Solar-See 2024 (ENGLISH)

## Overview 📝
**Solar-See** is an AI-based game and mapping service developed to identify non-metered solar panels and improve the accuracy of power demand forecasting.  
- **🗺️ Non-Metered Solar Panel Map**  
- **🎮 Solar Panel Discovery Game**  
  *AI uses user game data to find additional solar panels it may have missed.*  

---

## One-Line Solution Summary 🌞
- **Solar Panel Discovery Game** to enhance AI's panel detection capability.

---

## Definition of Social Problems to Solve 🖋️

1. 🌍 **Renewable energy is an essential energy source.**  
   - It is necessary for sustainable development and reducing environmental pollution.  

2. ⚡ **Power demand forecasting failures cause renewable energy plants to shut down.**  
   - Fossil fuel and nuclear power plants are difficult to shut down, leading to renewable energy being sacrificed.  

3. 🌤️ **Non-metered solar panels make power demand forecasting challenging.**  
   - Non-metered solar generation accounts for 11% of peak power usage.  

4. 💡 **Solar-See solves this issue by identifying non-metered solar panels.**  
   - It aims to find all non-metered panels nationwide, enhancing power demand forecasting accuracy and supporting renewable energy expansion.  

---

## Solution Overview ⚡

### 1. **📷 Solar Panel Detection Using Aerial Photos and AI**  
   - Train AI with high-quality aerial photos instead of conventional satellite images.  

### 2. **🗺️ Non-Metered Solar Panel Mapping Service**  
   - Display solar panels detected by AI on a map.  

### 3. **🤝 Crowdsourced Data Collection**  
   - Collect user data through the discovery game to continuously improve AI accuracy.  

### 4. **🌐 Expanding Awareness of Social Issues**  
   - Engage users to generate ongoing discussions and propose solutions.  

---

## Installation and Execution 🚀

### How to Run
1. **📱 Access via Mobile**  
   - Scan the QR code or visit [solar-see.site](https://solar-see.site).  
   ![QR Code](https://github.com/user-attachments/assets/5f1a69bf-6aa5-48fe-ace0-e10757c47aea)  

2. **💻 Clone the Source Code and Run Locally**  
   ```bash
   git clone --recurse-submodules https://github.com/tech-for-impact/Solar-See_2024.git
   cd frontend && git pull && cd ../backend && git pull && cd ..
   ```
  - Refer to the installation guides in each repository.  

---

## Demo Video 🎥  
[Watch the Demo Video](https://github.com/tech-for-impact/Solar-See_2024/raw/refs/heads/main/demo/solar-see-demo-video.mp4)

---

## References 📚  

### AI Development Resources  
- [YOLO11 🚀 Official](https://docs.ultralytics.com/models/yolo11/)  
- [Mask R-CNN (TensorFlow 2.14)](https://github.com/z-mahmud22/Mask-RCNN_TF2.14.0)  

### Aerial Photos and Training Data Sources  
- **📸 Aerial Photos:** National Geographic Information Institute  
- **🗂️ Training Data:** [AIHub Solar Panel Dataset](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71348)  

### Related Articles  
- [📰 Chosun Ilbo: Challenges in Power Demand Forecasting](https://biz.chosun.com/policy/policy_sub/2023/08/14/3BSO4UXWRJB5LNNHYN6WCY3ODM/)  
- [📰 Newsis: The Challenge of Renewable Energy](https://www.newsis.com/view/NISX20240814_0002850758)  
- [📰 Kyunghyang Shinmun: The Non-Metered Solar Panel Problem](https://www.khan.co.kr/economy/industry-trade/article/202108042040015)  

### Presentation Materials and Partner Organization  
- **📊 Final Presentation Deck:** [Figma Deck](https://www.figma.com/deck/TuZtQY16UshgZwb02bLiwv)  
- **🧑‍🤝‍🧑 Partner Organization:** [60Hz](https://60hz.io/)  

---

## Team Members 👥  

| Name       | Affiliation  | Email                 | Github ID                          | Role                      |  
|------------|--------------|-----------------------|------------------------------------|---------------------------|  
| Junggwon Lee  | EE, KAIST    | 2jungg@kaist.ac.kr    | [2jungg](https://github.com/2jungg)  | Frontend Developer         |  
| Hyeonsu Kim  | SoC, KAIST   | skykhs3@kaist.ac.kr   | [skykhs3](https://github.com/skykhs3) | Frontend, Backend Developer |  
| Eunbi Park   | SoC, KAIST   | kelly030813@kaist.ac.kr | [qkrdmsql](https://github.com/qkrdmsql) | Frontend Developer         |  
| Gwonwoo Yu   | SoC, KAIST   | rnjsdn1003@kaist.ac.kr | [KingsFavor](https://github.com/KingsFavor) | Coordinate Converter Developer |  
| Hyeri Lee    | SoC, KAIST   | harriet@kaist.ac.kr   | [hye-ilee](https://github.com/hye-ilee) | Frontend Developer         |  
| Chaemin Lim  | SoC, KAIST   | killerwhalee@kaist.ac.kr | [killerwhalee](https://github.com/killerwhalee) | Backend Developer          |  
| Seunghwa Pyo | ID, KAIST    | shpyo@kaist.ac.kr     | [hu9eswan](https://github.com/hu9eswan) | UI/UX Writing, Presentation Design |  
