# !DEPRECATED С 15 февраля VK закрыло API сообщений для пользователей. https://vk.com/dev/messages_api
# Общее
Хотели сохранить все свои сообщения в офлайн? Это программа для вас.
# Использование
1. Скачайте или склонируйте этот репозиторий
2. Установите (если еще не установлен) python3
3. Поставьте зависимости `pip install -r requirements.txt`
4. Создайте файл params.json такого вида (также можно использовать токен):
```JSON
{
    "app_id": "ВАШ_ID_ПРИЛОЖЕНИЯ_ВК",
    "user_login": "ЛОГИН",
    "user_password": "ПАРОЛЬ",
    "scope": "friends,messages,wall,status,photos"
}
```
5. Запустите `python3 main.py`. Закачка может продолжаться довольно долго (когда очень много сообщений), но прогресс сохраняется, так что программу можно остановить, а потом начать заново.
6. Результат - каждый диалог в красивом .html со стилями и JS для отображения вложений.
# Прочее
Качает не фотки (отностится и к другим вложениям), а их прямые ссылки (поскольку ВК не удаляет ничего с серверов). Если вам нужны полностью офлайн фотки - пишите свой скрипт.

Если написали скрипт или доделали функцию - киньте пулл. Также ставьте звезды если помогло.

The Software shall be used for Good, not Evil

