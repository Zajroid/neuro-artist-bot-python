# neuro-artist-bot for tg

## create virtual venv
```
python -m venv venv
```
## Install requiremnts
```
pip install -r requirements.txt
```


# Tree projects

```
neuro-artist-bot/
├── Dockerfile
├── README.md
├── bot.py
├── docker-compose.yml
├── requirements.txt
└── tgbot
    ├── assets
    │   ├── images
    │   └── stickers
    ├── config
    │   ├── __init__.py
    │   └── config.py
    ├── database
    │   └── __init__.py
    ├── filters
    │   └── __init__.py
    ├── handlers
    │   └── __init__.py
    ├── keyboards
    │   ├── __init__.py
    │   ├── inline.py
    │   └── reply.py
    ├── mics
    │   ├── __init__.py
    │   └── states.py
    ├── middlewares
    │   └── __init__.py
    ├── models
    │   └── __init__.py
    └── services
        └── __init__.py
```