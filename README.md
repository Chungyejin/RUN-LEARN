<h1>"게임처럼 즐기는 학습, Run & Learn"</h1>
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/554f0465-63d7-46d0-9320-ee9bfed84249" />


이 프로젝트는 여러 언어로 제공됩니다.
- [English](README.eng.md)
- [Português](README.pt.md)
- 
# 🩵 프로젝트 소개 및 개발 목적
 오늘날 많은 학생들은 학습 과정에서 **집중력 부족**과 **동기 저하**로 어려움을 겪고 있으며, 교육 자원에 접근하기 어려운 환경에 놓인 학생들의 **학습 격차**는 점차 심화되고 있습니다. 이러한 문제는 단순한 개인의 한계를 넘어 **교육 불평등**으로 이어지고 있습니다.  

**Run & Learn**은 이러한 문제를 해결하고자 **AI 기반 학습**과 **게임적 몰입 요소**를 결합하여 만든 **교육용 RPG 프로젝트** 로,
플레이어는 게임 속 NPC와 대화하면서 AI가 실시간으로 생성한 문제를 풀고, 게임을 즐기며 자연스럽게 학습할 수 있습니다.  

최종적으로, 본 프로젝트의 목표는 **교육 격차를 줄이고 모든 학생에게 공평한 학습 기회를 제공**하는 것입니다.

<br>
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/f303227f-81eb-4384-95c7-0f915b602927" />



# 🩵 개발 환경 및 아키텍쳐
<img width="500" height="360" alt="image" src="https://github.com/user-attachments/assets/99379032-b2d2-479e-aadb-c40a1f24ff0f" />
<img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/3cf7bdb2-808b-4a0e-874e-199fbfd69901" />
<img width="800" height="450"alt="image" src="https://github.com/user-attachments/assets/9c55f59f-92c0-460d-ba19-9e0d30eb04b8" />



# 🩵 주요 기능
<h3> 1. AI 문제 생성</h3>
   
   **OpenAI API**를 활용하여 NPC가 실시간으로 학습 문제를 출제합니다. 단순히 저장된 문제를 불러오는 방식이 아니라,
   흐름에 맞게 새로운 문제를 자동으로 생성할 수 있습니다.이를 통해 같은 상황에서도 항상 새로운 문제를 접할 수 있어, 
   반복 학습의 지루함을 줄이고 몰입도를 높입니다.
   <br>
   
   <img width="400" height="450"  alt="image" src="https://github.com/user-attachments/assets/dce52c45-a24f-48aa-a8a9-6bbdc237996e" />
   <img width="400" height="450" alt="image" src="https://github.com/user-attachments/assets/ae5babd0-3da7-41b6-9c21-d825bc76b1db" />

<h3> 2. 게임형 학습</h3>
   문제 풀이는 단순한 퀴즈 풀이가 아니라 퀘스트 진행 과정과 연결됩니다. 예를 들어 NPC가 “이 문제를 풀면 열쇠를 얻을 수 있어!”라는 식으로 문제를 제시하고, 
   정답을 맞히면 보상이나 진행 이벤트가 발생합니다. 이를 통해 학습 과정이 게임 진행의 일부가 되어, 자연스럽게 동기부여와 재미를 제공합니다.
   <br>
   <img width="400" height="450" alt="image" src="https://github.com/user-attachments/assets/7956b295-2f91-4c3d-8e3b-8f6009998e1a" />
   <img width="400" height="450" alt="image" src="https://github.com/user-attachments/assets/ec61500b-7e10-4e74-97fa-ecf19cfb756c" />


<h3> 3. 단원별 학습 관리</h3>
   1단원, 2단원 등 교과 단원에 맞춰 주제를 구분하여 문제를 관리할 수 있습니다.
   이를 통해 학습을 단계별로 효과적으로 할 수 있습니다.
   
<h3> 4. 랜덤 문제 제공</h3>
     같은 단원 내에서도 항상 같은 문제가 나오는 것이 아니라, 매번 다른 문제가 무작위로 생성됩니다. 그 덕분에 반복 학습 시에도 지루하지 않고,
     다양한 문제 유형을 접할 수 있어 학생들의 문제 해결 능력과 응용력을 강화합니다.
<br>
   <img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/3c70413a-648a-4d55-8593-c466fdf7831f" />

# 🩵 기대효과 및 활용분야

현재는 테스트용으로 중학교 1학년 수학 문제만 적용되었지만, 향후 다양한 과목과 여러 학년으로 확장할 계획이며,
학습 기록 분석을 통해 **난이도 조정**과 **학습 성취**도 추적 기능도 추가될 예정입니다. 학생들은 맞춤형 문제를 게임 환경에서 풀면서 몰입 학습을 경험하고, 
자기주도적 학습 습관, 집중력 향상, 학습 동기 강화와 같은 효과를 얻을 수 있습니다. 이러한 효과들은 교육 격차를 줄이고 공평한 학습 기회를 제공하는 데 활용될 수 있습니다.

또한 본 시스템은 학교와 학원에서 **개별 학생 맞춤형 학습 도구**로 활용할 수 있으며, 공교육과 사교육에서 학생 수준에 맞는 학습 자료 제공과 학습 성취도 관리에 도움을 
줄 수 있습니다. 더 나아가, 교육 관련 연구 기관이나 학습 데이터 분석 분야에서도 학습 패턴과 난이도 조정을 위한 **데이터 수집 및 분석 도구**로 활용될 수 있습니다.
<br>
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/adbb74f1-94ed-4d2d-98a6-8be36f0ae157" />

<h3>팀원 👥</h3>

| Name        | Role           |
|------------|----------------|
| 정예진 | Server Developer |
| 신예찬 | AI Developer |
| 황백준 | Server Developer |
| 배현아 | Product Designer | 

