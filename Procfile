web: celery flower --port=$PORT --broker=$CLOUDAMQP_URL --basic_auth=$AUTH_USER:$AUTH_PW
worker: celery -A tasks worker --loglevel=info
