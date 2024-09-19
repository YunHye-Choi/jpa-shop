## h2 컨테이너 실행 명령어
- 우분투
  - docker run -d -p 1521:1521 -p 8081:81 -v /home/yunhye/h2/jpashop:/opt/h2-data -e H2_OPTIONS="-ifNotExists" --name=h2 oscarfonts/h2
- Mac
  - docker run -d -p 1521:1521 -p 8081:81 -v /Users/yunhye/h2/jpashop:/opt/h2-data -e H2_OPTIONS="-ifNotExists" --name=h2 oscarfonts/h2