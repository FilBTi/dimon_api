# dimon_api

Чтобы запустить проект нужно в командной строке написать npm i

Потом нужно будет в корне файла добавить файл .env и в него написать PORT = 3000 (Порт можешь выбрать любой другой)

И затем в командной строке написать npm start

Должен запустится сервер, в командной строке пропишется хост с портом, который указал в env файле 

GET - запросы
- http://localhost:PORT/users/ - покажет всех юзеров
- http://localhost:PORT/users/2 - вставить цивру, чтобы по id найти пользователя
- http://localhost:PORT/currency/ - показывает все валюты
- http://localhost:PORT/history/1 - покажет как менялся курс валюты с времененем
  
