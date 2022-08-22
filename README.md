# Api_final

### Описание:
API для Yatube - социальной сети, предоставляющей пользователям возможность создать учетную запись, публиковать посты, подписываться на любимых авторов и отмечать понравившиеся записи. Доступен только аутентифицированным пользователям (аутентификация осуществляется по токену TokenAuthentication). Авторизованный пользователь может изменять и удалять свои записи, для неавторизованных пользователей доступно только чтение.

### Стек технологий:
Python, Django, DRF, SimpleJWT


### Установка
Клонировать репозиторий и перейти в него в командной строке:
git clone https://@github.com/comdastim/api_final_yatube.git

Перейти в yatube_api:
cd yatube_api

Cоздать и активировать виртуальное окружение:
python3 -m venv env
source env/bin/activate

Установить зависимости из файла requirements.txt:
python3 -m pip install --upgrade pip
pip install -r requirements.txt

Выполнить миграции:
python3 manage.py migrate

Запустить проект:
python3 manage.py runserver
