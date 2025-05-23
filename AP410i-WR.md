# Extreme AP410i 구성 방법

## 1. AP 연결 및 IP 찾기
- 라우터와 AP를 연결
- 라우터와 컴퓨터를 연결
- AP의 IP 주소 확인
  - 라우터 관리 페이지에서 연결된 장치 목록 확인
  - 또는 IP 스캐너 도구 사용

## 2. Windows Telnet 연결
- Windows 기능에서 Telnet 클라이언트 활성화
  - 제어판 → 프로그램 및 기능 → Windows 기능 켜기/끄기
  - "Telnet 클라이언트" 체크박스 선택
- 명령 프롬프트(CMD) 실행
- `telnet [AP의 IP 주소]` 명령어 입력

## 3. Wing 접속
- 웹 브라우저 열기
- 주소창에 `https://[AP의 IP 주소]` 입력
- 보안 경고가 표시될 경우 "계속 진행" 선택
- 관리자 계정으로 로그인

## 4. Wing에서 SSID 설정
- 왼쪽 메뉴에서 "Wireless" 또는 "무선" 선택
- "SSID" 또는 "무선 네트워크" 설정 선택
- 새 SSID 생성 또는 기존 SSID 편집
- 네트워크 이름, 보안 유형, 암호 등 설정
- 변경사항 저장 및 적용

---

## 1. VLAN 설정하는 방법 
- WING에 접속하여 Configuration -> Devices -> Sytem Profile -> default-ap410 -> Virtual Interfaces 에서 추가 하면된다.

![image](https://github.com/user-attachments/assets/5b16d561-4e81-45a9-9d63-6cccf1df5d06)


![image](https://github.com/user-attachments/assets/0cb8d9ec-15e6-4a17-98b9-8bbda0655799)
