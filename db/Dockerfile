# db/Dockerfile for MySQL
FROM mysql:8.0

# 환경 변수 설정
ENV MYSQL_ROOT_PASSWORD=${MYSQL_ROOT_PASSWORD}
ENV MYSQL_DATABASE=${MYSQL_DATABASE}
ENV MYSQL_USER=${MYSQL_USER}
ENV MYSQL_PASSWORD=${MYSQL_PASSWORD}

# 초기화 SQL 파일 추가
COPY init_db.sql /docker-entrypoint-initdb.d/init_db.sql

