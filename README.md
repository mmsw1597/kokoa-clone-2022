# Kokoa Clone 2022 Update

CSS got so much better!

## 요점 (2022/08/17)

1. 클래스 이름은 중복이 안생기게 끔 특이하고 길게 할 것 (BEM).
2. 뼈대를 만들고 나중에 추가할 부분은 주석처리.
3. 아이콘은 heroicons 사이트나 font awesome 사이트에서 구하면 된다.
4. css 파일 단축기 => link:css
5. 색상 추출 프로그램 ColorZilla
6. :not(x) 를 통해 속성을 적용시키지 않을 수 도 있다. 뜻은 x를 제외한 나머지에 적용한다는 의미.

## 요점 (2022/08/18)

1. VS코드 명령어 단축키 (nav>ul>li\*4>a) nav안에 ul안에 li 4개, a하나.
2. Border Box : 고정된 너비 200px에 padding left 50px를 주면 css는 250px로 만들어버린다.
이때 Border Box를 적용하면 padding을 주더라도 너비 200px을 유지한다.

## 요점 (2022/08/19)

1. 모든 페이지의 공통된 컴포넌트나 여백 크기가 있다면 변수로 따로 설정하거나 body 속성에
그 속성을 명시하자.
2. 부가적인 변경사항 반영할때 무작정 클래스를 추가하지 말고 selector를 사용하자.(ex : last-child)
3. 부모의 flex 영향으로부터 벗어나려면 부모에 비어있는 div를 추가하면 된다.
