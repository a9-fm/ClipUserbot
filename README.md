# Прошу не критиковать мой старющий код, оставил юзербота данного как память, благодаря нему я научился базовому пониманию в программировании 

## Clip Userbot - Самый простой юзербот для телеграм

## Создатель
* [Telegram](https://t.me/a9_fm)
* [Github](https://github.com/A9-FM)

## Для Termux (Android)
### Установка
```
pkg update -y ; pkg install python -y ; pkg install git -y ; curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py ; python3 get-pip.py ; rm get-pip.py ; git clone https://github.com/A9-FM/ClipUserbot ; cd ClipUserbot ; termux-wake-lock ; python3 bot.py
```

### При запуске
```
cd ClipUserbot ; termux-wake-lock ; python bot.py
```

---

## Для Windows
### Установка

Для установки скачиваем с оффициального сайта [Python](https://www.python.org/downloads/) самой новой версии (текущая 3.9.6)

Теперь запускаем установщик, и обьязательно ставим галочку на пункт
- [x] ADD PYTHON 3.9 to PATH

И ожидаем...

Теперь скачиваем ЮзерБота По этой [Ссылке](https://github.com/A9-FM/ClipUserbot/archive/refs/heads/main.zip)
Разархивируем файлы, и запускаем файл windows.bat

Всё)

### Запуск

Заходим в нашу папку и запускаем файл windows.bat

---

## Для Linux [Debian/Kali]
### Установка
Открываем терминал, и устанавливаем Python и также Git
```
apt install python3 git python3-pip
```

Теперь мы клонируем репозиторий коммандой
```
git clone https://github.com/A9FM/ClipUserbot.git
```

Переходим в директерию с юзерботом
```
cd ClipUserbot
```

И запускаем файл через Python
```
python3 bot.py
```

Готово)

### Запуск

Запускаем терминал и пишем такие комманды
```
cd ClipUserbot && python3 bot.py
```
