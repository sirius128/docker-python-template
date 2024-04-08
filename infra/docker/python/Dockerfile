FROM python:3.12

WORKDIR /usr/src/app

COPY requirements.txt ./

RUN apt-get update && apt-get install -y \
    unzip \
    && rm -rf /var/lib/apt/lists/*

RUN pip install --no-cache-dir -r requirements.txt

COPY .. .

# Edit the name of the python file to run
# CMD [ "python", "./main.py" ]
