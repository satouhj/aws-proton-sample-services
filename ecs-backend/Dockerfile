FROM 095820445610.dkr.ecr.ap-northeast-1.amazonaws.com/python:3.8.3-slim-buster
COPY app.py requirements.txt ./
RUN pip install -r requirements.txt
EXPOSE 80
CMD [ "python", "app.py"]
