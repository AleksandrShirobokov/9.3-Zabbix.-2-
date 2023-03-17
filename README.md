# 9.3 «Система мониторинга Zabbix. Часть 2»
# Александр Широбоков
## Задание 1. Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.
### Создаю шаблон
![Снимок экрана (48)](https://user-images.githubusercontent.com/69298696/225212696-78dea67c-b272-4d0a-a363-c59dd9335193.png)
### Также создаю два элемента данных для получения информации о загрузке процессора и памяти:
![Снимок экрана (49)](https://user-images.githubusercontent.com/69298696/225212968-93d81515-4834-4c83-aedf-f742e04abe12.png)
### Задание 2-3. Привязываю два шаблона к двум хостам (Shirobokov-1 & Shirobokov-2):
![Снимок экрана (50)](https://user-images.githubusercontent.com/69298696/225222677-263044d3-fdbb-4fba-974e-52b4db0ae40f.png)
## Задание 4. Создайте свой кастомный дашборд.
![Снимок экрана (52)](https://user-images.githubusercontent.com/69298696/225217221-b381af15-1aa0-4922-aa6b-3c1ebcea6ef7.png)
## Задание 5. Создать карту связи и показать выполнение триггера на разрыв соединения
### Связь есть:
![Снимок экрана (53)](https://user-images.githubusercontent.com/69298696/225221944-b721cadf-0a35-43ef-9ae6-92e392c51600.png)
### Связи нет:
![Снимок экрана (54)](https://user-images.githubusercontent.com/69298696/225222055-dfbbdb4f-8cb7-4d11-b0cb-31ea084d9a77.png)
## Задание 7. Доработайте Python-скрипт из лекции, создайте для него UserParameter и прикрепите его к созданному вами ранее шаблону.
### Скрипт:
![Снимок экрана (55)](https://user-images.githubusercontent.com/69298696/225817791-80c660a5-0a59-4d10-af30-05b6d9daba71.png)
### Итемы в работе:
![Снимок экрана (56)](https://user-images.githubusercontent.com/69298696/225817965-f604a88d-b77f-49c2-bd31-92d748c58295.png)
