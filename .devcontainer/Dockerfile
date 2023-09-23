FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update && apt-get install -y \
    python3-pip \
    python3-dev \
    libpq-dev \
 && apt-get clean

RUN pip3 install --no-cache-dir --upgrade pip \
    Django>=3.2 \
    djangorestframework>=3.12 \
    psycopg2-binary>=2.8 \
    boto3 \
    mysql-connector-python \
    slack-sdk \
    reverse_geocoder \
    pyarrow \
    pandas \
    numpy \
    django-rest-passwordreset \
    mysqlclient \
    django-phonenumbers \
    django-slack \
    pillow \
    django-debug-toolbar
