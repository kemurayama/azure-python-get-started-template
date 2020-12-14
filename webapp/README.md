# Azure Sample Python Web App

This is simple [Flask](https://flask.palletsprojects.com/en/1.1.x/) application for getting started.

```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
```

## Local Debug

```bash
export FLASK_APP=app/main:app
export FLASK_ENV=Development

pip install -r requirements.txt
flask run
```