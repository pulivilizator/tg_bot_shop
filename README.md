# Телеграм бот - магазин

#### Телеграм бот с админ панельлью Django, каталогом, корзиной, системой оплаты через сервис "Юкасса", инлайн режимом для FAQ, рассылкой из админ панели через Celery.

---

#### Для запуска переименуйте .env.example в .env, и укажите свои данные(Данные для подключения к базам данных можно не менять)
#### PAYMENT_TOKEN можно получить у bot father выбрав в качестве оплаты тестовую оплату Юкассы(/mybots -> выбрать бота -> payments -> ЮКасса -> Connect ЮКасса Test)
#### После запуска контейнеров все категории, товары, письма для рассылок и тд можно создать в админ панели

---

#### Использованные технологии:
- python3.12.3
- aiogram3.6.0
- aiogram-dialog
- Django5
- Celery
- PostgreSQL
- Redis
- Docker
