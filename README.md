# Telegram Kittybot
Адрес для примера в Telegram https://t.me/kitty_angel_bot

### Описание проекта
Бот в Телеграм можно создать для того, чтобы немного отдохнуть, переключить внимание, а где-то и посмеяться))<br>
Присылает рандомно фото разных котиков (приятных, забавных и прочих).

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/AngelNad/kittybot_prod.git
```

```
cd kittybot_prod
```
Cоздать файл kittybot_prod/.env со значением токена вашего бота в Телеграм:

```
TOKEN=...
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Запустить проект:

```
python3 kittybot.py
```

### Автор
Надежда Осипова
