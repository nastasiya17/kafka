docker-compose up

Запуск ./start.sh

## Запросы: 

POST http://localhost:8080/person?add&login=123&first_name=Petr&last_name=Sidorov&age=54

POST http://localhost:8080/person?add&login=321&first_name=Sidr&last_name=Petrov&age=45

## Ответ: 

send to queue: 1 

send to queue: 2

## Запуск ./start_writer.sh

Ответ:

{"age":54,"first_name":"Petr","last_name":"Sidorov","login":"123"}

inserted:123

{"age":45,"first_name":"Sidr","last_name":"Petrov","login":"321"}

inserted:321




