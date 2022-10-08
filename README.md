# chat-app-python
This is a small chat application using Flask and SocketIO to broadcast messages between clients.

## Virtual Environment Setup
* Create a virtual environment 
    ```python -m venv .env```
* Activate the virtual environment 
    ```activate .env/bin/activate```

## Install python packages
```
pip install -r requirements.txt
```
## Run Flask Application
```
flask --app main run
```
NOTE: `main` being the file name ```main.py```

## Accessing the Application
* Go to `http://localhost:5000` or `http://127.0.0.1:5000` in any web browser. If the url didn't work 
  then you can open the file `index.html` under templates.
* Similarly open couple other tabs with the same URL mentioned above

## Result
You will be able to see if you chat in a single window it should show up in other's chats as well.
