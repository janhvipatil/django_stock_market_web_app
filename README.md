# django_stock_market_web_app

## About

> A database driven Web App constructed using Django and Python and styled using Bootstrap CSS framework.
It's a Stock Market Portfolio app that let's you save stock ticker symbols to the database;
it then connects to a third party API to collect stock market information about your stocks.

## Getting Started

### Prerequisites

* Python 3.7; [pyenv](https://github.com/pyenv/pyenv) reccomended
* Pip

### Installing

Get the project up and running locally in just 5 easy steps.

1. Create a personal [Fork](https://github.com/janhvipatil/django_stock_market_web_app) of this repository.

2. **Clone** the fork with HTTPS, using your local terminal to a preferred location, and **cd** into the project.

```bash
git clone https://github.com/janhvipatil/django_stock_market_web_app.git

Cloning into 'django_stock_market_web_app'...
remote: Enumerating objects: 121, done.
remote: Counting objects: 100% (121/121), done.
remote: Compressing objects: 100% (86/86), done.
remote: Total 121 (delta 47), reused 102 (delta 31), pack-reused 0
Receiving objects: 100% (121/121), 46.54 KiB | 1.03 MiB/s, done.
Resolving deltas: 100% (47/47), done.

cd stocks/
```

3. Create your virtual environment, and activate it.

```bash
python -m venv venv
source venv/Scripts/activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run local server, and **DONE**!

```bash
python manage.py runserver

May 25, 2020 - 00:46:35
Django version 3.0.6, using settings 'stocks.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```

## Built With

* [Django](https://www.djangoproject.com/) Django is a high-level Web framework that encourages rapid development and clean, pragmatic design.
* [Python](https://www.python.org/)
* [Bootstrap](https://getbootstrap.com/)

## Credits 

* [Icon design](https://www.flaticon.com/) Used Flaticon.com for website icon.
* [API](https://iexcloud.io/) Got the API from IexCloud.io 

## License

[@MIT](https://github.com/janhvipatil/django_stock_market_web_app/blob/master/LICENSE)



