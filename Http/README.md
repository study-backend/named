
Http 란
Hyper Text Transfer Protocol 의 약자
: 인터넷에서 데이터를 주고받을 수 있는 프로토콜

7.http
1. 특징
•	인터넷상에서 데이터를 주고 받기 위한 서버/클라이언트 모델을 따르는 전송 프로토콜
•	애플리케이션 레벨의 프로토콜로 TCP/IP위에서 작동
•	클라이언트에서 요청(request)를 보내면 서버는 요청을 처리해서 응답(response)
•	80번 port 이용
비상태연결(Stateless, Connectless)
서버에 연결하고 요청해서 응답을 받으면 연결을 끊어버린다.
•	장점: 접속유지 최소화, 불특정 다수를 대상으로 하는 서비스에 유리
•	단점: 연결을 끊어버리기 때문에, 클라이언트의 이전 상태를 알 수 없음, 따라서 로그인을 해도 정보유지 불가, 이를 해결하기 위해 쿠키 등등을 이용

-상태코드(100~500)
	1xx : 정보성
	2xx : 성공
	3xx : 리다이렉트
	4xx : 클라이언트 오류
	5xx : 서버 오류
-http header에 대한 값을 보고 header의 내용을 추가하거나 할 수 있음
header에 대한 내용 - 핵심/ body - 본질
header에 대한 규약, body에 대한 규약
header가 어떻게 돼있고 body가 어떻게 돼있고

-request/response 분리되어있다. 
HTTP의 특징
- HTTP 메시지는 HTTP 서버와 HTTP 클라이언트에 의해서 해석이 됩니다.
- TCP/IP를 이용하는 응용 프로토콜(application protocol)입니다.
- HTTP는 연결 상태를 유지하지 않는 비연결성 프로토콜입니다. (이러한 단점을 해결하기 위해 Cookie와 Seesion 등장)
- HTTP는 연결을 유지하지 않는 프로토콜이기 떄문에 요청/응답(request/response) 방식으로 동작합니다.

기본적으로 아래와 그림과 같이 동작합니다.

 

예를들면, 클라이언트(client) 즉, 사용자가 브라우저를 통해서 어떠한 서비스를 url을 통하거나 다른 것을 통해서 요청(request)을 하면 서버에서는 해당 요청사항에 맞는 결과를 찾아서 사용자에게 응답(response)하는 형태로 동작합니다.

- 요청 : client -> server
- 응답 : server -> client


request가 어떻게 돼있고 response가 어떻게 돼있는지!!

header
클라이언트나 서버가 리퀘스트나 리스폰스를 처리하기 위한 정보가 들어있다. 
이러한 정보의 대부분은 클라이언트를 이용하는 사용자가 직접 볼 필요는 없습니다.
구성요소 : URI, 메소드, HTTP버전, HTTP헤더 필드
body
사용자와 리소스를 필요로 하는 정보

