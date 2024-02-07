# Анализ товарного предложения персональных компьютеров в онлайн-магазине
## Кейс
К нам обратился клиент, который занимается сборкой и продажей персональных компьютеров (за исключением мини-ПК и моноблоков). В связи с ростом популярности интернет-магазинов, таких как Wildberries, Ozon, OnlineTrade и т. п., за последние несколько лет, а также с целью привлечения большего числа клиентов при одновременном снижении затрат на содержание собственного магазина, доставку и рекламу товаров он планирует выйти на онлайн-рынок. В связи с этим клиент хотел бы узнать, от чего зависит цена, а также популярность персональных компьютеров, выкладываемых на онлайн-площадках, чтобы в дальнейшем планировать к сборке востребованные по техническим характеристикам компьютеры и продавать их по конкурентной цене.
Специалистом по сбору данных был выгружен файл в формате csv с одного из популярных онлайн-магазинов, содержащий информацию о товарах категории «Компьютеры и моноблоки».
## Цель анализа 
Выявить и изучить факторы, влияющие на цену и популярность компьютеров, представленных в интернет-магазине
## Основные результаты
- Средняя цена по всем представленным позициям 67 850 руб. Средняя цена среди позиций, по которым есть продажи 57 437 руб;
- Связь между ценой и количеством продаж обратная - чем выше цена, тем меньше количество продаж;
- Самыми продаваемыми являются ПК с ценами 30-40 т.р;
- Самые дорогие ПК с процессорами Intel Core i5/10 ядер и Intel Core i7/12 ядер;
- ПК с видеопроцессорами NVIDIA дороже других - больше половины из них стоит дороже 70 000 руб. 75% компьютеров с видеопроцессором Intel дешевле 30 000 руб., а с видеопроцессором AMD - дешевле 40 000 руб;
- Медианная цена на ПК с типом оперативной памяти DDR3 около 24 000, а с DDR4 около 70 000 руб;
- Средняя цена ПК с SSD 52 140 руб., у ПК с HDD 23 400 руб., у ПК с обоими дисками 77 310 руб;
- Топ процессоров: AMD Ryzen 5 (6 ядер), Intel Core i5 (6 ядер), Intel Core i3 (4 ядра), Intel Core i7 (4 ядра), Intel Pentium (2 ядра);
- Топ видеопроцессоров: AMD Radeon Vega 7, NVIDIA GeForce GT 1030, Intel HD Graphics, NVIDIA GeForce GTX 1660, NVIDIA GeForce RTX 3050;
- Впродажах ПК с DDR4 в 3.5 раза больше,чем DDR3.
- Самым популярным объемом оперативной памяти является 16Гб,затем идут 8Гб, 32Гб и  Гб.
- У 82 % проданных ПК в качестве накопителя стоит SSD, у 16% оба накопителя. У 2%
только HDD.
- Самый продаваемый объем жесткого диска - 500 Гб. Затем 250 Гб.
## Инструменты проекта
- Python
- Pandas
- Matplotlib


[Первый проект](https://github.com/chegrincova/portfolio/tree/main/01%20-%20First%20Project)

[Второй проект](https://github.com/chegrincova/portfolio/tree/main/02%20-%20Second%20Project)
