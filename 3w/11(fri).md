## 오늘의 회고 ヾ(•ω•`)o

### 효율적인 코드를 작성하기 위한 고민을 많이 해보기!

<br>

### 느낀 점 😃

어제 만족스럽게 짜놓은 유효성 판정 코드가 복잡하게 두번씩 쓰이는 기분이 들어 코드를 수정하였다. 여기서 테스트의 순기능이 발동했다. 테스트를 작성하면서 값을 넣고 검사를 할 때, 이렇게 하는게 더 효율적일 것 같다는 생각을 한다.

<br>

그리고 사실 오늘은 다른 일이 있어 static 처리를 알고 리팩토링을 거치고, 테스트 작성과 enum에 대한 고민을 하면서 마무리를 지을 거 같아 이어질 내용은 내일 더 자세히 적어보도록 하겠다..! 오늘은 그냥 열정 넘치는 나에게 박수...

### static 처리 💩

<br>
중복 관련 처리를 하는 valid 클래스는 변수가 없어 모두 static 처리를 해줘야 겠다는 생각이 들었다. static 메서드로 선언이 되면 굳이 생성자를 다른 클래스에서 만들어주지 않아도 값이 변경될 필요가 없기 때문에 언제 어디에서든지 불러올 수 있다!

<br>