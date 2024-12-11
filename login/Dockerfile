FROM python:3.9.10-slim-buster
RUN pip install flask
WORKDIR /home/microweb_app
COPY static/ static/
COPY templates/ templates/
COPY flask_app.py /home/microweb_app/
EXPOSE 5050
CMD python flask_app.py