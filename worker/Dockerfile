FROM python:3.7
ADD . ./worker
WORKDIR ./worker
RUN pip3 install pika
EXPOSE 5672
EXPOSE 15672
CMD ["python3", "worker.py"]
