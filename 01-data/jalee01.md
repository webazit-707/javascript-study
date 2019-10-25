  
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>

<body>
<p><b><u>&lt;사전적 의미&gt;</u></b></p>
<p><b><u>nul</u>l</b><span style="color: #333333;">은 JavaScript의<span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Glossary/Primitive">원시값</a><span style="color: #333333;"><span>&nbsp;</span>중 하나로, 어떤 값이 <b>의도적으로</b> 비어있음을 표현합니다.</span></p>
<p><span style="color: #333333;"><span style="color: #000000;"><b><a style="color: #000000;" href="https://developer.mozilla.org/ko/docs/Glossary/Undefined">undefined</a></b></span><span style="color: #333333;"><span style="color: #000000;">&nbsp;</span>원시 값을 나타내며, </span></span></p>
<p><span style="color: #333333;"><span style="color: #333333;">JavaScript의<span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Glossary/Primitive">원시 자료형</a><span style="color: #333333;"><span>&nbsp;</span>중 하나입니다. <span style="color: #333333;">함수는 값을 명시적으로<span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Statements/return">반환</a><span style="color: #333333;">하지 않으면&nbsp;</span>undefined<span style="color: #333333;">를 반환합니다.</span></span></span></p>
<p>&nbsp;</p>
<p><b>&lt;차이점&gt;</b></p>
<p><span>console.log(<b>typeof null</b>)&nbsp; &nbsp;/<b>/ 결과값&nbsp; : <span style="color: #009a87;">object <span style="color: #333333;"><span>&nbsp;</span>(하위호환 유지를 위해 "null"이 아님)</span></span></b></span></p>
<p><span>console.log(<b>typeof undefined</b>)&nbsp; //<b>결과값 :</b> <b><span style="color: #009a87;">undefined</span>&nbsp;</b> &nbsp;</span></p>
<p>&nbsp;</p>
<p><span>console.log(<b>1+null</b>)&nbsp; // <span style="color: #009a87;"><b>1</b></span></span></p>
<p><span>console.log(<b>1+undefined</b>) // <b><span style="color: #009a87;">NaN</span></b> : </span><b><span>숫자가</span><span> </span><span>아님</span><span><span>&nbsp;</span></span></b></p>
<p>&nbsp;</p>
<p><b><span><span><span>isNaN</span><span>(</span><span>1</span><span>&nbsp;</span><span>+</span><span>&nbsp;</span><span>null</span><span>)</span><span>&nbsp;</span><span>// <span style="color: #009a87;">false</span></span></span></span></b></p>
<p><b><span>isNaN</span><span>(</span><span>1</span><span>&nbsp;</span><span>+</span><span>&nbsp;</span><span>undefined</span><span>)</span><span>&nbsp;</span><span>// <span style="color: #009a87;">true</span></span></b></p>
<p>&nbsp;</p>
<p><span style="color: #333333;"><b>isNaN()</b><span style="color: #333333;"><span>&nbsp;</span>함수는 어떤 값이<span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/NaN">NaN</a><span style="color: #333333;">인지 판별합니다.</span></span></p>
<p><span style="color: #333333;"><span style="color: #333333;"><span style="color: #333333;">주어진 값이<span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/NaN">NaN</a><span style="color: #333333;"><span>&nbsp;</span></span><b>true</b><span style="color: #333333;">를, 그렇지 않은 경우<span>&nbsp;</span></span><b>false</b><span style="color: #333333;"><span>&nbsp;</span>를 반환합니다.</span></span></span></p>
<p>&nbsp;</p>
<p><b><span style="color: #006dd7;">var </span><span>이름</span><span> = &lsquo;</span><span>이정아</span></b><span><b>&rsquo;.</b> :<b> var</b></span><b><span>이</span><span> </span><span>붙어있으면</span><span> </span><span>값을</span><span> </span><span>새로</span><span> </span><span>기억</span></b></p>
<p><b><span>이름</span><span> = &lsquo;</span><span>별별</span></b><span><b>&rsquo;.</b> : <b>var </b></span><b><span>이</span><span> </span><span>안붙어있으면</span><span> </span><span>값을바꿉니다.</span><span></span></b></p>
<p><span>이름</span><span> // </span><b><span style="color: #009a87;">별별</span></b></p>
<p><b><span>이름</span></b><span><b> = undefined</b><span> :값을 바꿔줍니다.</span></span></p>
<p><span>이름</span><span> // <span style="color: #009a87;"><b>undefined</b></span></span><span><span> </span></span></p>
<p>&nbsp;</p>
<p><b><span><span>결론 :</span></span></b></p>
<p><b><span><span>&nbsp;</span></span><span style="color: #009a87;">의도적</span>으로<span> </span>빈<span> </span>값을<span> </span>넣고싶다면<span style="color: #009a87;"> null</span>을<span> </span>사용하는<span> </span>게<span> </span>좋습니다<span>.<span>&nbsp;</span></span></b></p>
<p><b><span>undefined</span>인지<span> null</span>인지<span> </span>표기를<span> </span>보고<span> </span>자신이<span> </span>의도한건지<span> </span>아닌지<span> </span>구분할<span> </span>수있기<span> </span>때문입니다<span>.</span></b><span><span> </span></span></p>
<p>&nbsp;</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style3" />
<h3 data-ke-size="size23"><b><span style="color: #333333;">null</span></b></h3>
<p><span style="color: #333333;">null<span style="color: #333333;">은 보통 반환값이 기대되지만 일치하는 값이 없을 때 대신 사용됩니다.</span></span></p>
<p>null<span style="color: #333333;"><span>&nbsp;</span>또는<span>&nbsp;</span></span>undefined<span style="color: #333333;">를 검사할 때,<span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Operators/Comparison_Operators">동등 연산자(==)와 일치 연산자(===)의 차이</a><span style="color: #333333;">를 주의하세요. 동등 연산자는 자료형 변환을 수행합니다.</span></p>
<p>&nbsp;</p>
<p><span>typeof</span> <span>null</span> <span>// "<b>object</b>" (하위호환 유지를 위해 "null"이 아님)</span></p>
<p><span>typeof</span> <span>undefined</span> <span>// "<b>undefined</b>"</span></p>
<p><span>null</span> <span>===</span> <span>undefined</span> <span>// false</span></p>
<p><span>null</span> <span>==</span> <span>undefined</span> <span>// true</span></p>
<p><span>null</span> <span>===</span> <span>null</span> <span>// true</span></p>
<p><span>null</span> <span>==</span> <span>null</span> <span>// true</span></p>
<p><span>!</span><span>null</span> <span>// true</span></p>
<p><span>isNaN</span><span>(</span><span>1</span> <span>+</span> <span>null</span><span>)</span> <span>// false</span></p>
<p><span>isNaN</span><span>(</span><span>1</span> <span>+</span> <span>undefined</span><span>)</span> <span>// true</span></p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style7" />
<h3><b><span style="color: #333333;">undefined</span></b></h3>
<p><b><span style="color: #333333;">undefined<span style="color: #333333;">와 일치, 불일치 연산자를 사용해 변수에 값이 할당됐는지 판별할 수 있습니다. </span></span></b></p>
<p><b><span style="color: #333333;"><span style="color: #333333;">다음 예제에서 변수<span>&nbsp;</span></span>x<span style="color: #333333;">는 초기화되지 않았으므로<span>&nbsp;</span></span>if<span style="color: #333333;">문은<span>&nbsp;</span></span>true<span style="color: #333333;">로 평가됩니다.</span></span></b></p>
<p>&nbsp;</p>
<p><span>var</span> x<span>;</span></p>
<p><span>if</span> <span>(</span>x <span>===</span> <span>undefined</span><span>)</span> <span>{</span></p>
<p><span>&nbsp; // <span style="color: #009a87;"><b>이 문이 실행됨</b></span></span></p>
<p><span>&nbsp; &nbsp; &nbsp; }</span> <span>else</span> <span>{</span></p>
<p><span>&nbsp; // <span style="color: #009a87;"><b>이 문이 실행되지 않음</b></span></span></p>
<p><span>}</span></p>
<p>&nbsp;</p>
<p><b><span><span style="color: #333333;"><span>&nbsp;</span></span><a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Operators/typeof">typeof</a><span style="color: #333333;">를 사용할 수도 있습니다.</span></span></b></p>
<p>&nbsp;</p>
<p><span><span>var</span> x<span>;</span></span></p>
<p><span> <span>if</span> <span>(</span><span>typeof</span> x <span>===</span> <span>'undefined'</span><span>)</span> <span>{</span> </span></p>
<p><span><span>&nbsp; &nbsp;// <span style="color: #009a87;"><b>이 문이 실행됨</b></span></span> </span></p>
<p><span><span>}</span></span></p>
<p>&nbsp;</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style3" />
<p><b><span><span>아래는 실제 결과값을 캡쳐한 사진입니다.</span></span></b></p>
<p>[##_Image|kage@bCOdGW/btqzjrdaKug/PHd22ensO2UAjAbU2jn3NK/img.png|alignCenter||_##]</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>출처 : zerocho youtube&nbsp; &amp; <a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/undefined">https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/undefined</a></p>
</body>
</html>
