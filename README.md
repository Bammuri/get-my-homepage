# get-my-home ver 0.1 
방명록 웹서비스 프로젝트
![tutorial](https://user-images.githubusercontent.com/28779618/77906987-d969cc00-72c3-11ea-834c-cd886d8f7cb9.gif)

http://ec2-15-165-172-121.ap-northeast-2.compute.amazonaws.com/

![210808_remove](https://user-images.githubusercontent.com/28779618/110314273-fc137180-804a-11eb-9912-6ae5c05f2836.png)

- 2021년 3월 8일 AWS 프리티어 종료로 배포가 중지되었습니다.

- 2020년 3월 27일 VER 0.1이 개발 완료 되었습니다.
- VER 0.1  
    - 구글, 네이버 소셜 로그인이 가능합니다.(chrome에서 접속 권장)
    - 방명록 (작성자, 제목, 내용)을 등록, 수정, 삭제할 수 있습니다.
    - 작성자는 수정이 불가능합니다.(readonly)

## Techset  
- Language : Java 8  
- Framework : Spring-boot 2.1.9   
- IDE : Intellij  
- Build tool : Gradle 4.10.2
- Test Framework : Junit 4  
- Database : H2(local), Mariadb(AWS RDB)  
- Others : AWS EC2, RDB(AWS), S3(AWS), GIT, Travis CI, CodeDeploy, Nginx(Reverse proxy)
