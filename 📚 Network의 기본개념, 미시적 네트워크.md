![image](https://github.com/user-attachments/assets/fbdd7779-59ac-4f30-bc63-9885a791909a)![image](https://github.com/user-attachments/assets/2e0a546a-5dba-461f-adf7-aa567ce89e7d)❓ 네트워크를 알아야 하는 이유 
  - AWS의 EC2 인스턴스 띄우기, 보안 그룹 설정, 리눅스 원격 접속, 웹 서버 설치 및 구축 등에 대한 이해
  - 웹 어플리케이션 개발 및 유지보수 기본 지식
  - 회사에서의 커뮤니케이션

--------------- 기본 양식 ----------------

<details>
<summary>❓</summary>

>""

</details>

------------------------------------------
<details>
<summary>❓네트워크의 개념</summary>

>"여러 개의 장치가 마치 그물처럼 서로 연결되어 정보를 주고받을 수 있는 통신망"
>![image](https://github.com/user-attachments/assets/2d4e1e7c-c3e9-4fcc-a39e-9704abeb66c8)

</details>


<details>
<summary>❓인터넷의 개념</summary>

>"여러 네트워크를 연결한 '네트워크의 네트워크', inter + net"
![image](https://github.com/user-attachments/assets/629ab70e-0a9b-4a84-825e-dd350aa9cb06)

</details>

<details>
<summary>❓네트워크를 알아야 하는 2가지 큰 이유</summary>

>"프로그램 개발", "유지보수"에 있어서 꼭 필요한 지식이다.

</details>

<details>
<summary>❓그래프의 개념</summary>

>"노드(node, vertex)와 노드(node, vertex)를 연결하는 간선(edge, link)로 이루어진 자료 구조"
![image](https://github.com/user-attachments/assets/31e77db8-93a5-4bf7-abdb-0c5a01cffef3)

</details>

<details>
<summary>❓자료구조란</summary>

> data structure, "정보를 표현하고 다루는 방법을 의미한다."

</details>

<details>
<summary>❓모든 네트워크의 구성</summary>

>"모든 네트워크는 '노드'와 노드를 연결하는 '간선', 노드 간 주고받는 '메시지'로 구성된다."
![image](https://github.com/user-attachments/assets/d21227e4-b0bc-41a8-a475-4b73cf95bfdc)

</details>

<details>
<summary>❓호스트(host)의 개념</summary>

>"네트워크에서의 가장 자리 노드, 종단시스템(end system), 네트워크를 통해 흐르는 정보를 최초로 생성 및 송신하고, 최종적으로 수신한다."
![image](https://github.com/user-attachments/assets/99302c28-094c-4b37-903f-08d642b43225)

</details>

<details>
<summary>❓서버(server)의 개념</summary>

>"어떠한 서비스를 제공하는 호스트, 서비스란 파일, 웹 페이지, 메일이냐에 따라 파일 서버, 웹 서버, 메일 서버가 될 수 있다."

</details>

<details>
<summary>❓클라이언트(client)의 개념</summary>

>"서버에게 어떠한 서비스를 요청(request)하고 서버의 응답(response)을 제공받는 호스트"

</details>

<details>
<summary>❓네트워크 장비의 개념과 예시</summary>

>"네트워크 장비란 호스트 간 주고받을 정보가 중간에 거치는 노드(가장자리 노드가 아닌 노드)를 말한다. 예시로 이더넷 허브, 스위치, 라우터, 공유기 등이 있다. 호스트 간 주고받는 정보가 수신지가지 안정적이고 안전하게 전송될 수 있도록 한다."
![image](https://github.com/user-attachments/assets/72ac8333-cf53-40d8-9d0a-22fb2fe9ae7c)

</details>

<details>
<summary>❓통신 매체의 개념</summary>

>"호스트와 네트워크 장비라는 각 노드를 연결하는 간선, 호스트와 네트워크 장비를 연결하는 유무선 매체라고 생각하며 된다."
![image](https://github.com/user-attachments/assets/99462c78-8740-4a7f-b352-8e9b3bada7aa)

</details>

<details>
<summary>❓메시지의 개념</summary>

>"통신 매체로 연결된 노드가 주고받는 정보 ( 웹 페이지, 파일, 메일 등... )"

</details>

<details>
<summary>❓LAN의 개념</summary>

>"Local Area Network의 약자로, 가까운 지역을 연결한 근거리 통신망을 말한다. ( 가정, 기업, 학교처럼 한정된 공간에서의 네트워크 ) "
![image](https://github.com/user-attachments/assets/62c2c2b8-307c-4439-8147-87517cc44b18)

</details>

<details>
<summary>❓WAN의 개념</summary>

>"Wide Area Netowrk의 약자로, 먼 지역을 연결하는 광역 통신망이다. 멀리 떨어진 LAN을 연결할 수 있는 네트워크이자 인터넷이 WAN에 속한다."

</details>

<details>
<summary>❓ISP의 개념</summary>

>"Internet Service Provider의 약자로 인터넷 서비스 업체이자, WAN에 연결 가능한 회선 임대 등의 WAN 관련 서비스를 제공한다. ( KT, LG유플러스, SK브로드밴드 등... ) "

</details>

<details>
<summary>❓회선 교환방식의 개념</summary>

>"호스트들이 네트워크를 통해 메시지를 주고 받는 방법 중, 메시지 전송로인 회선(circuit)을 설정하고 이를 통해 메시지를 주고 받는 방식(circuit switching)이다."
![image](https://github.com/user-attachments/assets/c916361f-8041-4ef5-b59f-a1b5c9450f07)

</details>

<details>
<summary>❓회선 스위치의 개념</summary>

>"호스트 사이의 일대일 전송로를 확보하는 네트워크 장비로, 회선 교환 네트워크가 올바르게 작동하도록 회선을 설정하는 네트워크 장비이다."
![image](https://github.com/user-attachments/assets/2e829521-1579-4352-af45-c9248b7b7ac4)

</details>

<details>
<summary>❓회선 교환 방식의 장단점</summary>

>"시간 동안 전송되는 정보의 양은 비교적 일정한 편이지만, 이용 효율에 있어서 문제점이 발생한다."

</details>

<details>
<summary>❓패킷의 개념</summary>

>"packet이란 패킷 교환 네트워크상에서 송수신되는 메시지의 단위를 말한다."

</details>

<details>
<summary>❓패킷 교환 방식의 개념</summary>

>"회선 교환 방식의 문제점을 해결한 방식으로, 메시지를 패킷(packet)이라는 작은 단위로 쪼개어 전송한다. 대부분의 현대 인터넷이 이용하는 방식이다."
![image](https://github.com/user-attachments/assets/11fd9ed6-b1a7-466e-bbae-6c7f2affcc08)

</details>

<details>
<summary>❓패킷 교환 방식의 장단점</summary>

>""

</details>

<details>
<summary>❓패킷 교환 방식의 장점</summary>

>"회선 점유가 없어서 네트워크 이용 효율이 상대적으로 더 높다. "

</details>

<details>
<summary>❓패킷 스위치의 개념</summary>

>"패킷 스위치는 패킷이 수신지까지 올바르게 도달할 수 있도록 최적의 경로를 결정하거나 패킷의 송수신지를 식별하는 장비이다."
![image](https://github.com/user-attachments/assets/637145f1-9109-40f7-b5cd-91106302db5d)

</details>

<details>
<summary>❓대표적인 패킷 스위치 장비의 예시</summary>

>"라우터(router)와 스위치(switch)"

</details>

<details>
<summary>❓패킷의 헤더와 트레일러, 페이로드의 개념</summary>

>"헤더와 트레일러는 각각 패킷의 앞뒤에 붙는 부가정보이고, 페이로드는 패킷을 통해 전송하고자 하는 데이터를 말한다."

</details>

<details>
<summary>❓패킷에 담기는 주소의 개념</summary>

>"주소(address)는 송수신지를 특정하는 정보를 말한다. (IP 주소, MAC 주소.. )"

</details>

<details>
<summary>❓유니캐스트의 개념</summary>

>"가장 일반적인 송수신 형태로, 하나의 수신지에 메시지를 전송하는 방식 ( 송신지와 수신지가 일대일로 메시지를 주고받는 방식 )"

</details>

<details>
<summary>❓브로드캐스트의 개념</summary>

>"자신을 제외한 네트워크상의 모든 호스트에게 전송하는 방식"

</details>

<details>
<summary>❓브로드캐스트 도메인의 개념</summary>

>"브로드캐스트가 전송되는 범위, 즉 자신을 제외한 네트워크상의 모든 호스트를 말한다. "

</details>

<details>
<summary>❓멀티캐스트의 개념</summary>

>"네트워크 내의 동일 그룹에 속한 호스트에게만 전송하는 방식"

</details>

<details>
<summary>❓애니캐스트의 개념</summary>

>"네트워크 내의 동일 그룹에 속한 호스트 중 가장 가까운 호스트에게 전송하는 방식"

</details>
