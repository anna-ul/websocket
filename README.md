# Протокол WebSocket

Этот проект содержит демонстрацию работы протокола WebSocket.
В проекте есть сервер, написанный для NodeJS, и клиент. Приложение реализует чат. Сначала вам надо установить пакеты,
необходимые для работы сервера:

```shell
npm i
```

Теперь можно запустить сам сервер:
```shell
npm start
```

Приложение реализует чат. Когда отправляется сообщение в одном окне, оно приходит во все остальные.
Откройте `index.html` в разных окнах или даже браузерах.
Отправьте сообщение и убедитесь, что сообщение пришло во все окна/браузеры.

## Дополнительное задание [опционально]
Реализуйте возможность вводить имя пользователя, подписывать сообщения и отправлять сообщение конкретному адресату.
Обратите внимание: при регистрации нового пользователя его имя должно появляться у всех клиентов. Для этого при
регистрации отправляйте сообщение о появлении нового пользователя, а при отправке сообщения вместе с сообщением
передавайте имя отправителя.