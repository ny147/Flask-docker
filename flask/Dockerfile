FROM python:3.9

# specify the current wd
WORKDIR /app

#copy current directory
ADD . /app

# Use pip to install the project requirements
RUN pip install -r requirements.txt

# Run the web server upon startup with eight threads 
CMD ["uwsgi","app.ini"]