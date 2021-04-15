# celery-monitor

> Flask-SocketIO celery websocket

use flask-socketio and celery monitor a bacground task

### install requirements

```shell
pip3 install -r requirements.txt
```

### usage

##### start celery process
``` shell
celery worker -A app.celery -P eventlet -l info
```
##### start flask
``` shell
python app.py
```

