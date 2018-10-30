Flask-SocketIO-Chat
===================

A simple chat application that demonstrates how to structure a Flask-SocketIO application.

To run this application install the requirements in a virtual environment, run `python chat.py` and visit `http://localhost:5000` on one or more browser tabs.

If you prefer, you can also start the server using the Flask cli:

    $ FLASK_APP=chat.py flask run

To generate CERT and KEY for using SSL, run:

    openssl req -x509 -newkey rsa:4096 -nodes -out cert.pem -keyout key.pem -days 365
