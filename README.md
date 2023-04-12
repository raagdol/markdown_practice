# 제목(Header)
'#" 1개부터 6개까지  
#의 개수가 작을수록 크기가 크다

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

React는 사용자 인터페이스를 구축하기 위해 선언적이고 효율적이며 유연한 Javascript 라이브러리입니다.
(React 공식문서)

# 줄바꿈(Line Breaks)
띄어쓰기 두번 or br태그

React는 사용자 인터페이스를 구축하기 위해 선언적이고 효율적이며 유연한 JavaScript 라이브러리입니다. <br />
"컴포넌트"라고 불리는 작고 고립된 코드의 파편을 이용하여 복잡한 UI를 구성하도록 돕습니다.
(React 공식문서)

# 강조(Emphasis)

이텔릭 _ _<br />
이텔릭 + 두껍게 **_ _** <br />
취소선 ~~ ~~ <br />
밑줄 <u> </u>


_이텔릭_ <br />
**두껍게** <br />
**_이텔릭 + 두껍게_** <br />
~~취소선~~ <br />
<u>밑줄</u>

# 목록(List)
번호를 하나만 사용하거나 순서대로 작성하지 않아도 1, 2, 3, ... 으로 표기됨

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)
마크다운은 a태그의 target속성은 제공하지 않음  
[]안에 이름 ()안에 주소

<a href="https://google.com">Google</a>

[Google]("https://google.com")

<a href="https://naver.com" title="NAVER로 이동">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동")

# 이미지(Images)


![React](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/200px-React-icon.svg.png)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장<br />
> (네이버 국어사전)

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">Google</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
React는 사용자 인터페이스를 구축하기 위해 선언적이고 효율적이며 유연한 Javascript 라이브러리입니다.
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|--
static | 기준 없음 | O
relative | 요소 자기자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

줄바꿈 br 태그  
밑줄 u 태그 or style="text-decoration: underline;  
target속성 _blank 필요한 경우 a태그를 직접 작성  
img 속성 width 필요한 경우 img태그에서 직접 작성

# 수평선(Horizontal Rule)

-, _, * 세번 작성