FROM python:3.12

COPY *.py setup.cfg LICENSE README.md requirements.txt /app/

WORKDIR /app

RUN pip install -r requirements.txt

RUN python setup.py install

EXPOSE 8000

CMD [ "/usr/local/bin/app1" ]