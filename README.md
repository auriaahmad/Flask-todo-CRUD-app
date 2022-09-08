# Flask-todo-CRUD-app
### Learning outcome
- How to setup a basic CRUD application with Flask with SQLite DB
- Jinja template 
- host flask app on Heroku

### TODO APP 
👇👇👇
- [Link](https://flaskcrudappauria.herokuapp.com/) 

![image](https://user-images.githubusercontent.com/50408063/188907553-6802e811-5533-4e63-91a7-e0f370efb254.png)

## How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```


