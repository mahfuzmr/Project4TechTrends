FROM python:3.8
LABEL maintainer="Mahfuzur Rahman"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN python init_db.py
CMD [ "python", "app.py" ]
EXPOSE 3111
#description
#install requirements
#database initialization
#run app.py on port 3111