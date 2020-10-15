## [LOSE_WAIT & TIME_WAIT 최종 분석](https://tech.kakao.com/2016/04/21/closewait-timewait/)

1. 트래픽이 많은 웹서비스에서 발생하는 일
- cpu가 여유가 있는데도, 웹서버가 응답을 못하는 경우
- 대표적인 이유로, CLOSE_WAIT상태


2. CLOSE_WAIT로 인한 서버 행업 현상
- [lsof 사용법](https://www.lesstif.com/system-admin/lsof-20776078.html): lsof -i:8080 -> 8080포트를 쓰는 프로세스 정보
- [netstat 사용법(https://websecurity.tistory.com/103) netstat -tonp ->

북마크: 예제 TCP 서버부터
