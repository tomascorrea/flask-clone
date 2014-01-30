flask-clone
===========

Add a clone method a flask application.

```python

from flask.ext.clone import Flask

app_1 = Flask('app1')

@app_1.route('/')
def home():
  return 'Hello'
  

app_2 = Flask('app2')

app_2.clone(app_1)

```
