FROM    tiangolo/uwsgi-nginx-flask:flask

RUN     apt-get update && \
        apt-get install libmysqlclient-dev -y && \
        pip install flask-mysql -y
 
ADD     /azure-vote /app
