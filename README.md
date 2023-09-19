# javascript0918
파일명 : exercise1.html

(1) <body> 태그의 첫번째 자식 태그로 <h1>자바스크립트 첫 번째 실습</h1> 과 그리고 두 번째 자식 태그로 <hr> 을 작성한다.
(2) window.prompt("숫자를 한 개를 입력하세요..") 를 사용해서 입력을 받는다.
(3) 입력된 숫자에 10을 곱한 결과는 <h2> 태그와 함께 도큐먼트 영역에 출력한다.
(4) 입력된 숫자에 10을 뺀 결과는 자바스크립트 콘솔 창에 출력한다.

파일명 : exercise2.html
- 구현 내용
1. 프롬프트 창으로 1 부터 9사이의 숫자를 한 개 입력 받는다.(숫자만 입력받는다고 가정한다.)
2. 입력된 숫자가 1~9 사이가 아니면 다시 입력받는다.
3. 입력된 숫자에 해당하는 단의 구구단을 행단위로 출력한다.

	n 단입니다.  	 --> 첫번째 제목크기, 원하는 색상
        ----------------------  	 --> 분리선(<hr> 태그)
         n x 1 = y1
         n x 2 = y2
             :


소스명 : exercise3.html
다음에서 제시된 기능들을 자바스크립트로 구현하시오.

(1) util.js 에 정의된 함수를 사용하여 구현한다.
(2) 웹 페이지의 제목을 <h1> 태그와 함께 "자바스크립트 실습(3)" 이라고 파란색으로 출력한다.
(3) window.prompt() 를 사용해서 사용자로 부터 숫자를 입력 받는다.
(4) 입력된 숫자는 자바스크립트 콘솔창에 출력한다.
(5) 1부터 이 숫자까지의 값을 더해서 브라우저의 도큐먼트 영역에 <h2> 태그와 함께 출력한다.
    "1부터 xx 까지의 합은 xxx 입니다."
(6) 입력된 데이터가 null 거나, "" 이면  "비어있는 입력" 이라는 메시지를
     브라우저의 도큐먼트 영역에 <h3> 태그와 함께 출력한다.
(7) 입력된 데이터가 숫자가 아니면
     브라우저의 도큐먼트 영역에 <h3> 태그와 함께 출력한다.

소스명 : exercise4.html
다음에서 제시된 기능들을 자바스크립트로 구현하시오.

(1) util.js 에 정의된 함수를 사용하여 구현한다.
(2) 웹 페이지의 제목을 <h1> 태그와 함께 "자바스크립트 실습(4)" 이라고 원하는 칼라로 출력한다.

(3) 다음 기능을 처리하는 함수 sum()를 구현해 본다.
	- 매개변수를 한 개 선언한다.
	- 매개변수에 아무값도 전달되지 않으면 리턴값 없이 리턴한다.
	- 1 부터 매개변수에 전달된 숫자값 까지 합을 구하여 리턴한다.

(4) 0부터 5사이의 난수를 하나 추출하여 아규먼트로 전달하면서 sum() 함수를 호출하는데
    0이 추출된 경우에는 아규먼트 없이 호출한다.
    호출한 다음 
    리턴값이 있으면 다음 형식으로 브라우저의 도큐먼트 영역에 <h2> 태그와 함께 출력하고

	호출 결과값 : XX

    리턴값이 없으면 다음과 같이 브라우저의 도큐먼트 영역에 <h3> 태그와 함께 출력한다.

	결과값이 없어요!!	      
     
     이 과정을 5번 반복한다.


