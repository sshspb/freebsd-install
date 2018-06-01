**FreeBSD 11.1-RELEASE** может быть загружена отсюда:

https://download.freebsd.org/ftp/releases/ISO-IMAGES/11.1/FreeBSD-11.1-RELEASE-amd64-disc1.iso 

### Установка

Выбор вариантов работы установочного носителя
![Image 01](https://github.com/sshspb/freebsd-install/blob/master/images/installer-01.bmp) 

Выбор опции `<Install>` вызовет программу-установщик. 

Выбор раскладки клавиатуры 
![Image 02](https://github.com/sshspb/freebsd-install/blob/master/images/installer-02.bmp)

Использовать раскладку клавиатуры по умолчанию.

Установка имени хоста
![Image 03](https://github.com/sshspb/freebsd-install/blob/master/images/installer-03.bmp)

Имя хоста, например: machine3.example.com

Выбор устанавливаемых компонентов
![Image 04](https://github.com/sshspb/freebsd-install/blob/master/images/installer-04.bmp)

Нам ничего из этого списка не понадобится. 

Выбор способа разбиения дискового пространства
![Image 05](https://github.com/sshspb/freebsd-install/blob/master/images/installer-05.bmp) 

Выбираем шаблонное (guided) разбиение

Выбор всего диска или раздела
![Image 06](https://github.com/sshspb/freebsd-install/blob/master/images/installer-06.bmp) 

Выбираем весь диск

Выбор схемы разделов
![Image 07](https://github.com/sshspb/freebsd-install/blob/master/images/installer-07.bmp) 

Вариант MBR, по умолчанию

Создаваемые разделы
![Image 08](https://github.com/sshspb/freebsd-install/blob/master/images/installer-08.bmp) 

Выражаем согласие, <Finish>

Последнее предупреждение
![Image 09](https://github.com/sshspb/freebsd-install/blob/master/images/installer-09.bmp) 

<Commit>

#### После установки

Cуперпользователь root
![Image 10](https://github.com/sshspb/freebsd-install/blob/master/images/installer-10.bmp) 

Вводим пароль для root

Выбор сетевого интерфейса
![Image 11](https://github.com/sshspb/freebsd-install/blob/master/images/installer-11.bmp) 

По умолчанию

Использовать протокол IPv4
![Image 12](https://github.com/sshspb/freebsd-install/blob/master/images/installer-12.bmp) 

<Yes>

Сервис DHCP
![Image 13](https://github.com/sshspb/freebsd-install/blob/master/images/installer-13.bmp) 

Не нужен, <No>

Статическая настройка IPv4 на сетевом интерфейсе
![Image 14](https://github.com/sshspb/freebsd-install/blob/master/images/installer-14.bmp) 

Примерно так

Протокол IPv6
![Image 15](https://github.com/sshspb/freebsd-install/blob/master/images/installer-15.bmp) 

Не нужен, <No>

Настройка Резолвера DNS
![Image 16](https://github.com/sshspb/freebsd-install/blob/master/images/installer-16.bmp) 

Примерно так

Дополнительные сетевые сервисы
![Image 17](https://github.com/sshspb/freebsd-install/blob/master/images/installer-17.bmp) 

Нужен только sshd - Secure Shell (SSH) демон.

Что то непонятное
![Image 18](https://github.com/sshspb/freebsd-install/blob/master/images/installer-18.bmp) 

Ничего не надо

Добавление пользователей
![Image 19](https://github.com/sshspb/freebsd-install/blob/master/images/installer-19.bmp) 

Тут всё понятно

Exit
![Image 20](https://github.com/sshspb/freebsd-install/blob/master/images/installer-20.bmp) 

<OK>

Желаете продолжить конфигурировать вручную?
![Image 21](https://github.com/sshspb/freebsd-install/blob/master/images/installer-21.bmp) 

<No> 

Желаете перезагрузку?
![Image 22](https://github.com/sshspb/freebsd-install/blob/master/images/installer-22.bmp) 

<Reboot>

При перезагрузке надо умудриться вынуть компакт-диск.
