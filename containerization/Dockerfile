FROM python:3.9-slim
WORKDIR .
COPY requirements.txt .
RUN python3 -m pip install -r requirements.txt
COPY . .
EXPOSE 5000
ENTRYPOINT python3 app.py