# # USE LIGHT WEIGHT LINUX WITH INSTALLED PYTHON I.E. python:3.8
# FROM python:3.10-slim-buster 

# # CREATE FOLDER INSIDE IT WHERE CODE WILL BE STORE
# WORKDIR /app

# # COPY REQUIREMENTS FROM LOCAL TO CONTAINER
# COPY requirements.txt requirements.txt

# # RUN RQUIREMENTS.TXT 
# RUN pip install --upgrade pip
# RUN pip install -r requirements.txt

# COPY . . 

# CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]



FROM python:3.10-slim-buster 
ENV PYTHONBUFFERED=1
WORKDIR /django 
COPY requirements.txt requirements.txt 
RUN pip3 install -r requirements.txt 
