#Take pateela 

FROM python:3.14

#Add ingredients

WORKDIR /app

COPY . .

#mix / precess the items

RUN pip install -r requirements.txt

EXPOSE 8000

#Gas On

CMD ["python","main.py"]
