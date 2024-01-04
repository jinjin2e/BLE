# BLE
BLE, Bluetooth Low Energy 블루투스 4.0을 사용하는 저전력 디바이스를 말한다.  
저전력 디바이스인 만큼 고속통신에 단점이 있음. 대신 Coin Cell 하나만으로도 1년정도 동작 할 정도로 배터리 소모량이 적다.   
***


## 동작 방식 구분 
> ### Advertise Mode 
> 전원인가 후 주변의 모든 장치에 일방적으로 신호를 보내는 장치로 통신과는 무관한 비콘같은 장치. 2.4GHz 주파수 대역에서 Advertising Channel (37, 38, 39 채널)에서만 동작 ( 블루투스 장치들의 페어링 모드와 같은 동작인가? )  
>
>
>
> ### Connection Mode
> Advertising 패킷 전달 후 장치간의 연결의 과정이 필요한 동작 방식. 연결이 되면 Advertiser와 Observer는 서로 1:1 동작으로 Frequency Hopping 방식으로 동작한다. ( 페어링 성공 후 master 와 slave의 동작인듯 )  
> ```
> Advertiser : Signal을 주기적으로 보내는 디바이스
> Observer : Signal을 주기적으로 Scan 하는 디바이스 (Signal에 귀 기울이고 있는 디바이스)
> ```   
> ![image](https://github.com/jinjin2e/BLE/assets/93366905/3c8892d4-79ac-4272-980d-dcaa302761a6)


![images_zhemdrawer_post_d2802fee-27b3-4abb-9003-47365ed4052b_BLE_Layer_model](https://github.com/jinjin2e/BLE/assets/93366905/f174f189-e532-4321-b6a4-758e93ca6afd)
