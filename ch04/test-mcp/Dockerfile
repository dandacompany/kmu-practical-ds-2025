FROM python:3.13-slim
WORKDIR /app
COPY docker/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY src/ .
EXPOSE 8000
CMD ["python", "server.py"]