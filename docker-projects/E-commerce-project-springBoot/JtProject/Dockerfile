#take pateela
FROM alpine/java:22-jdk

#add Ingredients
WORKDIR /app

COPY JtSpringProjectApplication.java .

#mix the ingredient

RUN javac JtSpringProjectApplication.java

EXPOSE 8001

#Gas On

CMD ["java","JtSpringProjectApplication"]
