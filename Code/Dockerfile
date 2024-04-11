#Python light edition#
FROM python:3.8.10-slim  

#Create a work directory name like code,app etc
WORKDIR /code

#


#Run pip to install necessary dependencies in the image for fastapi
RUN pip install fastapi uvicorn

# copy from current directory to work directory
COPY . /code

#
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]