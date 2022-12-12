Чтобы получить token
(Опционально) Открываем DevTools в браузере и на вкладке Network включаем троттлинг.
Переходим по ссылке https://oauth.yandex.ru/authorize?response_type=token&client_id=23cabbbdc6cd418abb4b39c32c41195d
Авторизуемся при необходимости и предоставляем доступ
Браузер перенаправит на адрес вида https://music.yandex.ru/#access_token=AQAAAAAYc***&token_type=bearer&expires_in=31535645. Очень быстро произойдет редирект на другую страницу, поэтому нужно успеть скопировать ссылку.
изображение
Ваш токен, то что находится после access_token.