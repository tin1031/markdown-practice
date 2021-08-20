# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 샵 갯수가 많을 수록 작아진다 = h1~h6

# 문장(Paragraph)

동해물과 백두산이 어쩌구
애국가 일부분 내용

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

##### 띄어쓰기 두 번이나 br/ 태그로 줄바꿈 처리

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

#### 밑줄은 제공하지 않으므로 u로 함 => html에선 안됨

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한
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

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://google.com" title="네이버로 이동">NAVER</a>

[NAVER](https://naver.com "네이버로 이동")

# 이미지(Image)

![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

#### 이미지로 이동

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문 작성
>
> > 중첩 인용
> >
> > > 중중첩된 인용1
> > > 중중첩된 인용2
> > > 중중첩된 인용3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = "AAA";
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 어쩌구 저쩌구
```

# 표(Table)

position 속성

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration:underline">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

# 수평선(Horizontal Rule)

---

---

---
