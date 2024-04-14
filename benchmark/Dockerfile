FROM python:3.13.0a6-slim
RUN apt-get update && apt-get install -y less git
COPY requirements.txt /aider/requirements.txt
RUN pip install lox typer pandas matplotlib imgcat aider-chat
RUN pip install --upgrade pip && pip install -r /aider/requirements.txt
WORKDIR /aider

