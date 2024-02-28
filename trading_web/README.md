# trading_web
## 웹 영상
https://github.com/jyy4014-git/trading_web/assets/134044918/965dd983-a1ed-4bf7-bce3-1c4d89f6928a



## 환경세팅
- Java 11 version
- Spring Boot
- Ajax
- Maria DB
- BootStrap

## 프로세스
- GCP 이용해 네이버, 증권사에서 데이터 수집하여 DB에 저장
- 웹과 DB를 연결하여 거래 정보, 뉴스 내용, 그래프 등 표시
- 그래프의 경우 3초마다 DB에서 새로운 데이터 가져와서 계속 이어져서 그래프를 그리도록 구현.

## 아쉬운점
- 레디스로 했다면 실시간 구현과 속도가 더 빨랐을 것 같다.
- 그래프를 불러오는 속도가 조금 느린 부분이 아쉽다.
