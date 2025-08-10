FROM python:3.13.5

## djangoのインストール
RUN pip install -U pip \
    && pip install django

WORKDIR /home/myapp

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]