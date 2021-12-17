# capstone-design2
:key: Subject
---
게임형 동작 인식 스마트 홈 트레이닝 시스템

:raising_hand: Members
---
* **2018102178 컴퓨터공학과 김유현**
<br>팀장, Teachable Machine + 웹캠 연동한 동작 인식 연구 및 구현, 멀티플레이 게임 구현, 게임 UI 매핑 및 연동
* **2018102230 컴퓨터공학과 정은서** 
<br>키넥트 동작 인식 연구 및 구현, 애니메이션 제작(캐릭터 안무 동작, 각종 이펙트 등), 게임 UI 제작, 사용자 평가

:bulb: Motivation & Goal
---
헬스장에서 일어난 집단 감염으로 인해, 여러 사람들과 함께 운동하는 GX 프로그램을 이용하기 어려워졌다. 본사람들은 가정에서 홀로 운동을 해야 하는 상황으로, 흥미를 잃을 수 있고 이에 꾸준히 운동을 지속하지 못하는 경우가 많다.<br>
따라서, 본 프로젝트에서 제안하는 홈 트레이닝 시스템은<br>
:one: 리듬 댄스 게임과 스피닝 운동을 결합, 단기적이고 직관적인 보상 제공으로 사용자의 흥미 유발 <br>
:two: 멀티 플레이 게임으로 지인들과의 경쟁심리를 유발해 운동량을 향상 <br>
3️⃣ 모션 인식 기술을 접목하여 사용자의 운동 정확도를 체크하여 보다 효율적인 운동 환경을 제공<br>

을 최종 목표로 하여 사용자들의 홈 트레이닝 낮은 지속률을 개선하고자 한다.

:computer: System Architecture
---
![system_architecture](https://user-images.githubusercontent.com/37354574/146490587-37bafcb9-f215-49ae-8842-c9bad477c07e.png)
:one: 사용자 카메라 설치 후 실내 자전거 위 동작 수행 <br>
:two: 카메라가 사용자를 트래킹 하여 Body 동작 데이터 전송 <br>
:three: 데이터 분석 후 Unity 내의 캐릭터의 동작과 얼마나 일치하는지 스코어링 <br>
:four: 게임이 종료되면 이에 따른 보상(올라간 체력 게이지, 더 젊어진 캐릭터, 새로운 노래) 제공 <br>


:page_facing_up: Documents
---
* [기초조사서](https://github.com/youhyeoneee/capstone-design2/tree/main/docu/%EA%B8%B0%EC%B4%88%EC%A1%B0%EC%82%AC%EC%84%9C)
* [면담보고서](https://github.com/youhyeoneee/capstone-design2/tree/main/docu/%EB%A9%B4%EB%8B%B4%ED%99%95%EC%9D%B8%EC%84%9C)
* [중간보고서](https://github.com/youhyeoneee/capstone-design2/tree/main/docu/%EC%A4%91%EA%B0%84%EB%B3%B4%EA%B3%A0%EC%84%9C)
* [최종보고서](https://github.com/youhyeoneee/capstone-design2/tree/main/docu/%EC%B5%9C%EC%A2%85%EB%B3%B4%EA%B3%A0%EC%84%9C)

📸 Demo
---
![웹캠](https://user-images.githubusercontent.com/37354574/146492611-c91e6ec5-a27f-494a-8360-b3432da97af8.gif)
![키넥트](https://user-images.githubusercontent.com/37354574/146492382-f37cac79-34b0-4fda-afd3-b0c4b273ecb5.gif)
<img src="https://user-images.githubusercontent.com/37354574/146493636-8309031a-5570-4b41-8e5b-d85c3a9c5031.jpg" width="600" height="400"/>
<img src="https://user-images.githubusercontent.com/37354574/146493676-4a068544-76cf-4ab5-ae53-a0206ca575c0.jpg" width="600" height="400"/>
![키넥트](https://user-images.githubusercontent.com/37354574/146492030-7720e4e6-7d10-4f0e-a674-0e4534042ba4.gif)
![웹캠](https://user-images.githubusercontent.com/37354574/146492095-55771ee9-61a8-4463-a591-ce5675dffe80.gif)
<img src="https://user-images.githubusercontent.com/37354574/146494163-f0222908-ada7-4b46-8199-1399d841dca5.jpg" width="600" height="400"/>
<img src="https://user-images.githubusercontent.com/37354574/146494167-dbfd96c2-d8ec-4b3b-b1f7-45b297e7f2ee.jpg" width="600" height="400"/>
<img src="https://user-images.githubusercontent.com/37354574/146494172-084e3777-b096-4e98-b0f4-8150d787ece7.png" width="600" height="400"/>
