## Анализ БД крупного сервиса для чтения книг по подписке

**Цель исследования** - проанализировать базу данных, чтобы помочь сформулировать ценностное предложение для нового продукта.


**Задачи:**

- Посчитать, сколько книг вышло после 1 января 2000 года;
- Для каждой книги расчитать количество обзоров и среднюю оценку;
- Определить издательство, которое выпустило наибольшее число книг толще 50 страниц — так можно исключить из анализа брошюры;
- Определить автора с самой высокой средней оценкой книг  (среди книг с 50 и более оценками);
- Посчитать среднее количество обзоров от пользователей, которые поставили больше 50 оценок.

## Выводы

По итогам анализа базы данных было установлено:

1. 821 книга из нашего каталога была выпущена после 2000 года. Таким образом, в нашем сервисе вполне достаточное количество современной литературы и нашим подписчикам точно есть из чего выбирать


2. После подсчета количества обзоров и средней оценки каждой книги можно утверждать, что в нашем сервисе достаточное количество обзоров и оценок для того, чтобы нашим подписчикам было проше сделать свой выбор


3. В нашем каталоге больше всего книг толще 50 стр. у издательства Penguin Books, которое выпустило 42 книги. С ними у нас налажено наиболее плодотворное сотрудничество


4. Автор с самой высокой средней оценкой книг - Джоан Роулинг (около 4,3), что позволяет говорить, что книги о Гарри Поттере по-прежнему одни из самых любимых у наших подписчиков



5. Наконец, среднее количество обзоров от пользователей, которые поставили больше 50 оценок: 24.3. Таким образом, наши критики достаточно опытны в плане рекомендации контента, и подписчики при выборе книг могут смело опираться на их советы

## Ссылки
[**Просмотр тетрадки через nbviewer**](https://nbviewer.org/github/sashasepp/da_projects/blob/main/13_sql/13_sql.ipynb)
