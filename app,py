from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return '''
    <html>
        <head><title>AK Computers</title></head>
        <body style="text-align: center; font-family: Arial; margin-top: 100px;">
            <img src="/static/logo.png" alt="Computer Logo" width="200" height="200">
            <h1>Welcome to <span style="color: blue;">AK Computers</span></h1>
        </body>
    </html>
    '''

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000, debug=True)
