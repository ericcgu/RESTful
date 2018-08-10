FROM python:3
RUN mkdir -p /home/project/restful
WORKDIR /home/project/restful
COPY requirements.txt .
RUN pip install --upgrade pip --no-cache-dir -r requirements.txt
COPY . .
CMD ["python", "app.py"]