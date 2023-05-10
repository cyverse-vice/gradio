FROM python:latest

COPY requirements.txt .
COPY app.py .

RUN pip install -r requirements.txt

EXPOSE 7860

ENTRYPOINT python app.py