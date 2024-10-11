# 나만의 클라우스 서버 만들기 

![nextCloud](https://commons.wikimedia.org/wiki/File:Nextcloud_Logo.svg#/media/%ED%8C%8C%EC%9D%BC:Nextcloud_Logo.svg)

: 라즈베리파이를 이용하여 나만의 클라우드 서버를 만들어보자. 

## 준비물
- 라즈베리파이4
- 라즈베리파이용 전원 어댑터
- 블루투스 키보드    
- 마우스 
- 모니터
- micro HDMI 케이블

## 사전지식 
### 라즈베리파이 OS 
- 라즈베리파이 OS는 라즈베리파이에서 사용하는 운영체제이다.
### 3rd party OS
- 라즈베리파이 OS 외에도 다양한 OS가 있다.
### DietPi 
- DietPi는 라즈베리파이 OS의 한 종료로서, 새로운 소프트웨어를 설치하는데 있어서 최적화된 경량화된 OS이다. 

## 작업 순서 
1. [DietPi 다운로드](https://dietpi.com/)
2. 라즈베리파이4 DietPi 이미지 파일 다운로드
3. DietPi 이미지 굽기
4. 라즈베리퍼이에 DietPi 이미지 삽입 후 부팅하기
5. DietPi 로그인
    - ID: root
    - PW: dietpi
6. 시스템 업데이트 진행 
7. 재부팅 
8. nextcloud 설치 
9. 웹 브라우저에 `http://라즈베리파이ip주소/nextcloud` 접속
10. nextcloud 계정 로그인
    - ID : admin
    - PW : dietpi

# 실습1 - 핸드폰에 있는 사진을 nextcolud 서버에 업로드 하기
1. 핸드폰에서 nextcloud 앱 다운로드
2. nextcloud 앱 실행
3. 서버 주소 입력
4. ID, PW 입력
5. 사진 업로드
6. 같은 네트워크에 있는 컴퓨터의 웹 브라우저에서 nextcloud 서버에 접속하여 사진 확인

# 준비물 
- 라즈베리파이4
- microSD 카드
- 라즈베리파이 전원 어댑터
- 모니터
- 키보드
- 마우스
- 휴대폰

# 참고
- [How to Make a Raspberry Pi Cloud Server](https://www.instructables.com/How-to-Make-a-Raspberry-Pi-Cloud-Server/)
