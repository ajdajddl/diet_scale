# diet_scale
계산식) 적정체중 =(본인신장-100)*0.9
변수명) user_height user_weight normal_w
prompt 현재 키, 몸무게 입력받기
DOM 객체 변수 생성

---
<h1>prompt 현재 키 몸무게 입력받기</h1>

`let userheight = window.prompt('당신의 키는?')`

`let userweight = window.prompt('당신의 몸무게는?')`

`let normal_w = (userheight-100)*0.9`

`let result =userweight-normal_w`

<h1>DOM 객체 변수 생성</h1>

`const span_height = document.getElementsByClassName('height')[0]`

`const span_weight = document.getElementsByClassName('weight')[0]`

`const span_normal = document.getElementsByClassName('normal')[0]`

`const span_weight2 = document.getElementsByClassName('weight2')[0]`

<h1>검사</h1>

`console.log(userheight,userweight,normal_w,result)`

`console.log(span_height,span_weight,span_normal,span_weight2)`

<h1>DOM 변수에 데이터 변수 userheight~result 출력</h1>

`span_height.innerHTML = userheight`

`span_weight.innerHTML = userweight`

`span_normal.innerHTML = normal_w`

`span_weight2.innerHTML = result`
