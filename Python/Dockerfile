FROM python:3.9

WORKDIR /app
# misspelt app as appp

COPY app.py /app
# misspelt app.py as appy.py

RUN pip install flask netiface

EXPOSE 8000
# port is a numeric value

CMD ["python", "app.py"]
# misspelt python as pythn
