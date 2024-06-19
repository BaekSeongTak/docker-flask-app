# flask/Dockerfile for Flask application
FROM python:3.9

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 파일 복사
COPY ./requirements.txt /app/requirements.txt
COPY ./app /app/app

# 의존성 설치
RUN pip install -r requirements.txt

# Flask 애플리케이션 실행
CMD ["flask", "run", "--host=0.0.0.0"]

