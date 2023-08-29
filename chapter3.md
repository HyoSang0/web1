# HTML   
* html은 마크업 언어라고 부른다  
* 꺽쇠<>안에 넣어서 코드를 작성  
* 태그 문법  

```html
<div 속성이름="속성값"></div>  
<div style="color:red"></div>  
```  

# 자주 사용되는 html 태그  
```html
    <h1>헤드 태그</h1>
    <h2>1에서 6까지</h2>
    <h6>점점 작아짐</h6>
    <div>한 줄 씩 영역을 가짐</div>
    <div>영역2</div>
    <p>긴 문장을 쓸 때</p>
    <p>긴 <span style="color:red">문장 중간 특정 단어를 꾸미고 싶을 때</span> 문장을 쓸 때</p>
    <ul>
        <li>리스트1</li>
        <li>리스트2</li>
    </ul>
    <br/> //영역 사이 공백
    <hr/> //영역 사이 수평선과 공백
    <input type="text" /> //입력 받을 때
    <input type="number" />
    <button>버튼</button>
    <img src="이미지 주소"/>
```  

# css  
* class와 id를 통해서 꾸민다.  
* hdmi 코드에 선택자(class, id)를 부여하고 css로 선택해 꾸민다.  
* class는 띄어쓰기를 통해 여러가지를 가질 수 있고 id는 오직 한 가지만 가질 수 있다.  
* 꾸미기는 태그 안에서, head 태그 안에서, css에서. 3가지 방법으로 꾸밀 수 있다.

## html 안에서 style로 꾸미는 법
```html
<head>
    <style>
        .title{ /*class가 title인 친구를 호출*/
            color:red
        }
        #title{ /*id가 title인 친구를 호출*/
            color:red
        }
    </style>
</head>
<body>
    <p class="title" id="title">긴 문장을 쓸 때</p>
</body>
```  

## css와 연동하는 법
```html
<head>
    <link rel="stylesheet" href="./main.css"/>
</head>
<body>
    <p class="title" id="title">긴 문장을 쓸 때</p>
</body>
```

```css
.title{  /*class가 title인 친구를 호출*/
    color:red
}
#title{ /*#id가 title인 친구를 호출*/
    font-size: 150%;
}
```  

# 자주 사용하는 css 속성  
```css
p > span { 
    color:red;
}

.layout{
    background-color: blue;
    width: 300px;
    height: 300px;
    border: 10px solid #000;
    border-radius: 100px;
    text-align: center; /*가운데 정렬*/
}
.title{
    color:#fff;
    font-size: 200%;
    font-weight: 900;
    margin-top: 100px; /*부모 태그로부터 여백*/
    padding-top: 50px; /*현재 태그의 여백*/
}
```

## 구글 웹 폰트
[https://fonts.google.com/?subset=korean&noto.script=Kore]  
* 폰트 선택 > select > link  
