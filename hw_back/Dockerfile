FROM python:3.7-alpine 
EXPOSE 8000
WORKDIR /hw_back
COPY requirements.txt /hw_back
RUN pip3 install -r requirements.txt --no-cache-dir
COPY . /pw_back
ENTRYPOINT ["python3"] 
