# leejounga.github.io

#TODO

<!-- 체크박스 [ ]:빈 박스, [x]:체크된 박스 -->
- [x] Study Markdown
- [ ] make `index.html`

## Markdown 사용법

```html
<h1>heading 1</h1>
<h2>heading 2</h2>
<h3>heading 3</h3>
<h4>heading 4</h4>
<h5>heading 5</h5>
<h6>heading 6</h6>
```
# Markdown H1
## Markdown H2
### Markdown H3
#### Markdown H4
##### Markdown H5
###### Markdown H6

###목록

```html
<!-- 비순차 목록 -->
<!-- ul>li{item$}*3 -->
<ul>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ul>
<!-- 순차 목록 -->
<!-- ol>li{item$}*3 -->
<ol>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ol>
```

### 비순차 목록

- item1
- item2
- item3

### 순차 목록

1. item1
1. item2
1. item3

### 이미지
```html
<img src="http://i.imgur.com/PLHppZB.jpg" alt="가오나시">
```
<!-- 1080/2+[Emmet Math:Ctrl+Shift+Y] -->
<img src="http://i.imgur.com/PLHppZB.jpg" alt="가오나시" width="540" height="960">

<!-- 마크다운 문법: 마크다운 문법은 이미지 사이즈 조절이 안 -->
<!-- ![가오나시] (http://i.imgur.com/PLHppZB.jpg) -->

<!-- 마크다운 문법: 로컬 파일에 있는 이미지 삽입 -->
![gaonasy](Assets/gaonasy.jpg "gaonasy")

### 하이퍼링크
```html
<a href="http://iropke.com/">이롭게 에이전시</a>
```

- [디자이너에게 영감을 주는 사이트](http://iropke.com/blog/archives/3994)
- [뮤지컬 노트르담 드 파리](https://www.youtube.com/watch?v=R6Qg1isd9JM&list=PLQelIPu05G2lm-SuAFPE5EJW8BhTHCRr-)

### 인용구문

인용절은 보통 들여쓰기를 통해 사용자에게 일반 문장과 구분해준다.<br>
HTML 언어에서는 <blockquote>요소를 사용하여 인용절을 구조화한다.

> "Design is All. All is Design"<br>
> "Learn By Doing"<br>
> "그것이 최선입니까? 확실해요?"
