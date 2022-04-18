FROM python:3.8


WORKDIR /usr/src/app

RUN pip install django==3.1.13
RUN pip install pymysql==1.0.2


COPY ./django-test .


CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]

EXPOSE 8000