### **1\. [https://www.naver.com:443](https://www.naver.com:443) -> 요청이 된다**

\-> HTTP 요청 메시지를 생성한다.

### **2\. 클라이언트에서 HTTP 메시지를 전송한다.**

\-> 웹 브라우저가 HTTP 메시지를 생성하고 -> SOCKET 라이브러리를 통해 전달(TCP/IP 연결) -> TCP/IP 패킷 생성(HTTP 메시지 포함) -> LAN 드라이버와 장비를 통해 서버로 전송

### **3\. 서버가 요청(request)패킷을 받고 응답(response) 메시지를 전송한다.**

### **4\. 응답 패킷이 도착하면 웹 브라우저가 HTML을 렌더링 한다.**

https://layton0-0.tistory.com/47?category=1108221
