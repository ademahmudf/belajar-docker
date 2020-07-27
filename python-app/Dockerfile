FROM python:3 

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY app ./
EXPOSE 8080
CMD [ "python", "./server.py"]
