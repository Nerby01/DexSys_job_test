Файловая база создана на версии платформы 8.3.24.1342

Описание задач:

Задача 1: 
Дана заполненная таблица значений, состоящая из 3-х колонок: «Дата» (тип «Дата»), «Время» (тип «Строка:8») и «Сумма» (тип «Число»). 
Необходимо удалить из таблицы все строки, не относящиеся к периоду с 10 утра до 19 вечера будних дней. 
   
Задача 2: 
У справочника ФизЛица есть реквизит НашКлиент булевого типа. 
Необходимо, чтобы при установленном флажке в форме списка, помимо самого флажка, в отдельной колонке отображалась надпить «Это хорошо» зелеными буквами, а при снятом — «Это нужно менять» красными. 
 
Задача 3: 
В справочнике ЮрЛица есть реквизит ГоловнаяОрганизация: Справочник.ЮрЛица, что позволяет построить древовидную филиальную структуру (в филиале заполнена головная организация). 
При этом максимальное количество уровней иерархии 2 (т.е. головная организация -> филиал).
Внимание: именно реквизит и только один. 
Также есть регистр сведений РеквизитыЮрЛиц в котором хранятся ИНН юр. лиц. 
Значение ИНН может меняться в течение месяца несколько раз. 
Дубли ИНН возможны только в рамках филиальной структуры (т.е. у ЮЛ одной головной организации могут быть одинаковые ИНН или одинаковый ИНН с головной организацией). 
Необходимо предусмотреть проверки добавления / изменения и удаления данных по ИНН, а также изменения иерархии, которые будут контролировать отсутствие дублей. 
При решении обязательно учитывать периодичность и историчность данных о реквизитах.