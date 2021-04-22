
FROM python:alpine
RUN pip install redis
RUN pip install requests

COPY . .

ENTRYPOINT ["python"]
CMD ['worker.py"]
