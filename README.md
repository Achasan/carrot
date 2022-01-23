# 🥕 당근찾기게임
- https://achasan.github.io/carrot
- 이전에 JavaScript를 통해서 만들었던 당근찾기게임을 올려놓은 Repository입니다.

## 게임방식
- 웹페이지를 들어가서 ▶ 재생버튼을 클릭하여 게임을 시작합니다.
- 벌레를 클릭하게되면 게임오버가 됩니다.
- 총 15개의 당근을 클릭하면 승리하게됩니다.

## Stack
- 해당 프로젝트는 HTML5, CSS3, JavaScript를 사용하여 만든 토이프로젝트입니다. 주요기능은 아래와 같습니다 :)
  - JavaScript를 통해 Element를 생성, CSS의 transform 속성을 사용하여 Element 랜덤 배치
    - top, left가 아닌 transform으로 Element를 옮긴 이유는 렌더링 과정을 피할 수 있어 성능을 향상시킬 수 있기 때문입니다.
  - setInterval() 함수를 사용하여 시간 카운트
  - 버블링(Bubbling) 개념을 활용하여 부모태그에 이벤트를 넣고, 클릭된 자식태그의 클래스이름에 따라 작동되는 함수가 다르도록 구현
