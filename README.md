# test_celebrator
Тестовое задание для СоларЛаб

В корневой директории находится файл БД PersonsDB с тестовыми данными.

Реализованные функции:
1. Списки:
- полный список всех ДР
- пагинация
- сортировка по каждому критерию (Имя, Возраст, Дата)
- поиск (пагинация и сортировка его результатов)
- выделение прошедших ДР (opacity 0.5)
- список ближайших ДР за 30 дней
- отметка, если ДР сегодня

2. Данные:
- хранение данных в БД
- добавление ДР (имя и дата - обязательные поля, фото - необязательное)
- редактирование ДР
- удаление ДР
- детальная информация

3. Фото
- хранение фото на сервере, используя нейминг с помощью Guid
- удаление фото с сервера при удалении ДР
- изменение размера фото при загрузке (до ширины в 300 пикслей, высота скейлится)
