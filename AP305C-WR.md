## [CLI]
- 8PuTTy에서 AP의 IP주소 입력 
- ID : admin
- PW : aerohive 

- ssid Ark
- interface wifi0 ssid Ark
- save config

 ## AP장비 IP주소 찾는법 
 1) Advanced_IP_Scanner 사용하기
 2) 라우터에 연결 -> 라우터 IP HTTP 주소에 입력 -> 연결된 장비에 할당된 IP주소 찾기 

## 삭제방법
- show running-config 
- no interface wifi0 ssid Ark

- 이후 ssid 삭제하고싶으면
- no ssid Ark 
