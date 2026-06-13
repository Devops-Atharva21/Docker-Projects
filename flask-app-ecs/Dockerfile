#Take base images

FROM python:3.14 

#make Directory

WORKDIR /app

COPY . .

#Run pip 

RUN pip install -r requirements.txt 

#run the app

CMD ["python","run.py"]
