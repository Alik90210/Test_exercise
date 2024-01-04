### SQL запрос :page_with_curl:
1. В файле <a href ='https://github.com/Alik90210/Test_exercise/blob/main/SQL_request.txt'> SQL_request.txt </a> содержится SQL запрос, который ищет три машины в  bigquery-public-data.chicago_taxi_trips, получившие наибольшее количество чаевых в апреле 2022 года и формирует группировку по сумме чаевых этих трех машин по месяцам всей истории базы. Скачиваем файл bquxjob_6d2b83b2_18cd3fbc55e.csv нашего запроса  из базы.
   
### Преобразование в Pandas :hammer:
2. В файле <a href='https://github.com/Alik90210/Test_exercise/blob/main/Test_hhru.ipynb'> Test_hhru.ipynb </a> на языке Python 3.8 и c использованием библиотеки Pandas я вычисляю  как изменялась сумма чаевых в процентах в последующие месяцы по сравнению с предыдущим и добавляю новую колонку tips_change с данной информацией. Итерацию в самом SQL считаю делать нерационально.

### Результат :floppy_disk:
3. В итоге получился файл <a href='https://github.com/Alik90210/Test_exercise/blob/main/test_hhru_Kruglov_A.csv' test_hhru_Kruglov_A.csv </a>.

### Комментарии :speech_balloon:
4. Можно добавить стоблец taxi_id, для этого можно сделать все тоже самое для конкрентого taxi_id по отдельности (всего их 3) и собрать в общую талицу. 

### Мои контакты :love_letter:
5. Если я Вас заинтресовал, то пишите в телеграмм https://t.me/N9021010 или звоните +7 911 954 7650 (Алексей). Буду рад обратной связи).
