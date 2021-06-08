### Настройка конфига
Конфиг должен выглядеть вот так:
```js
{
	"tokens": [ // Массив с токенами, за место них вставляем полученные
		"token...",
		"token...",
		"token..."
	],
	"owner_id": [540629911], // Айди пользователей, кому будут крутиться сообщения
	"cd": 15000 // Раз во сколько миллисекунд будут создаваться беседы
}
```
### Запуск
```
Открываем командную строку, переходим в папку со скриптом и вводим npm i
В отрытой cmd запускаем скрипт командой node app.js и наслаждаемся накруткой сообщений
```

![alt text](https://i.imgur.com/1B3rMBJ.png)
