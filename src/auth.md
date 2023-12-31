# Авторизация

- /auth

На данную страницу перебрасываются пользователи, которые постучались на защищённый api, но в ответ получили код ответа 401(__UNAUTHORIZED__). 

Страница выглядит следующим образом:
![auth.png](..%2Fresource%2Fimage%2Fauth.png)

На заднем фоне проигрывается не большое по размеру видео на весь экран.

### Фон
Существует 4 видео. Выбор видео идёт в зависимости от времени года в настоящий момент. (Пока есть только одно видео по адресу: [forLoginPage.webm](..%2Fresource%2Fvideo%2FforLoginPage.webm)) пока всегда проигрывать это видео. В дальнейшем появятся остальные.

### Форма авторизации
Форма авторизации черного цвета с прозрачностью в 15%. Легкое загругление краев. 
Сверху написано "Доброго времени суток" - необходимо осуществить надпись, так же как и с фоновым видео, то есть времени суток: Доброго дня, Добрый вечер, Доброй ночи, Доброе утро.

### Используемый API
В данном примере при нажатии на кнопку "Получить Jwt" на сервер должен уйти POST запрос по адресу ("/api/auth/login") Информация по запросу описана в файле [api.yaml](..%2Fapi.yaml)

### Возможные корректировки
Все элементы данного макета могут подвергаться коррекции или прочим изменениям на усмотрение фронтэндера, если в этом есть глубокая необходимость.
Надпись на кнопке менять запрещено.
