---
title: "To Do List App with Vue"
categories: [Vue, Project]
---

### Vue를 이용한 To Do List App 만들기- 1. 프로젝트 설계

---

간단한 todolist를 제작하며 Vue 프레임워크에 대한 학습을 진행한다.

1. 구성 및 환경

   - 기능 : 내용 입력 / 완료 여부 / 순서 이동
   - Vue
   - node
   - npm, yarn
   - SPA(Single Page App)
   - Unit Test
   - Cloud 환경에 배포

2. 스케치(구상)
   <img src="https://gyofeel.github.io/assets/images/To_Do_List_App_with_Vue/01.jpeg"/>
   <br>
   <img src="https://gyofeel.github.io/assets/images/To_Do_List_App_with_Vue/02.jpeg"/>
   <br>
3. 컴포넌트 구성
4. 간단한 UX/UI 설계
   - Drag&Drop? 간단하게 적용할 수 있는 방법이 있다면 ... (구현 기간이 짧기 때문), 영역 간 아이템의 이동을 위하여
   - Drag&Drop이 어렵다고 판단 되면 이동을 위한 버튼 설계(화살표를 가진 버튼 등)
   - key event : input 태그를 이용해 To Do를 입력할 때, Enter 키 이용.
   - mouse event : 완료 체크/취소를 제어하는 부분에 적용.
