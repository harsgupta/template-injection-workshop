FROM python:3.13-rc-slim
COPY ./src /app
WORKDIR /app
RUN pip install -r /app/requirements.txt
ENTRYPOINT ["python"]
CMD ["./app.py"]