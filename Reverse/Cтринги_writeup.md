Поскольку тематика реверс, пробуем запустить файл.
Просит ввести какое-то число, если не подходит ничего не выдает и программа закрывается.
Закидываем в иду, чтоб посмотреть что там происходит.
Находим функцию main
Ну тут и так понятно все, строки в base64, достаем их и декодируем
Последняя часть флага вызывается в функции перед system("pause");
Переходим в нее и видим последнюю строчку.

t8{r3v3rs3_3ngin33ring_is_coo1}
