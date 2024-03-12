# CSS 구조와 필수 예제

  

CSS는 Cascading Style Sheets의 약자로, 웹 페이지의 스타일을 정의하기 위해 사용되는 언어입니다. 기본적인 CSS 구조는 선택자(selector)와 선언블록(declaration block)으로 구성됩니다. 선택자는 스타일을 적용하고자 하는 HTML 요소를 지정하고, 선언블록은 중괄호 `{}` 안에 속성(property)과 그 값(value)으로 구성되어 있습니다.

  

<br>

  

## 기본 CSS 구조

```css

선택자 {

속성: 값;

속성: 값;

}

```

  

<br>

  

## 필수 CSS 예제 5가지

  

1. **텍스트 색 변경하기**

```css

p {

color: blue;

}

```

이 CSS 코드는 모든 `<p>` 태그에 있는 텍스트의 색상을 파란색으로 변경합니다.

  

<br>

  

2. **배경색 설정하기**

```css

body {

background-color: #f0f0f0;

}

```

`body` 태그의 배경색을 회색으로 설정합니다.

  

<br>

  

3. **폰트 크기 조정하기**

```css

h1 {

font-size: 24px;

}

```

`<h1>` 태그의 폰트 크기를 24픽셀로 설정합니다.

  

<br>

  

4. **마진 설정하기**

```css

.container {

margin: 20px;

}

```

`.container` 클래스를 가진 요소의 모든 면에 대해 20픽셀의 마진을 적용합니다.

  

<br>

  

5. **호버 효과 추가하기**

```css

button:hover {

background-color: green;

}

```

버튼 위에 마우스를 올리면 배경색이 초록색으로 변경됩니다.