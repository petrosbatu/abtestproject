В репозитории файл AB_test.ipynb содержит ноутбук с выполненым анализом данных AB-тестирования. cookie_cats.txt - исходные данные
Этот набор данных включает результаты A/B-тестирования мобильной игры Cookie Cats, исследующего влияние перемещения начальных ворот в игре с уровня 30 на уровень 40. После установки игры игрокам были случайным образом назначены ворота либо на 30 уровне, либо на 40.
Имеются данные о 90 189 игроках, которые установили игру во время проведения AB-теста. Переменные:
- userid: уникальный номер, идентифицирующий каждого игрока.
- version: попал ли игрок в контрольную группу (gate_30 - ворота 30 уровня) или группу с перенесенными воротами (gate_40 - ворота 40 уровня).
- sum_gamerounds: количество игровых раундов, сыгранных игроком в течение первых 14 дней после установки.
- retention_1: вернулся ли игрок через 1 день после установки?
- retention_7: вернулся ли игрок через 1 день после установки?
