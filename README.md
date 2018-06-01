FreeBSD 11.1-RELEASE может быть загружена отсюда:
https://download.freebsd.org/ftp/releases/ISO-IMAGES/11.1/FreeBSD-11.1-RELEASE-amd64-disc1.iso 

Установка

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

!(https://github.com/sshspb/freebsd-install/blob/master/images/installer-01.bmp) Выбор вариантов работы установочного носителя
Выбор опции [ Install ] вызовет программу-установщик. 

installer-02.bmp Выбор раскладки клавиатуры 
Будем использовать раскладку клавиатуры по умолчанию.

installer-03.bmp Установка имени хоста
Имя хоста, например: machine3.example.com

installer-04.bmp Выбор устанавливаемых компонентов
Нам ничего из этого списка не понадобится. 

installer-05.bmp Выбор способа разбиения дискового пространства
Выбираем шаблонное (guided) разбиение

installer-06.bmp Выбор всего диска или раздела
Выбираем весь диск

installer-07.bmp Выбор схемы разделов
Вариант MBR, по умолчанию

installer-08.bmp Создаваемые разделы
Выражаем согласие, <Finish>

installer-09.bmp Последнее предупреждение
<Commit>

После установки

installer-10.bmp Cуперпользователь root
Вводим пароль для root

installer-11.bmp Выбор сетевого интерфейса
По умолчанию

installer-12.bmp Использовать протокол IPv4
<Yes>

installer-13.bmp Сервис DHCP
Не нужен, <No>

installer-14.bmp Статическая настройка IPv4 на сетевом интерфейсе
Примерно так

installer-15.bmp Протокол IPv6
Не нужен, <No>

installer-16.bmp Настройка Резолвера DNS
Примерно так

installer-17.bmp Активирование дополнительных сетевых сервисов
Нужен только sshd - Secure Shell (SSH) демон.

installer-18.bmp Что то непонятное
Ничего не надо

installer-19.bmp Добавление пользователей

installer-20.bmp Exit
<OK>

installer-21.bmp Желаете продолжить конфигурировать вручную?
<No> 

installer-22.bmp Желаете перезагрузку?
<Reboot>

При перезагрузке надо умудриться вынуть компакт-диск.
