FROM python:3.8

RUN mkdir /backend
WORKDIR /backend
ADD . /backend/
RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "/backend/main.py"]