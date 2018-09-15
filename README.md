# Learning Flask by Tutorial
I stumbled across [this tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) and thought to give it a try.

## Venv setup
if not installed yet, install python3-venv as such:
```bash
sudo apt install python3-venv
```

After that you are ready to setup the environment:
```bash
python3 -m venv venv
source venv/bin/activate
pip install wheel flask python-dotenv flask-wtf flask-sqlalchemy flask-migrate flask-login flask-mail pyjwt
```

Now you should be all set to run the application
```bash
flask run
```
## Links which were usefull along the way
 - [Online Sql Designer](http://ondras.zarovi.cz/sql/demo/) An online tool to model Relational database models
 - [Flask Mail](https://pythonhosted.org/Flask-Mail/) Plugin to send mails from the application
 - [JSON Web Tokens](https://jwt.io/) for generating tokens for e.g. password resets
