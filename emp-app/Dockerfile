FROM python:3.10          # base image

WORKDIR /app              # working directory inside container

COPY backend/ /app/backend/     # copy backend code
COPY frontend/ /app/frontend/   # copy frontend files

RUN pip install --no-cache-dir -r /app/backend/requirements.txt

EXPOSE 80

CMD ["python", "/app/backend/app.py"]