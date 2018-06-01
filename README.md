**FreeBSD 11.1-RELEASE** может быть загружена отсюда:

https://download.freebsd.org/ftp/releases/ISO-IMAGES/11.1/FreeBSD-11.1-RELEASE-amd64-disc1.iso 

### Установка

![Image 01](https://github.com/sshspb/freebsd-install/blob/master/images/installer-01.bmp) 

Выбор опции **Install** вызовет программу-установщик. 

![Image 02](https://github.com/sshspb/freebsd-install/blob/master/images/installer-02.bmp)

Использовать раскладку клавиатуры по умолчанию.

![Image 03](https://github.com/sshspb/freebsd-install/blob/master/images/installer-03.bmp)

Установка имени хоста, например: *machine3.example.com*

![Image 04](https://github.com/sshspb/freebsd-install/blob/master/images/installer-04.bmp)

Ничего из этого списка компонентов не нужно. 

![Image 05](https://github.com/sshspb/freebsd-install/blob/master/images/installer-05.bmp) 

Выбираем шаблонный (guided) способ разбиение дискового пространства

![Image 06](https://github.com/sshspb/freebsd-install/blob/master/images/installer-06.bmp) 

Выбираем весь диск

![Image 07](https://github.com/sshspb/freebsd-install/blob/master/images/installer-07.bmp) 

Вариант MBR, по умолчанию

![Image 08](https://github.com/sshspb/freebsd-install/blob/master/images/installer-08.bmp) 

Выражаем согласие, **Finish**

![Image 09](https://github.com/sshspb/freebsd-install/blob/master/images/installer-09.bmp) 

**Commit**

#### После установки

![Image 10](https://github.com/sshspb/freebsd-install/blob/master/images/installer-10.bmp) 

Вводим пароль для *root*

![Image 11](https://github.com/sshspb/freebsd-install/blob/master/images/installer-11.bmp) 

Сетевой интерфейс по умолчанию

![Image 12](https://github.com/sshspb/freebsd-install/blob/master/images/installer-12.bmp) 

**Yes**, использовать протокол IPv4

![Image 13](https://github.com/sshspb/freebsd-install/blob/master/images/installer-13.bmp) 

**No**, сервис DHCP не нужен,

![Image 14](https://github.com/sshspb/freebsd-install/blob/master/images/installer-14.bmp) 

Статическая настройка IPv4 на сетевом интерфейсе

![Image 15](https://github.com/sshspb/freebsd-install/blob/master/images/installer-15.bmp) 

**No**, Протокол IPv6 не нужен

![Image 16](https://github.com/sshspb/freebsd-install/blob/master/images/installer-16.bmp) 

Настройка Резолвера DNS

![Image 17](https://github.com/sshspb/freebsd-install/blob/master/images/installer-17.bmp) 

Нужен только sshd - Secure Shell (SSH) демон.

![Image 18](https://github.com/sshspb/freebsd-install/blob/master/images/installer-18.bmp) 

Ничего не надо

![Image 19](https://github.com/sshspb/freebsd-install/blob/master/images/installer-19.bmp) 

Добавить пользователя

![Image 20](https://github.com/sshspb/freebsd-install/blob/master/images/installer-20.bmp) 

Exit, **OK**

![Image 21](https://github.com/sshspb/freebsd-install/blob/master/images/installer-21.bmp) 

**No**, не желаем продолжать конфигурировать вручную

![Image 22](https://github.com/sshspb/freebsd-install/blob/master/images/installer-22.bmp) 

**Reboot**, желаем перезагрузку

При перезагрузке надо умудриться вынуть компакт-диск.

#### P.S.

При установке на виртуальную машину Oracle VM VirtualBox сеть заработала после уставки типа подключения адаптера "Сетевой мост" :

![Image vm-net](https://github.com/sshspb/freebsd-install/blob/master/images/vm-net.bmp)

#### P.P.S.

Перезагрузить FreeBSD
```
# shutdown -r now
```

Останов FreeBSD и отключение
```
# shutdown -p now
```

Предоставить право останавливать FreeBSD пользователю user_name
```
# pw groupmod operator -m user_name
```
