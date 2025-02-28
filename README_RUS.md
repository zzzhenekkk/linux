# Операционные системы UNIX/Linux (Базовый)

Установка и обновление системы Linux. Основы администрирования.

## Оглавление

1. [Введение](#введение)
2. [Linux и администрирование](#linux-и-администрирование)
   - [Часть 1: Установка ОС](#часть-1-установка-ос)
   - [Часть 2: Создание пользователя](#часть-2-создание-пользователя)
   - [Часть 3: Настройка сети ОС](#часть-3-настройка-сети-ос)
   - [Часть 4: Обновление ОС](#часть-4-обновление-ос)
   - [Часть 5: Использование команды sudo](#часть-5-использование-команды-sudo)
   - [Часть 6: Установка и настройка службы времени](#часть-6-установка-и-настройка-службы-времени)
   - [Часть 7: Установка и использование текстовых редакторов](#часть-7-установка-и-использование-текстовых-редакторов)
   - [Часть 8: Установка и базовая настройка сервиса SSHD](#часть-8-установка-и-базовая-настройка-сервиса-sshd)
   - [Часть 9: Установка и использование утилит top, htop](#часть-9-установка-и-использование-утилит-top-htop)
   - [Часть 10: Использование утилиты fdisk](#часть-10-использование-утилиты-fdisk)
   - [Часть 11: Использование утилиты df](#часть-11-использование-утилиты-df)
   - [Часть 12: Использование утилиты du](#часть-12-использование-утилиты-du)
   - [Часть 13: Установка и использование утилиты ncdu](#часть-13-установка-и-использование-утилиты-ncdu)
   - [Часть 14: Работа с системными журналами](#часть-14-работа-с-системными-журналами)
   - [Часть 15: Использование планировщика заданий CRON](#часть-15-использование-планировщика-заданий-cron)

## Введение

Курс предоставляет базовые знания по установке, настройке и администрированию операционных систем семейства UNIX/Linux. Вы узнаете, как эффективно управлять системными ресурсами, настраивать сеть и сервисы, а также работать с системными журналами и планировщиком задач CRON.

## Linux и администрирование

### Часть 1: Установка ОС

Инструкции по установке операционной системы Linux на виртуальную машину или реальное оборудование, включая базовую настройку системы.

### Часть 2: Создание пользователя

Руководство по созданию и настройке учетных записей пользователей в системе.

### Часть 3: Настройка сети ОС

Настройка сетевых параметров, включая IP-адреса, DNS и шлюз по умолчанию.

### Часть 4: Обновление ОС

Пошаговое руководство по обновлению операционной системы и установке последних обновлений безопасности.

### Часть 5: Использование команды sudo

Настройка привилегий администратора с использованием команды `sudo`.

### Часть 6: Установка и настройка службы времени

Настройка времени системы и синхронизация с интернет-серверами времени.

### Часть 7: Установка и использование текстовых редакторов

Инструкции по установке и работе с текстовыми редакторами, такими как Vim и Nano.

### Часть 8: Установка и базовая настройка сервиса SSHD

Настройка удаленного доступа к системе через SSH.

### Часть 9: Установка и использование утилит top, htop

Мониторинг системных ресурсов с использованием утилит `top` и `htop`.

### Часть 10: Использование утилиты fdisk

Работа с разделами дисков с помощью утилиты `fdisk`.

### Часть 11: Использование утилиты df

Мониторинг свободного и занятого места на дисках с помощью утилиты `df`.

### Часть 12: Использование утилиты du

Анализ использования дискового пространства с помощью утилиты `du`.

### Часть 13: Установка и использование утилиты ncdu

Использование `ncdu` для анализа дискового пространства с улучшенным интерфейсом.

### Часть 14: Работа с системными журналами

Просмотр и анализ системных журналов для мониторинга работы системы.

### Часть 15: Использование планировщика заданий CRON

Настройка автоматического выполнения задач с использованием планировщика `CRON`.

## Обратная связь

Мы ценим вашу обратную связь по данному проекту. Пожалуйста, поделитесь своими мыслями и предложениями через [форму обратной связи](https://forms.yandex.ru/cloud/641817c002848f26a078c4a6/). Это поможет нам сделать обучение лучше.




# Операционные системы UNIX/Linux (Базовый).

Установка и обновления системы Linux. Основы администрирования.


## Contents
1. [Chapter I](#chapter-i)
2. [Chapter II](#chapter-ii) \
    2.1. [Linux](#linux)  
    2.2. [Администрирование](#администрирование)  
    2.3. [Виртуальные машины](#виртуальные-машины) 
3. [Chapter III](#chapter-iii) \
    3.1 [Установка ОС](#part-1-установка-ос)  
    3.2 [Создание пользователя](#part-2-создание-пользователя)  
    3.3 [Настройка сети ОС](#part-3-настройка-сети-ос)   
    3.4 [Обновление ОС](#part-4-обновление-ос)  
    3.5 [Использование команды  sudo](#part-5-использование-команды-sudo)  
    3.6 [Установка и настройка службы времени](#part-6-установка-и-настройка-службы-времени)  
    3.7 [Установка и использование текстовых редакторов](#part-7-установка-и-использование-текстовых-редакторов)  
    3.8 [Установка и базовая настройка сервиса SSHD](#part-8-установка-и-базовая-настройка-сервиса-sshd)   
    3.9 [Установка и использование утилит top, htop](#part-9-установка-и-использование-утилит-top-htop)   
    3.10 [Использование утилиты fdisk](#part-10-использование-утилиты-fdisk)   
    3.11 [Использование утилиты df](#part-11-использование-утилиты-df)    
    3.12 [Использование утилиты du](#part-12-использование-утилиты-du)    
    3.13 [Установка и использование утилиты ncdu](#part-13-установка-и-использование-утилиты-ncdu)    
    3.14 [Работа с системными журналами](#part-14-работа-с-системными-журналами)     
    3.15 [Использование планировщика заданий CRON](#part-15-использование-планировщика-заданий-cron)    


## Chapter I

![linux](misc/images/linux.png)

>От разработчиков: \
>Для полного погружения можешь на время чтения задания включить любимую джазовую композицию.

Планета Земля, США, штат Калифорния, Комптон, джаз клуб "Seb's", настоящее время.

`-` Ну что, Себастьян, ты же не думал, что я поверю, что ты позвал меня просто посидеть и отдохнуть? Ты не из тех, кто посреди рабочей недели станет писать старому товарищу, если тебе нечего сказать.

`-` От тебя никогда ничего не скрыть! Я думал перейти к делу более плавно, но раз ты столь проницателен...

`-` Хватит мне льстить, мне же интересно, к чему мы тут собрались.

`-` Дело в том, что я недавно влился в одну компанию разработчиков, которой нужен был администратор. Но вот беда: в качестве ОС они используют Linux.

`-` И ты, как уверенный пользователь Windows, хочешь разобраться в основах Linux'а, а заодно и администрирования?

`-` Именно! Насколько я помню, ты как раз разбираешься и в том, и в другом.

`-` Что же, тогда доставай свой ноутбук! Конечно я давно этим не занимался, но постараюсь помочь. Главное — успеть до закрытия клуба, иначе придётся продолжить завтра.

\> *Композиция заканчивается, музыка медленно утихает, вам приносят заказанные напитки*

\> *Пока Себастьян достаёт и включает свой ноутбук, Вы решаете рассказать небольшую историческую справку*


## Chapter II

### Linux
`-` История Linux начинается в 1991 году, когда финский аспирант и программист Линус Торвальдс стал разрабатывать ядро операционной системы для своего компьютера.

`-` Свои наработки он выложил на общедоступном сервере, и это стало ключевым событием в истории Linux. Сначала десятки, потом сотни и тысячи разработчиков поддержали его проект - общими усилиями на свет появилась полноценная операционная система.

`-` Первая официальная версия Linux 1.0 вышла в 1994 году. С самого начала и по сей день Linux распространяется как свободное программное обеспечение с лицензией GPL. Это значит, что исходный код операционной системы может увидеть любой пользователь - и не только увидеть, но и доработать его. Единственное условие - измененный, модифицированный код должен быть также доступен всем и распространяться по лицензии GPL. Это важно, так как дает возможность разработчикам использовать код и в то же время не бояться проблем из-за авторских прав.

`-` Сегодня Linux - самая известная и наиболее используемая операционная система с открытым исходным кодом. Как операционная система, Linux - это программное обеспечение, которое находится под всем другим программным обеспечением на компьютере, получая запросы от этих программ и передавая эти запросы на аппаратное обеспечение компьютера.

\> *Официантка приносит вам заказанные напитки, музыканты вновь начинают играть*

### Администрирование

`-` Администрирование - это, если не вдаваться в подробности, поддержка и улучшение работы всего компьютерного и офисного оборудования, периферийных устройств, сетевого подключения и т.д. При администрировании Linux большая часть работы протекает в терминале, поэтому стоит начать с использования базовых утилит.

\> *К этому моменту ноутбук Себастьяна загружается, и Вы видите ужасную картину: на нем даже не стоит нужная операционная система...*

\> *Чтобы не переустанавливать операционную систему Себастьяна, Вы решаете использовать виртуальную машину*

### Виртуальные машины

`-` Виртуальная машина (VM, ВМ) также, как и физические компьютеры, имеет ЦП, память, диски для хранения файлов и при необходимости может подключаться к Интернету. Отличие лишь в том, что компоненты вашего компьютера (аппаратная часть) материальны, а виртуальные машины существуют только в виде кода.

`-` Проще говоря, это виртуальный компьютер, на который можно устанавливать операционную систему и все сопутствующее программное обеспечение, при этом никаких изменений в Вашей основной операционной системе не будет.

`-` Виртуализация — это процесс создания программной (виртуальной) версии компьютера с выделенными ресурсами ЦП, памяти и хранилища, которые "заимствуются" у физического компьютера. Виртуальная машина — это компьютерный файл (образ), который действует как обычный компьютер.

`-` В свою очередь _VirtualBox_ - это программный продукт виртуализации, т.е. инструмент для создания виртуальных машин.

\> *Ещё некоторое количество полезной информации Вы захотели рассказать потом, а потому создаёте у Себастьяна на ноутбуке папку materials с полезной информацией*


## Chapter III

В качестве результата работы должен быть предоставлен отчет по выполненным задачам. В каждой части задания указано, что должно быть помещено в отчёт после её выполнения. Это могут быть скриншоты, какие-то данные и т.д.
- В репозиторий, в папку src, должен быть загружен отчёт с расширением .md.
- В отчёте должны быть выделены все части задания, как заголовки 2-го уровня.
- В рамках одной части задания всё, что помещается в отчёт, должно быть оформлено в виде списка.
- Каждый скриншот в отчёте должен быть кратко подписан (что показано на скриншоте).
- Все скриншоты обрезаны так, чтобы была видна только нужная часть экрана.

## Part 1. Установка ОС

`-` Что ж, давай наконец поставим этот Linux, -- Себастьян придвигает ноутбук поближе к вам.

`-` Да, самое время. Я видел отличную инструкцию по установке нужной нам версии на сайте *Linuxconfig*.

**== Задание ==**

##### Установить **Ubuntu 20.04 Server LTS** без графического интерфейса. (Используем программу для виртуализации - VirtualBox)

- Графический интерфейс должен отсутствовать.

- Узнайте версию Ubuntu, выполнив команду \
`cat /etc/issue.`
- Вставьте скриншот с выводом команды.

## Part 2. Создание пользователя

`-` Установленная система -- это хорошо, но вдруг ей будет пользоваться кто-то ещё? Сейчас научу тебя созданию нового пользователя.

**== Задание ==**

##### Создать пользователя, отличного от пользователя, который создавался при установке. Пользователь должен быть добавлен в группу `adm`.

- Вставьте скриншот вызова команды для создания пользователя.
- Новый пользователь должен быть в выводе команды \
`cat /etc/passwd`
- Вставьте скриншот с выводом команды.

## Part 3. Настройка сети ОС

`-` В нашем мире без интернета далеко не уедешь. Однако, поскольку мы хотим подготовить тебя к роли системного администратора, я покажу немного больше, чем просто настройку сети.

`-` Перед тем, как мы приступим, советую почитать про сетевые интерфейсы и DHCP.

**== Задание ==**

##### Задать название машины вида user-1  
##### Установить временную зону, соответствующую вашему текущему местоположению.  
##### Вывести названия сетевых интерфейсов с помощью консольной команды.
- В отчёте дать объяснение наличию интерфейса lo.  
##### Используя консольную команду получить ip адрес устройства, на котором вы работаете, от DHCP сервера. 
- В отчёте дать расшифровку DHCP.  
##### Определить и вывести на экран внешний ip-адрес шлюза (ip) и внутренний IP-адрес шлюза, он же ip-адрес по умолчанию (gw). 
##### Задать статичные (заданные вручную, а не полученные от DHCP сервера) настройки ip, gw, dns (использовать публичный DNS серверы, например 1.1.1.1 или 8.8.8.8).  
##### Перезагрузить виртуальную машину. Убедиться, что статичные сетевые настройки (ip, gw, dns) соответствуют заданным в предыдущем пункте.  

- В отчёте опишите, что сделали для выполнения всех семи пунктов (можно как текстом, так и скриншотами).
- Успешно пропинговать удаленные хосты 1.1.1.1 и ya.ru и вставить в отчёт скрин с выводом команды. В выводе команды должна быть фраза "0% packet loss".

## Part 4. Обновление ОС

`-` Ты спросишь меня: "Готова ли теперь система?". Не готова она совсем! Мы же ещё не обновили её до последней версии.

**== Задание ==**

##### Обновить системные пакеты до последней на момент выполнения задания версии.  

- После обновления системных пакетов, если ввести команду обновления повторно, должно появиться сообщение, что обновления отсутствуют.
- Вставить скриншот с этим сообщением в отчёт.

## Part 5. Использование команды **sudo**

`-` Как часто тебе в детстве говорили, что ты забыл сказать "волшебное" слово? Одним из таких "волшебных" слов было "пожалуйста". В Linux есть его аналог - _sudo_. Система не станет выполнять некоторые операции, пока не услышит "волшебное" слово.

**== Задание ==**

##### Разрешить пользователю, созданному в [Part 2](#part-2-создание-пользователя), выполнять команду sudo.

- В отчёте объяснить *истинное* назначение команды sudo (про то, что это слово - "волшебное", писать не стоит).  
- Поменять hostname ОС от имени пользователя, созданного в пункте [Part 2](#part-2-создание-пользователя) (используя sudo).
- Вставить скрин с изменённым hostname в отчёт.

## Part 6. Установка и настройка службы времени

`-` Хоть у нас сейчас и стоит правильное время, оно может быть таким не всегда. Чтобы не настраивать его каждый раз самим, существуют службы синхронизации времени.

**== Задание ==**

##### Настроить службу автоматической синхронизации времени.  

- Вывести время часового пояса, в котором вы сейчас находитесь.
- Вывод следующей команды должен содержать `NTPSynchronized=yes`: \
  `timedatectl show`
- Вставить скрины с корректным временем и выводом команды в отчёт.

## Part 7. Установка и использование текстовых редакторов 

`-` Думаю, мы готовы перейти к одному из самых страшных этапов. 

На висящей на стене карте мира вы указываете в сторону Нидерландов:

`-` Здесь Брам Моленар разгадал тайны гармонии и внутренней концентрации. \
Именно здесь, 2 ноября 1991 года, вышла первая версия VIM. \
Ты хочешь научиться работать в VIM?

`-` Да.

`-` Тогда я и есть твой мастер.

`-` Хорошо...

`-` Только не плачь.

`-` Ладно..

**== Задание ==**

##### Установить текстовые редакторы **VIM** (+ любые два по желанию **NANO**, **MCEDIT**, **JOE** и т.д.)  
##### Используя каждый из трех выбранных редакторов, создайте файл *test_X.txt*, где X -- название редактора, в котором создан файл. Напишите в нём свой никнейм, закройте файл с сохранением изменений.  
- В отчёт вставьте скриншоты:
  - Из каждого редактора с содержимым файла перед закрытием.
- В отчёте укажите, что сделали для выхода с сохранением изменений.
##### Используя каждый из трех выбранных редакторов, откройте файл на редактирование, отредактируйте файл, заменив никнейм на строку "21 School 21", закройте файл без сохранения изменений.
- В отчёт вставьте скриншоты:
    - Из каждого редактора с содержимым файла после редактирования.
- В отчёте укажите, что сделали для выхода без сохранения изменений.
##### Используя каждый из трех выбранных редакторов, отредактируйте файл ещё раз (по аналогии с предыдущим пунктом), а затем освойте функции поиска по содержимому файла (слово) и замены слова на любое другое.
- В отчёт вставьте скриншоты:
    - Из каждого редактора с результатами поиска слова.
    - Из каждого редактора с командами, введёнными для замены слова на другое.

## Part 8. Установка и базовая настройка сервиса **SSHD**

`-` Удобно иметь доступ от одного компьютера к другому по сети, правда? Но чтобы это было не только удобно, но и безопасно, стоит использовать сервис SSH.

**== Задание ==**

##### Установить службу SSHd.  
##### Добавить автостарт службы при загрузке системы.  
##### Перенастроить службу SSHd на порт 2022.  
##### Используя команду ps, показать наличие процесса sshd. Для этого к команде нужно подобрать ключи.
- В отчёте объяснить значение команды и каждого ключа в ней.
##### Перезагрузить систему.
- В отчёте опишите, что сделали для выполнения всех пяти пунктов (можно как текстом, так и скриншотами).
- Вывод команды netstat -tan должен содержать  \
`tcp 0 0 0.0.0.0:2022 0.0.0.0:* LISTEN`  \
(если команды netstat нет, то ее нужно установить)
- Скрин с выводом команды вставить в отчёт.
- В отчёте объяснить значение ключей -tan, значение каждого столбца вывода, значение 0.0.0.0.

## Part 9. Установка и использование утилит **top**, **htop**

`-` Если бы меня спросили, что полезного делают утилиты **top** и **htop**, я бы ответил одним словом - всё.

**== Задание ==**

##### Установить и запустить утилиты top и htop.  

- По выводу команды top определить и написать в отчёте:
  - uptime
  - количество авторизованных пользователей
  - общую загрузку системы
  - общее количество процессов
  - загрузку cpu
  - загрузку памяти
  - pid процесса занимающего больше всего памяти
  - pid процесса, занимающего больше всего процессорного времени
- В отчёт вставить скрин с выводом команды htop:
  - отсортированному по PID, PERCENT_CPU, PERCENT_MEM, TIME
  - отфильтрованному для процесса sshd
  - с процессом syslog, найденным, используя поиск 
  - с добавленным выводом hostname, clock и uptime  

## Part 10. Использование утилиты **fdisk**

`-` Теперь давай разберёмся, как получить информацию о жёстком диске. Специально для тебя я собрал пару примеров работы с утилитой fdisk.

**== Задание ==**

##### Запустить команду fdisk -l.

- В отчёте написать название жесткого диска, его размер и количество секторов, а также размер swap.

## Part 11. Использование утилиты **df** 

`-` Информацию о жёстком диске мы получили, но, зачастую, куда интереснее информация о дисковом пространстве, которую можно получить с помощью утилиты df.

**== Задание ==**

##### Запустить команду df.  
- В отчёте написать для корневого раздела (/):
  - размер раздела
  - размер занятого пространства
  - размер свободного пространства
  - процент использования
- Определить и написать в отчёт единицу измерения в выводе.  

##### Запустить команду df -Th.
- В отчёте написать для корневого раздела (/):
    - размер раздела
    - размер занятого пространства
    - размер свободного пространства
    - процент использования
- Определить и написать в отчёт тип файловой системы для раздела.

## Part 12. Использование утилиты **du**

`-` df - не единственный способ получить информацию о дисковом пространстве. Сейчас расскажу про ещё один.

**== Задание ==**

##### Запустить команду du.
##### Вывести размер папок /home, /var, /var/log (в байтах, в человекочитаемом виде)
##### Вывести размер всего содержимого в /var/log (не общее, а каждого вложенного элемента, используя *)

- В отчёт вставить скрины с выводом всех использованных команд.

## Part 13. Установка и использование утилиты **ncdu**

`-` Тебе, возможно, не очень понравился формат, в котором команда du выводит информацию. Я тебя прекрасно понимаю. Поэтому сейчас мы рассмотрим её улучшенную версию.

**== Задание ==**

##### Установить утилиту ncdu.
##### Вывести размер папок /home, /var, /var/log.

- Размеры должны примерно совпадать с полученными в [Part 12](#part-12-использование-утилиты-du).

- В отчёт вставить скрины с выводом использованных команд.

## Part 14. Работа с системными журналами

`-` Системному администратору иногда приходится просматривать события, происходившие в системе в недавнем прошлом. Для этого в Linux есть системные журналы.

**== Задание ==**

##### Открыть для просмотра:
##### 1. /var/log/dmesg
##### 2. /var/log/syslog
##### 3. /var/log/auth.log  

- Написать в отчёте время последней успешной авторизации, имя пользователя и метод входа в систему.
- Перезапустить службу SSHd.
- Вставить в отчёт скрин с сообщением о рестарте службы (искать в логах).

## Part 15. Использование планировщика заданий **CRON**

`-` Фух, наконец-то мы добрались до последней части моего долгого повествования. Сейчас я покажу программу, которая, помимо прочего, заметно упрощает периодический вызов других программ.

**== Задание ==**

##### Используя планировщик заданий, запустите команду uptime через каждые 2 минуты.
- Найти в системных журналах строчки (минимум две в заданном временном диапазоне) о выполнении.
- Вывести на экран список текущих заданий для CRON.
- Вставить в отчёт скрины со строчками о выполнении и списком текущих задач.

##### Удалите все задания из планировщика заданий.
- В отчёт вставьте скрин со списком текущих заданий для CRON.


💡 [Нажми тут](https://forms.yandex.ru/cloud/641817c002848f26a078c4a6/), **чтобы поделиться с нами обратной связью на этот проек**т. Это анонимно и поможет команде Продукта сделать твоё обучение лучше.
