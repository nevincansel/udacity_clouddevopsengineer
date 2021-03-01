FROM python:alpine3.7 
COPY . /app
WORKDIR /app
RUN pip install flask
EXPOSE 11130 
ENTRYPOINT [ "python" ] 
CMD [ "HelloWorld.py" ]