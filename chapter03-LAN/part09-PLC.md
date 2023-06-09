## PLC(Power Line Communication)

*송선용 전기 배선을 사용하여 통신하는 기술*

전기 배선을 LAN 케이블으로 바꾸어 사용할 수 있게 한 기술이라고 이해하면 된다.

기존 건물에 LAN 배선을 구축하려면 대규모 공사가 필요하지만, 이 방식을 사용하면 기존의 전기 배선을 그대로 LAN의 네트워크 배선으로 사용할 수 있기 때문에 공사가 필요하지 않다. 또한 통신용으로 변경한다고 해서 전기 배선으로 이용할 수 없는 것이 아니므로 건물 내 LAN 배선을 간단히 구현할 수 있다.

PLC 어댑터에는 콘센트에 연결할 때 사용하는 전원 케이블과 LAN 케이블 연결용 단자가 준비되어 있다. 컴퓨터를 PLC 어댑터에 연결할 경우 이 단자에 LAN 케이블을 연결하여 통신한다.

> 가정의 전기 배선은 '교류'라는 전기가 흐른다. 교류 전기는 60Hz의 주파수로 전송된다. 반면, 데이터 통신 신호는 수 MHz라는 굉장히 높은 주파수로 전송된다. PLC 어댑터는 양쪽을 합친 신호를 만들어 전기 배선으로 송출한다. 수신하는 쪽의 PLC 어댑터는 주파수가 높은 데이터의 송신부분만 취득하여 사용한다.

> 모뎀(modem) : "Modulator-Demodulator"의 줄임말로, 통신 시설을 통하여 데이터를 전송할 때 전송되는 신호를 바꾸는 장치다. 직류 디지털 신호를 전화선으로 보낼 수 있는 교류 아날로그 신호로 바꾸고 아날로그 신호는 디지털 신호로 바꾼다. 즉, 인터넷 또는 전화 회선과 컴퓨터를 연결하는 다리 역할을 한다.
