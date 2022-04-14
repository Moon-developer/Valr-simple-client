# VALR Simple Python Client

| Python | 3.9, 3.10 |
|--------|-----------|

A Simple Python Library to integrate with [VALR API]("https://docs.valr.com").

## Cloning source

Get this package by:

```shell
$ git clone https://github.com/Moon-developer/Valr-simple-client.git
```

Activate the virtual environment with venv before coding, testing & packaging:

```shell
$ cd .
$ python3 -m venv .dev_env
$ source .dev_env/bin/activate
$ python3 -m pip install -r requirements.txt
```

Required `ENVIRONMENT` variables:

```dotenv
VALR_KEY='valr_key'
VALR_SECRET='valr_secret'
```

Example Usage, See `example.py` file:

```shell
$ python3 example.py
```