# get-my-home ver 0.1 
방명록 웹서비스 프로젝트

http://ec2-15-165-172-121.ap-northeast-2.compute.amazonaws.com/

- 2020년 3월 27일 VER 0.1이 개발 완료 되었습니다.
- VER 0.1  
    - 구글, 네이버 소셜 로그인이 가능합니다.(chrome에서 접속 권장)
    - 방명록 (작성자, 제목, 내용)을 등록, 수정, 삭제할 수 있습니다.
    - 작성자는 수정이 불가능합니다.(readonly)

## Techset  
language : java 8 
framework : spring-boot 2.1.9   
IDE : Intellij  
build tool : gradle 4.10.2
test framework: junit 4  
database : H2(local), mariadb(AWS RDB)  
others : AWS EC2, RDB(AWS), S3(AWS), GIT, Travis CI, CodeDeploy, Nginx(Reverse proxy)