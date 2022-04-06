# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
<!-- 띄워쓰기 두번하거나 <br/>를 쓰면됨 -->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>  
대한 사람 대한으로 길이 보전하세  

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
 <u>밑줄</u> <!--u태그는 마크다운에서만 사용 -->


# 목록(List)
<!-- 숫자가 자동으로 1. 2. 3.으로 변경됨 html에서 <ol> 태그와 같음 -->
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록  <!-- 들여쓰기를 2번하고 작성하면 됨 -->
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
<!-- 맨 위에 a태그를 마크다운으로 작성하면 이렇게 간결해짐 -->
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://google.com "NAVER로 이동!")
<!-- 마우스 올렸을때 출력되는 title 메시지도 간결하게 작성 가능함 -->
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>
<!-- _black로 새 탭으로 열때는 위와 같이 a태그를 써야함 -->

# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)
<!-- 링크와 이미지의 차이는 맨 앞에 ! 느낌표를 넣는지 않는지 차이 -->

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)
<!-- 이미지를 클릭하면 링크로 이동됨 -->

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3

# 인라인(inline) 코드 강조
<!-- 키보드 1번 옆에 백틱 ` 기호로 묶어주면 강조효과가 생김 -->
CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블럭(block) 코드 강조
<!-- 처음과 끝에 백틱 기호 3번씩 넣고 중간에 html적고 html 코드를 넣으면 내가 작성한 코드가 하이라이트 되어 보여지게 됨 (css,js도 동일)  -->
```html 
<a href="https://www.google.co.kr" target="_blank">GOOGLE</a>
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
<!-- 터미널 코드도 화면에 보여지게 가능함 -->
```bash
$ git commit -m 'Study Markdown'
```

<!-- 일반 텍스트도 강조 해줄 수 있음 -->
```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값<!-- 아래 선은 머리와 몸통을 구분하기 위함 (글씨 굵기) -->
--|:--:|--:     
static | 기준-없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
<!-- :--:은 가운데 정렬 --:는 오른쪽 정렬임 -->

# 원시 HTML(Raw HTML)
<!-- 마크다운은 HTML로 변환되기 때문에 HTML 문법을 그대로 사용할 수도 있음 -->
동해물과 <u>백두산</u>이 마르고 닳도록<br />
하느님이 <span style="text-decoration: underline;">보우하사</span> 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___