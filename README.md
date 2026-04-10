# DIGITALLY.TJ (Django)

Полноценный интернет-магазин компьютерной техники на Django + Django Templates + HTMX.

## Что реализовано

- Apps: `products`, `users`, `orders`, `cart`
- Каталог с фильтрами и поиском
- Страница товара + добавление в корзину
- Корзина с изменением количества и удалением (через HTMX без перезагрузки)
- Регистрация, логин, личный кабинет
- Оформление заказа и история заказов
- Админ-панель для управления категориями, товарами, заказами
- SQLite на старте, настроены `static` и `media`

## Запуск

1. Установить зависимости:

```bash
pip install -r requirements.txt
```

2. Применить миграции:

```bash
python manage.py migrate
```

3. Заполнить каталог тестовыми категориями/товарами:

```bash
python manage.py seed_store
```

4. Создать администратора:

```bash
python manage.py createsuperuser
```

5. Запустить сервер:

```bash
python manage.py runserver
```

## Админка

Откройте: `http://127.0.0.1:8000/admin/`

В админке доступны:
- CRUD категорий (добавление/редактирование/удаление)
- CRUD товаров
- Добавление до 3+ URL-изображений для каждого товара

## Telegram интеграция заказов

Чтобы новые заказы отправлялись в Telegram-бот:

1. Создайте бота через `@BotFather`
2. Узнайте `chat_id` (через `getUpdates` или специального бота)
3. Перед запуском сервера задайте переменные окружения:

```bash
set TELEGRAM_BOT_TOKEN=your_bot_token
set TELEGRAM_CHAT_ID=your_chat_id
python manage.py runserver
```
