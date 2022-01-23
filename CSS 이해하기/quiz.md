Q. 다음 중 CSS 규칙으로 바른 것을 고르세요.

1. ```h1 ( font-size: 15px, color: red )```
1. ```h1 { font-size = 15px; color = red }```
1. **```h1 ( font-size: 15px / color: red )```**
1. ```h1 { font-size: 15px; color: red }```

---

Q. 선택자에서 문서 내에 모든 요소를 선택할 수 있는 기호로 알맞은 것을 고르시오.

1. ```#```
2. ```@```
3. ```$```
4. **```*```**

---

Q. 다음 보기에서 class 선택자와 id 선택자의 설명으로 틀린 것을 고르시오.

1. class 선택자의 기호는 . 이다
2. **id 속성의 값은 문서 내에 유일하게 사용된다.**
3. id 선택자의 기호는 # 이다
4. id 속성의 값은 문서 내에 여러 번 사용될 수 있다.

---

Q. class명에 "button"으로 끝나는 요소가 선택되도록 알맞게 조합된 코드를 고르시오.

1. ```[class*="button"]```
2. ```[class~="button"]```
3. ```[class^="button"]```
4. **```[class$="button"]```**

---

Q. 아래 선택자 조합에서 item2가 선택되지 않는 것을 고르시오.

```html
<div class="wrap">

<strong> title </strong>
<p> description </p>

<ul class="list">

<li class="item i1"> item 1 </li>  
<li class="item i2"> item 2 </li>  
<li class="item i3"> item 3 </li>

</ul>

</div>
```

1. ```.wrap .item.i2```
2. **```strong + .list .i2```**
3. ```div > .list .i2```
4. ```.wrap .list .i2```

---

Q. 마우스 커서가 올라가 있는 요소를 선택할 때 사용하는 가상 선택자로 올바른 것을 고르시오.

1. ```:active```
2. **```:hover```**
3. ```:visit```
4. ```:focus```

---

Q. 가상 요소에 내용을 넣기 위해 사용되는 속성 명으로 올바른 것을 고르시오.

1. text
2. **content**
3. context
4. innertext

---

Q. 구체성이 가장 높은 셀렉터를 고르시오.

1. ```.name > .first```
2. ```.name > .first:hover```
3. **```#name```**
4. ```*```

---

Q. "box"의 폰트 색상으로 알맞은 것을 고르시오.

```html
<div class="wrap">

<div class="box">box</div>

</div>
<style>
.wrap { color: orange !important; }
.wrap div { color: red; }
.box { color: green !important; }
.wrap .box { color: blue; }
</style>
```

1. orange
2. red
3. **green**
4. blue

---

Q. "index 1"의 폰트 색상으로 알맞은 것을 고르시오.

```html
<div class="box" style="color: yellow">

<h1 class="title">title</h1>
<p class="desc">description</p>

<ul class="index" style="color: blue;">  

<li class="in_item in1">index 1</li>
<li class="in_item ">index 2</li>

</ul>

</div>

<style>

.box { color: red !important; }
.index > .in_item { color: pink; }
div ul .in_item { color: orange; }
.in_item.in1 { color: black; }
p + ul.index { color: yellow; }

</style>
```

1. **black**
2. yellow
3. orange
4. pink
5. blue