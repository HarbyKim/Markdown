# 제목(Header)
# 제목 1
## 제목 2
### 제목 3
#
<br />

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세

# 강조(Emaphasis)

_이텔릭_  
**볼드**   
**_이텔릭 + 볼드_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(list)

1. 순서가 필요한 목록
1. 순서가 필요한 목록<br/>
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크
<a href="http://google.com">구글</a>  
[구글](http://google.com)  
[네이버](http://google.com "Naver로 이동")

# 이미지
![HEROPY](https://heropy.blog/css/images/logo.png)


# 인용문(block Quote)
>남의 말이나 글에서 직접 또는 간접적으로 따온 문장.  
>(네이버 사전)

>인용문 작성
>>중첩 인용문 작성
>>>중첩 인용문 작성
>>>>중첩 인용문 작성

# 인라인(Inline) 코드 강조

css에서 `background` 혹은 `background-image`  
속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
# 블록(block) 코드 강조
```html
    <a href="http://google.com">구글</a>  
```

```css
    .list > li {
        position: absolute;
        top: 40px;
    }
```
```javascript
    function func() {
        let a  = 'AAA';
        return a;
    }
```

```bash
$ git commit -m 'Study Markdown'
```
```plaintext
개발용 목적이 아닌 텍스트 필드
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

# 표(Table)
position 속성  

값 | 의미 | 기본값
-- | :--: | --:
static | 기준 없음 | O
ralative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X