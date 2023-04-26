# web_using_chatgpt
[스파르타코딩클럽](https://spartacodingclub.kr/) 무료 강의 - [ChatGPT로 10분만에 웹사이트 만들기]를 들으면서 기록한 리포지토리 입니다.
***
+ 개발환경
    - Windows 10
    - Visual Studio Code
***
### 📌 코드 정렬법
- Ctrl + K + F 를 사용하면 코드 들여쓰기가 된다.
<br/><br/>

### 📌 부트스트랩(Bootstrap)
- 오픈소스 CSS 프레임워크
- 웹 페이지를 쉽고 빠르게 만들 수 있도록 도와준다.
- 반응형 웹 디자인을 지원
<br/><br/>

### 📌 HTML의 class 속성을 사용하여 CSS 스타일 적용하기
- class 속성은 동일한 스타일이나 기능을 가진 HTML 요소들을 그룹화하여 하나의 이름으로 묶어 관리할 수 있게 해준다.
- CSS에서 해당 class를 선택자로 사용하여 그룹화한 HTML 요소에 대해서 일괄적인 스타일 적용을 할 수 있다.
- CSS에서는 `.클래스명` 형식으로 클래스를 선택자로 사용한다.
- 예시
```HTML
<div class="container">
  <h1 class="title">Hello, World!</h1>
  <p class="description">This is a paragraph.</p>
  <button class="btn btn-primary">Click me!</button>
</div>
```
```CSS
.title {
  font-size: 2em;
  color: red;
}

```
<br/><br/>

### 📌 Github을 사용해서 웹 호스팅하기
- Github로 **정적** 웹사이트 호스팅이 가능하다.
- 호스팅하고자 하는 리포지토리 하위에 `index.html`이 꼭! 존재해야 한다.
- `Settings > Pages`에 들어가서 Branch를 None에서 main으로 변경해준다.
- 잠시 기다리면 상단에 웹 사이트 링크가 생성된다.
<br/><br/>