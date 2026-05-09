# Часть 1: Проектирование тестов для Яндекс.Самоката

[Задание 1: чек-лист](https://docs.google.com/spreadsheets/d/1PHdZlZyfySxDWuQs2lDZUW17S6EghfvKYV8QNpZ9KXA/edit?gid=943703744#gid=943703744)

[Задание 1: данные валидации](https://docs.google.com/spreadsheets/d/1PHdZlZyfySxDWuQs2lDZUW17S6EghfvKYV8QNpZ9KXA/edit?gid=1540465171#gid=1540465171)

[Задание 1: баги вне тестовой документации»](https://docs.google.com/spreadsheets/d/1PHdZlZyfySxDWuQs2lDZUW17S6EghfvKYV8QNpZ9KXA/edit?gid=1539613303#gid=1539613303)

[адание 2: тест-кейсы](https://docs.google.com/spreadsheets/d/1PHdZlZyfySxDWuQs2lDZUW17S6EghfvKYV8QNpZ9KXA/edit?gid=424948590#gid=424948590)

[Баг-репорты](https://docs.google.com/spreadsheets/d/1PHdZlZyfySxDWuQs2lDZUW17S6EghfvKYV8QNpZ9KXA/edit?gid=791488173#gid=791488173)


[Методичка по работе стенда](https://code.s3.yandex.net/qa/files/server_operation.pdf)

Проект содержит тестовую документацию и результаты ручного тестирования веб и мобильного приложений Яндекс.Самокат.

## Задание 1. Проектирование тестов и тестирование веб-приложения

1. Изучить [требования к веб-приложению](https://docs.google.com/document/d/1peAUFCm-Xr9miJ-YRCQjRMekcuU1_qbHAC2dm3PFK_I/edit?tab=t.0#heading=h.uwghzsu8i2st)

2. Составить чек-лист по экрану «Статус заказа» и занести результат на вкладку «Задание 1: чек-лист»

3. Для экрана «Сделать заказ» составить проверки на валидацию полей и занести результат на вкладку **«Задание 1: данные валидации»

4. Провести тестирование всей функциональности (кроме главной страницы / лендинга):
   * по получившимся чек-листам и таблицам
   * по остальным макетам и требованиям

   Результаты занести на вкладку «Задание 1: баги вне тестовой документации»

   [Макеты веб-приложения](https://www.figma.com/design/vHgTVzFac8zyxhMZ2o4b2m/web?node-id=0-1&p=f)
   
   [Инструкция по работе со статусами заказа](https://code.s3.yandex.net/qa/files/Instruktsiya_po_rabote_so_statusami_zakaza.pdf) 

5. Отмечать результаты тестирования:
   * `PASSED` — тест пройден успешно
   * `FAILED` — тест не пройден
     
   При статусе `FAILED`:
   * завести баг-репорт на вкладке «Баг-репорты»
   * вписать ID баг-репорта в соответствующую таблицу результатов

## Задание 2. Проектирование тестов для мобильного приложения

1. Изучить [требования к мобильному приложению](https://code.s3.yandex.net/qa/files/requirements_mob_app.pdf)
2. Спроектировать тест-кейсы:
   * на функциональность, выделенную жирным шрифтом в требованиях
   * на вёрстку по [макетам мобильного приложения](https://www.figma.com/design/kqLqPvSvjLVLomkdadkAnk/mobile) к этой функциональности.  
   
   Занести результат на вкладку «Задание 2: тест-кейсы» в Google-таблицах
