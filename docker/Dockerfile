FROM python:3.7

WORKDIR /workdir

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .
ENTRYPOINT ["python", "run.py"]
