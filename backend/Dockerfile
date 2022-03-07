FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /monologue/backend/
ADD requirements.txt /monologue/backend/
RUN pip install -r requirements.txt
COPY . /monologue/backend/