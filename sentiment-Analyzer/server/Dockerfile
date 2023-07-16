# init a base image
FROM python:3.10

#define present working directory
WORKDIR /app

#Copy contents into working dir
ADD . /app

#Install dependencies 
RUN pip install -r requirements.txt

#command to build the image
CMD ["python", "app.py"]

