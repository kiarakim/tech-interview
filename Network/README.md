# Network
1. [Internet Network](#internet-network)
2. [HTTP Concepts](#http-concepts)
3. [HTTP Method, State Code and Header](#http-method-state-code-and-header)
4. [HTTP Versions](#http-versions)
5. [REST](#rest)
6. [ETC](#etc)

&nbsp;
## Internet Network
### OSI 7계층
### IP와 IP 주소
### TCP와 UDP
#### TCP
인터넷 상에서 데이터를 메세지의 형태 죽,세그먼트 라는 블록 단위로 보내기 위해 IP와 함께 사용하는 프로토콜이다.
TCP와 IP를 함께 사용하는데, IP가 데이터의 배달을 처리한다면 TCP는 패킷을 추적 및 관리한다.
높은 신뢰성을 보장한다.
연속성보다 신뢰성있는 전송이 중요할 때에 사용된다.

#### UDP
데이터를 데이터그램 단위로 처리하는 프로토콜이다.
정보를 주고 받을 때 정보를 보내거나 받는다는 신호절차를 거치지 않는다.

#### TCP vs UDP
| TCP | UDP |
| --- | --- |
| 연결형 서비스가상 회선 방식 제공 | 비연결형 서비스로 데이터그램 방식 제공 |
| 높은 신뢰성 보장 | 신뢰성 낮아 연속성이 중요한 서비스에 사용 |


### 로드밸런싱
### 라우팅
### DNS
### NAT
### DHCP
### 서브넷 마스크와 게이트웨이
### 소켓
TCP Socket이라고 했을 때, TCP를 User Mode Application이 접근할 수 있도록 File 형식으로 추상화 한 인터페이스.


## HTTP Concepts
### HTTP
### 쿠키와 세션
### URI, URL, URN

## HTTP Method, State Code and Header
### HTTP Method
### HTTP 응답코드
### HTTP 헤더

## HTTP Versions
### HTTP/1.1과 그 이전
### HTTP/2.0
### HTTP/3.0
### HTTPS

## REST
### REST API
### RESTful

## ETC
### 웹 서버와 WAS의 차이점
### Socket.io와 WebSocket의 차이
### 브라우저 동작 방법
### OAuth
### www.kakao.com을 브라우저에 입력하고 엔터를 쳤을 때, 네트워크상 어떤 일이 일어나는지 설명해 주세요.
