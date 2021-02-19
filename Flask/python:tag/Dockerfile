# https://hub.docker.com/_/python 태그 이용  

# python이 설치되어 있는 이미지를 다운
FROM python:3.9.2-alpine3.13
COPY . /app
WORKDIR /app

# flask 설치
RUN pip install flask

# 컨테이너 포트개방
EXPOSE 5000

# 실행 
CMD ["python", "app.py"]