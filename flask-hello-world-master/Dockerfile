FROM python:python3
 
LABEL Name=kartaca-flaskapp Version=0.0.1
EXPOSE 8000

RUN mkdir /docker-code
WORKDIR /docker-code
ADD . /docker-code

RUN python3 -m pip install -r requirements.txt
CMD ["python3", "hello.py"]