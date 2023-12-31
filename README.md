# Kittygram
 Kittygram - это веб-приложение для обмена фотографиями и изображениями с милыми котиками. Пользователи могут загружать, просматривать и комментировать фотографии котиков, делиться ими с другими пользователями и наслаждаться милыми изображениями.
 
## Требования
- AngularJS-powered HTML5 Markdown editor.
- Python 3.8 или выше
- Django 3.2 или выше
- PostgreSQL 10 или выше (можно использовать другую базу данных, но для проекта используется PostgreSQL)
- Node.js и npm (для сборки фронтенд-части)

## Как использовать
Для доступа к административной панели, перейдите по адресу http://localhost:8000/admin/ и введите учетные данные созданного административного пользователя.
Чтобы загрузить фотографии котиков, зарегистрируйтесь или войдите в систему.
После авторизации вы сможете просматривать фотографии котиков, добавлять свои собственные фотографии, комментировать их и ставить лайки.

## Трудности 
При разработке особое внимание уделялось конфигурационным файлам. Так как на сервере одновременно работают два проекта нужно верно перераспределить порты и правильно запустить контейнеры. Кроме того сервер обладает ограниченным количеством памяти, поэтому перед деплоем нужно очищать кеш. 

## Настройки
Все настройки Django находятся в файле settings.py.
Переменные окружения, такие как секретный ключ (SECRET_KEY), разрешенные хосты (ALLOWED_HOSTS), настройки базы данных и другие, должны быть установлены в файле .env.

 ## Автор
Kittygram разработан Dubldum. Вы можете связаться со мной по электронной почте khaishbashev.david@gmail.com, или на GitHub: github.com/dubldum.


