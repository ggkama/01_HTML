# HTML

## HTML 1번 글자관련태그

body 태그 : 브라우저에 보여질 내용을 작성하는 태그

    <body></body>



엔터 : br(line brake) 태그

    <br>

띄어쓰기 : %nbsp;

    &nbsp;


설명 (들여쓰기) : pre

    <pre></pre>


(bold) 태그 : 단순히 글자를 굵게 표시하는 태그

    <b></b>

(italic) 태그 : 단순히 글자를 기울여 표시하는 태그

    <i></i>

strong 태그 : 글자(단어)를 강조하는 태그

    <strong>내용</strong>

웹 접근성이란?- 일반인 뿐만 아니라 장애인,고령자들을 위해 웹 사이트에서 제공하는 모든 서비스를 이용할 수 있도록 보장하는 것 (웹 개발 의무 사항)

mark 태그 : <mark>형광팬 효과</mark>를 주는 태그

u(under) 태그 : <u>밑줄 긋는 태그</u>

s 태그 : <s>글자 가운데 선을 긋는 태그(취소,오타)</s>

del 태그 : <del>삭제선을 긋는 태그(있다가 없어짐)></del>

걸그룹 멤버 명단 : <del>미영(탈퇴)</del>, 숙희, <s>영희(오타)</s> 영숙 

small 태그 : <small>글자를 작게</small> 표시하는 태그

sup(윗첨자) 태그 : x<sup>3</sup>

sub(아랫첨자) 태그 : log<sub>2</sub>

abbr(abbreviation : 약어) 태그 : 마우스 오버 시 툴팁 제공


### 글자 관련 태그 연습

	<p>

    <mark>태그</mark>들은 해당 태그 내에서 중첩으로 사용 가능하다.<br>
    <strong>굵은</strong> 글자를  사용할 수 도 있고, <em>기울이거나,
    </em> <s>취소선</s>을 넣는 등<br>
    다양하게 사용할 수 있다.

	</p>



## HTML 2번 목록관련태그

ul (Unordered List) 태그 : 순서가 없는 목록
```
<ul>
</ul>
```
li (List item) 태그 : 목록의 한줄
```
<li>
</li>
```
ol(Ordered List) : 순서가 있는 목록
```
<ol>
</ol>
```

type 속성 : 표시되는 숫자 형식 지정

type="a" : 엉어 소문자(a,b,c,d,e....)
type="A" : 영어 대문자(A,B,C,D,E....)
type="i" : 로마 소문자(i, ii, iii, iv, v, vi...)
type="I" : 로마 대문자(I, II, III, IV, V, VI...)
type="1" : 숫자 (1, 2, 3)
start 속성 : 목록 시작 번호
eversed 속성 : 순서 반대로(역순)

<ol type="I" start="3" reversed>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
        <li>Java</li>
        <li>DB(Oracle)</li>
    </ol>

## HTML 3번 표관련태그

자료를 정리하기위해 사용하는 table 태그 
```
<tabel> </tabel>
```

테이블의 한 행을 나타내는 tr 태그
```
<tr></tr>
```

테이블에 출력될 값을 작성하는 td 태그
```
<td></td>
```

열의 제목을 나타내는 th태그 (td와 같은 레벨로 작성 -> td대신 th작성 가능)
```
<td></td>
```

표 또는 이미지의 설명을 작성하는 태그
```
 <caption style="caption-side: bottom;">제목</caption>
 ```

테이블 상단 영역(컬럼 제목 영역)을 나타내는 thead 태그
```
<thead></thead>
```

테이블 중단 영역(값 작성 영역)을 나타내는 tbody 태그
```
<tbody></tbody>
```

테이블 하단 영역(합계 영역)을 나타내는 tfoot 태그
```
<tfoot></tfoot>
```

열로 나열된 방향 (가로, 옆)을 병합하는 colspan(열 병합)속성
```
<td rowspan="3">서울시 중구</td>
```

