### Вопросы

#### Question 1
В конфиге prometheus указан один volume:
```
    volumes:
      - ./prometheus:/etc/prometheus/
```

Я проверил, значения метрик сохраняются между перезапусками контейнеров.
<br/>
Но в папке `./prometheus` лежит только 1 файл - файл с таргетами. 
<br/>
Где тогда хранится вся БД Прометея, если других volume-ов нет?


#### Question 2
Можешь показать, как ты в конфиге прометея задаешь параметр `--storage.tsdb.retention.time=1y`
<br/>
По дефолту Прометей 15 дней хранит метрики?