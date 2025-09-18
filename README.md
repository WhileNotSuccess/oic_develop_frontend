# 실행방법
1. 이 리포지토리를 --recursive 옵션을 사용해서 클론한다.
2. vscode에 검색 기능을 사용해서 oic.yju.ac.kr을 localhost.com으로 전부 바꾼다
3. env를 설정한다
4. docker compose up -d
5. db 컨테이너에 접속해서 mysql -u root -p 를 사용해서 로그인한다
6. use db;
7. source /sqls/all.sql;
8. exit
