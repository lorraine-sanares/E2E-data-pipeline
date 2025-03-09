FROM python:3.9

RUN pip install pandas

# Location in the container where we will copy the file
WORKDIR /app

# copying file onto docker image
COPY pipeline.py pipeline.py

# asking docker to run pipeline file straight away
ENTRYPOINT ["python", "pipeline.py"]
