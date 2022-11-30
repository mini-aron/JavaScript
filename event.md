javascript event

### 마우스 이벤트
+ click 요소에 마우스를 클릭했을 때 이벤트가 발생
+ dbclick 요소에 마우스를 더블클릭했을 때 이벤트가 발생
+ mouseout 요소에 마우스를 오버했을 때 이벤트가 발생
+ mouseout 요소에 마우스를 아웃했을 때 이벤트가 발생
+ mousedown 요소에 마우스를 눌렀을 때 이벤트가 발생
+ mouseup 요소에 마우스를 떼었을 때 이벤트가 발생
+ mousemove 요소에 마우스를 움직였을 때 이벤트가 발생
+ contextmenu context menu(마우스 오른쪽 버튼을 눌렀을 때 나오는 메뉴)가 나오기전에 이벤트 발생

### 키 이벤트

+ keydown 키를 눌렀을 때 이벤트가 발생
+ keyup 키를 떼었을 때 이벤트가 발생
+ keypress 키를 누른상태에서 이벤트가 발생

### 폼 이벤트
+ focus 요소에 포커스가 이동되었을 때 이벤트 발생
+ blur 요소에 포커스가 벗어났을 때 이벤트 발생
+ change 요소에 값이 변경 되었을 때 이벤트 발생
+ submit submit 버튼을 눌렀을 때 이벤트 발생
+ reset reset 버튼을 눌렀을 때 이벤트 발생
+ select  input이나 textarea 요소 안의 텍스트를 드래그하여 선택했을 때 이벤트 발생

### 로드 및 기타 이벤트
+ load 페이지의 로딩이 완료되었을 때 이벤트 발생
+ abort 이미지의 로딩이 중단되었을 때 이벤트 발생
+ unload 페이지가 다른 곳으로 이동될 때 이벤트 발생
+ resize 요소에 사이즈가 변경되었을 때 이벤트 발생
+ scroll 스크롤바를 움직였을 때 이벤트 발생

### 인라인 방식
```<태그명 on이벤트 = 자바스크립트 코드> </태그명> ```

```
<div onclick="view()"`>클릭</div>

<script>
  function view() {
     aleat("클릭했습니다.");
    }
  </script>

```







