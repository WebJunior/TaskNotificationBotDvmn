# Task notification bot for [dvmn](https://dvmn.org/)
## 1. Описание
Бот позволяет получать мгновенные уведомления о проверке заданий через телеграмм. 

## 2. Требования к окружению
Бот разрабатывался на языке `python 3.7.3`. Для его запуска потребуется установить
 [интерпретатор python](https://www.python.org/downloads/).

### 2.1 Переменные окружения
Для работы бота понадобятся следующие переменные:

    * DVMN_TOKEN
    * TELEGRAM_BOT_TOKEN
    * MY_TELEGRAM_ID
    * PROXSY_SOCKS5
    
1. Создайте `.env` файл около `script.py`.
2. `.env` файл должен содержать:

```
DVMN_TOKEN = личный_токен_от_аккаунта_девмана
TELEGRAM_BOT_TOKEN = токен_вашего_телеграм_бота
MY_TELEGRAM_ID = ваш_телеграмм_айди
PROXSY_SOCKS5 = адрес_вашего_прокси
```

## 3. Как установить
Скачайте файл `requirements.txt` и положите его в корень проекта. Наберите в терминале:
`pip install -r requirements.txt`

## 4. Запуск
Либо через терминал `python script.py` либо через любую IDE ( в PyCharm, например, сочетание клавиш `Shift + F10`).