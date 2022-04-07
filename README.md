# rep
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
  return "privet"

app.run(port='8000')
