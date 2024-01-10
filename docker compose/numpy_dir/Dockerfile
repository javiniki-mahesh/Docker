FROM python:3.7-slim

RUN mkdir -p /app/numpy_dir_

COPY numpy_dir/. /app/numpy_dir_/

WORKDIR /app/numpy_dir_

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# Run app.py when the container launches
CMD ["python", "numpyfile.py"]
