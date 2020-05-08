FROM python:3.6

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN pip install FLASK
RUN pip install wheel
RUN pip install flask-restful

ONBUILD COPY . /usr/src/app
CMD [ "python", "productitems.py" ]
