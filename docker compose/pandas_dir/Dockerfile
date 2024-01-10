FROM python:3.7-slim

RUN mkdir -p /app/pandas_dir_

COPY pandas_dir/. /app/pandas_dir_

WORKDIR /app/pandas_dir_


RUN pip install -r requirements.txt

# Run app.py when the container launches
CMD ["python", "pandasfile.py"]