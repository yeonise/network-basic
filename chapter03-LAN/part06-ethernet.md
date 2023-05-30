## Ethernet

미국 제록스(Xerox)사 팔로 알토 연구소(Palo Alto Research Center, PARC)의 로버트 맷칼프가 발명한 네트워크 규격이다.

현재 LAN 환경에서는 특별한 경우를 제외하고 모두 이더넷을 사용하고 있다.

- 버스형 LAN : 10BASE-2, 10BASE-5 등

- 스타형 LAN : 10BASE-T, 100BASE-TX, 1000BASE-T 등

통신 속도가 10Mbpss인 10BASE-T에 비해 고속 이더넷 규격인 100BASE-TX는 100Mbps로 빨라졌고, 기가비트 이더넷 규격으로 등장한 1000BASE-T는 1Gbps까지 고속화가 진행되었다.

현재는 1000BASE-T가 널리 이용되고 있어 '이더넷'이란 말은 '고속 이더넷', '기가비트 이더넷'을 포함한 모든 것을 칭하는 의미로 사용되고 있다.

이더넷에서는 네트워크의 통신 상태를 감시하여, 다른 사람이 송신하지 않을 경우에 한해 데이터를 송신하는 Carrier Sense 구조와 어쩔 수 없이 동시에 송신이 발생한 경우 신호 충돌을 검출하는 Collision Detection의 구조에 의해 통신을 제어한다. 이러한 제어 방법을 CSMA/CD(Carrier Sense Multiple Access/Collision Detection) 방식이라고 한다.

> CSMA/CD 방식은 송신하는 사람이 없는 경우에만 데이터를 전송한다. (Carrier Sense)  
그래도 동시에 전송하여 패킷 충돌(신호 충돌)이 발생하면 임의의 시간동안 대기한 뒤 재전송한다. (Collision Detection)  
이와 같이 통신을 수행하므로 케이블 하나를 여러 대의 컴퓨터가 공유할 수 있다.
