FROM python:3.8-alpine
COPY . /app
WORKDIR /app
# ENV FLASK_APP=app.py
# ENV FLASK_RUN_HOST=0.0.0.0
RUN pip install -r requirements.txt
CMD python app.py 
EXPOSE 5001
# CMD ["flask","run"]