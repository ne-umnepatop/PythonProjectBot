# ProjectBOT.py

Идея: бот в тг для записи на экскурсии по ВПД
Группа: Зелепугин Андрей, Хафизов Родион, Кутузов Михаил

## Функции бота:

Со стороны управляющего ботом: 
- запустить файл app.py

Со стороны студента: 
- написать боту свой табельный, ФИО, Группу
- написать время экскурсии, которую хочет посетить
- посмотреть статистику своих посещений

Со стороны организатора:
- отметить присутствующих


---
FOR STUFF ONLY:

Для проекта по питону первый курс

Плейлист с инструкцией:
https://www.youtube.com/watch?v=w4PCDo9C4tA&list=PLwVBSkoL97Q3phZRyInbM4lShvS1cBl-U

Если накрутим ошибок, пересмотрим: https://www.youtube.com/watch?v=fob8oQOjB2Q&list=PLwVBSkoL97Q3phZRyInbM4lShvS1cBl-U&index=7

Если захотим познать асинхронное программирование: https://www.youtube.com/watch?v=5BVdOs3nVKk&list=PLwVBSkoL97Q3phZRyInbM4lShvS1cBl-U&index=6


**Программа-минимум:**

Аккаунт студента:
1) записываться на экскурсии
2) отписываться от экскурсий
3) смотреть статистику своих посещений

Общие функции бота:
1) распределение студентов по экскурсиям
2) приём заявок студентов
3) подготовка статистики посещений для каждого студента

Аккаунт организатора:
1) Отмечать присутствие

**Программа-максимум:**

Общие функции бота:
1) приоритетность студентов с меньшим числом посещений;
2) приоритетность студентов с меньшим числом прогулов;
3) рейтинг экскурсий по интересности;
4) англоверсия и англорассылка;
5) если записан, но не придёт, то ему будет ограничен доступ к самым интересным экскурсиям;
6) описание экскурсий;
7) связь с оргом;
8) статистика посещений;
9) задержка перед записью (уведомление заранее)
10) поддержка отзывов об экскурсии (прим: звёзды)
11) запись на экскурсию “с отсевом”


аккаунт организатора: 

1) добавлять экскурсии с ограниченным количеством мест + спрашивать необходимость трансфера
2) журнал ака учет посещений
3) перераспределие людей в ручном порядке
4) если у чела уже 2 экскурсии то отдавать предпочтение в записи другим
5) чтение отзывов об экскурсии


аккаунт студента:
1) записываться на экскурсии
2) отписываться от экскурсий
3) смотреть статистику своих посещений
4) график (цифра) вероятности попадания на след. экскурсию (?)
5) уведомление за 2 дня
6) написание отзывов об экскурсии


**Требования**

| Требование                                                                                | :-1: | :+1: |
|-------------------------------------------------------------------------------------------|------|------|
| Оформление по PEP8                                                                        | -3 |4|
| Соблюдение принципа DRY                                                                   |-2|4|
| Наличие коммитов от всех участников проекта                                               | -3 |4|
| Наличие читаемых сообщений коммита, отображающих суть изменений                           |0|2|
| Использование системы докуметирования исходного кода (например, Doxygen)                  |0|4|
| Наличие файла README.md с коротким описанием программы (что делает, как запустить и т.д.) |-1|2|
| Наличие wiki-страницы с документаций и описанием программы                                |0|2|
| Использование функций                                                                     |-1|2|
| Использование классов                                                                     |0|4|
| Использование наследования                                                                |0|2|
| Оригинальность темы                                                                       |0|5|
| Полнота реализации                                                                        |0|5|
 Итого                                                                                     |-10|40|