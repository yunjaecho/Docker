# Docker

## MYSQL 설치
#### 1. sudo docker pull mysql : 도커 이미지 가져오기
#### 2. sudo docker images : 도커 이미지 목록 확인
#### 3. sudo docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=패스워드 --name mysql mysql : 도커 이미지 커테이너 생성 및 실행
#### 4. sudo docker ps -a : 도커 프로세스 확인 (-a 옵션은 중지된 프로세스 확인)
#### 5. sudo docker rm mysql : 도커 프로세스 완전 삭제
#### 6. sudo docker rmi mysql : 도커 이미지 삭제
옵션 : -d : detach , -p 3306:3306 : 포트 앞의것은 host, 뒤의것 docker container 

#### 7. sudo docker exec -it mysql_dev bash : mysql 실행
