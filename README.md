# Healthy Mento

`Skils`: torch, python, ubuntu20.04LTS , git-hub, notion

`model`: MediaPipe, Motion Transfer, Yolo v8 small

<hr>
<br>

### <b>AI를 기반으로 진행하는 LWBG 팀의 헬스케어 서비스 'Heathly Mento' 프로젝트</b>

<br><br>

## 1.Collaborator
- 팀장 : 김동신(주제선정, 기획 및 설계, Motion Transfer, Media Pipe, Chat GPT, PPT)
- 팀원 : 유호선(주제선정, 기획 및 설계, Yolo v8, Chat GPT)

<br><br>

## 2. Tech
- Front-End
<br><br>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white">
  
- Back-End
<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white">&nbsp;
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white">&nbsp;
  <img src="https://img.shields.io/badge/Mysql-4479A1?style=flat-square&logo=Mysql&logoColor=white">&nbsp;

  <br>

  - Edit Tool
  <br><br>
      <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/Mysql Workbench-4479A1?style=flat-square&logo=Mysql&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/Jupyter Notebook-F37626?style=flat-square&logo=Jupyter&logoColor=white">&nbsp;

     <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white">

<br><br>

## 3. Project Management (22.11.03 ~ 22.12.14)
### 프로젝트 개발 방식
  - #### `Front-End`

    `Figma`를 활용하여 UI/UX 설계
    <br>
  - #### `Back-End`

    `FastAPI`를 통한 서버 통신, `MySQL`로 데이터베이스 설계.
    <br>
  - #### `AI Model`

    `Python`의 `MediaPipe`와`Motion Transfer` 메인으로 사용자에게 운동에 대해 가이드를 제시하고,
    `Yolo v8`을 이용하여, 음식을 분류하여, 칼로리와 가지고 있는 음식을 기반으로 Chat GPT로 하루 식단을 가이드
    
    <br>

## 4. 프로젝트 상세 내용
<div align='center'>
  
  |목차 & 기획 의도|
  |---|
  |![image](https://github.com/KimDong-gue/Second_Team_Project/assets/116249934/0a5f30ca-b9bf-484c-90fd-d438b6b5f842)|
  <br>
  
  |사용한 Tech & AI Model|
  |---|
  |`Media Pipe`, `Motion Transfer`, `Yolo v8 Small`, `Chat GPT`|
  <br>
  
  |Gantt Chart & Flow Chart|
  |---|
  |![image](https://github.com/KimDong-gue/Healthy-Mento/assets/116249934/698326d3-6137-4ad4-8e9e-c14a547e4cae)|
  |![image](https://github.com/KimDong-gue/Healthy-Mento/assets/116249934/449f5882-8d72-43cd-8855-6cf162d26e3c)|

  <br>
  
  | 운동 자세 검출 예시 |
  |---|
  |![image](https://github.com/KimDong-gue/Healthy-Mento/assets/116249934/af7ee6cd-10dc-4dad-b883-f98c51f3c84e)|

  | 음식 추천 예시 |
  |---|
  |![image](https://github.com/KimDong-gue/Healthy-Mento/assets/116249934/887fb075-0f5e-4018-8d86-6f9d28d1a6a4)|

  | 운동 예시 |
  |---|
  |![12321](https://github.com/KimDong-gue/Healthy-Mento/assets/116249934/2a066c26-2d16-4926-bf8a-544f93a2842a)|

  <br>
  
  |시행 착오 / 개선 사항|
  |---|
  |<div align='center'>시행 착오</div>|
  |![image](https://github.com/KimDong-gue/Healthy-Mento/assets/116249934/8abcb693-79d5-466c-b2c4-b9c6624c5c8a)|
  
  - Yolo v8 Small 모델링시, Data InBalance 문제 때문에, 데이터 증강을 수행 후, 어느정도의 InBalance를 해결하였습니다.  
  - MediaPipe로 운동 자세를 검출할 때, 초기에 발생한 다양한 어려움들을 극복하기 위해 끊임없는 실험과 수정 작업이 필요했습니다. 이러한 경험을 통해 데이터 다양성, 후처리 기술의 활용, 적절한 임계값 설정, 모델의 업데이트에 대한 중요성을 깨달았습니다. 이러한 
   과정을 통해 프로젝트를 성공적으로 완료할 수 있었습니다. 
  - Motion Transfer 모델링시, 프로젝트를 시작할 때, 동영상을 변경하지 않고 데모버전을 만들기로 결정했습니다. 이는 초기에 프로토타입을 빠르게 구현하고 사용자에게 시각적으로 효과를 보여주는 것이 목표였습니다. 그 후, Fine-Tuning해서 Motion Transfer하려고
    하였으나, Reference를 보는 통찰력이 부족해, 구현하는데는 어려움이 있었습니다. 향후에 Reference를 참고해서 완료할 예정입니다. 
  
  |<div align='center'>참고 문헌<div>|
  |(https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch)https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch
  (https://github.com/AliaksandrSiarohin/first-order-model)
  (https://github.com/svip-lab/impersonator)
  (https://github.com/Wangt-CN/DisCo?tab=readme-ov-file)|
  <br>
  
</div>

