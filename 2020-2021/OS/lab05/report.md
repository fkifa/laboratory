---
# Front matter
lang: ru-RU
title: "Лабораторная работа №5"
subtitle: "Операционные системы"
author: "Колосова Кристина Александровна"
---

# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Выполнение лабораторной работы

1. Определила имя домашнего каталога  (рис. - @fig:001)

![имя домашнего каталога](https://sun9-3.userapi.com/impg/5AoJwjbVtjYt1z2dJtI61xTYdH0fNbrpiaiXCQ/aVZcYUAnQqY.jpg?size=290x61&quality=96&sign=1dfc406d2d0f85d2f9b4e47f3315ca25&type=album)

{#fig:001 width=100%}

2. Выполнение ряда действий:

2.1. Перешла в каталог /tmp с помощью команды cd  (рис. - @fig:002)

Команда cd используется для перемещения по файловой системе операционной системы типа Linux.

![Переход в /tmp и просмотр содержимого](https://sun9-34.userapi.com/impg/Q_ygLriis3MO5WAPwZyMUHF-5lLsljAA59qYow/2XwqQpjk0ZU.jpg?size=727x269&quality=96&sign=ad2e8cde9440231e2415caad370f9d77&type=album)

2.2. Вывела на экран содержимое каталога /tmp командой ls с различными опциями. (рис. - @fig:003)

Команда ls используется для просмотра содержимого каталога

Разница в выводимой на экран информации:

-ls -a - отображает все файлы, включая скрытые (это те, перед именем которых стоит точка)

-ls -r - обратный порядок сортировки

![просмотр содержимого разными способами](https://sun9-67.userapi.com/impg/kGj5A6zqDo4JV-nMn_cyUaqvUNs9teGSMwQp4A/RJlkMcmej34.jpg?size=674x498&quality=96&sign=9ffbeb5abd5c511241cfce0154bd5c64&type=album)

{#fig:003 width=80%}

2.3. Определите, есть ли в каталоге /var/spool подкаталог с именем cron? (рис. - @fig:004)

Так же перешла в этот каталог с помощью cd с указанием пути, значит он есть.

![подкаталог cron](https://sun9-15.userapi.com/impg/yr7rFq-LhpvsskV_VxmI6EO83dh-pP-UU1mVOw/l0RTnjNtZN4.jpg?size=454x39&quality=96&sign=991c90b52b46471c87674680bf8fef31&type=album)

{#fig:004 width=100%}

2.4. Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Определите, кто является владельцем файлов и подкаталогов? (рис. - @fig:005)

владелец - kolosovaka.

![домашний каталог](https://sun9-17.userapi.com/impg/GRfmhIzKVAyogIvmeuUU_doOcO44qkHJZRyrxA/m1xIV3cZnuk.jpg?size=620x259&quality=96&sign=62f54b94722dc7c3adf1eddece272a0d&type=album)

{#fig:005}

3. Выполнение ряда действий

3.1.В домашнем каталоге создаю новый каталог с именем newdir. (рис. - @fig:006)

Команда mkdir используется для создания каталогов. --parents (или -p) — создание каталога вместе с родительскими по отношению
к нему каталогами.

3.2. В каталоге ~/newdir создаю новый каталог с именем morefun. (рис. - @fig:006)

![создание newdir и morefun](https://sun9-67.userapi.com/impg/v9t482vYDEBGe02RQOy8P_gOgmfsic4ImAhplg/55K2cQMmnKw.jpg?size=446x57&quality=96&sign=bf9f5c7fc2d4c701da07bb963ec15e09&type=album)

{#fig:006 width=100%}

3.4. Пробую удалить ранее созданный каталог ~/newdir командой rm. (рис. - @fig:008)

Каталог не был удален, так как rm используются для удаления файлов, а для каталогов - rm -r или rmdir, если каталог пустой.

3.5. Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли каталог удалён. (рис. - @fig:008)

да, удален!

![пункты 3.4 и 3.5](https://sun9-37.userapi.com/impg/2ag9C7NIx5zkRyQuiV6NYZDeqqD7qS7akfRRpg/a2t_-CHsoeo.jpg?size=603x291&quality=96&sign=c9786a4dab367c45abda2127e60b4f63&type=album)

{#fig:008 width=100%}

4. С помощью команды man опреляю, какую опцию команды ls нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него. (рис. - @fig:009)

Опция -R.

![опция ls для просмотра содержимого подкаталогов](https://sun9-76.userapi.com/impg/VNk_OA9-55Iyvx7m39khUumtIePbb3_a75gYwQ/Oh0tnrZX6LA.jpg?size=398x57&quality=96&sign=23288c368e74ea9e696465303833134d&type=album)

{#fig:009 width=100%}

5. Определите набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого
каталога с развёрнутым описанием файлов. (рис. - @fig:010)

Это опции -l и -t.

![опции ls для сортировки по времени](https://sun9-55.userapi.com/impg/eBlCQjRxBg4SQiNYnFzA6eCugNJVBLLZrG2x3Q/8nv9Iu0fvMw.jpg?size=440x101&quality=96&sign=c45de443fb4cabcd4094599bfde45555&type=album)

{#fig:010 width=100%}

6. Используйте команду man для просмотра описания следующих команд: cd, pwd,
mkdir, rmdir, rm. Поясните основные опции этих команд.

Команда man используется для просмотра (оперативная помощь) в диалоговом режиме руководства (manual) по основным командам операционной системы типа Linux.

***cd*** - нет справочной таблицы (рис. - @fig:011)

![man cd](https://sun9-27.userapi.com/impg/fKqR9UcgjjWHojIwrbWAeTviQSIDIMWUuGNyPQ/lW1oXchDVfM.jpg?size=312x56&quality=96&sign=9d0b93db5259f5831a6c15c2110aaa64&type=album)

{#fig:011 width=100%}

***pwd***

L - Не разыменовывает символические ссылки. Если путь содержит символические ссылки, то выводит их без преобразования в исходный путь.

P - Преобразовывает символические ссылки в исходные имена. Если путь содержит символические ссылки, то они будут преобразованы в названия исходных директорий, на которые указывают.
 
***mkdir***

p - создает все директории, которые указаны внутри пути. Если какая-либо директория существует, то предупреждение об этом не выводится.

v - выводить сообщение о каждой создаваемой директории.
 
***rmdir***

v - выводит диагностику на каждый процесс с каталогами

s - удаляет все что внутри каталога включительно
 
***rm***

r - рекурсивно удаляет всё что есть в каталоге

i - выводит запрос на подтверждение удаления каждого файла

7. Используя информацию, полученную при помощи команды history, выполните
модификацию и исполнение нескольких команд из буфера команд. (рис. - @fig:012) (рис. - @fig:013)

Для вывода на экран списка ранее выполненных команд используется команда history. Выводимые на экран команды в списке нумеруются. К
любой команде из выведенного на экран списка можно обратиться по её номеру в
списке, воспользовавшись конструкцией !<номер_команды>.

Можно модифицировать команду из выведенного на экран списка при помощи
следующей конструкции:
!<номер_команды>:s/<что_меняем>/<на_что_меняем>

![модификация и исполнение одной команды](https://sun9-2.userapi.com/impg/hpc5CrJNFcDhkagSwpCGr17iAxtOcT2A7OAZYg/LDX7lUBywfo.jpg?size=517x258&quality=96&sign=e8424e1482d5143e1305fad3a2bb63a0&type=album)

{#fig:012 width=100%}


![модификация и исполнение другой команды](https://sun9-3.userapi.com/impg/xkddSn74iSEA7BZ0pfHzrw4WIyMb-pVda0NwYA/9TOcctTYQNw.jpg?size=567x321&quality=96&sign=eab2be9b2de1344afcaf0423751368d9&type=album)

{#fig:013 width=100%}

#Контрольные вопросы

1. Что такое командная строка? - это специальная программа, которая позволяет управлять компьютером путем прямого воздействия на ядро ОС от ввода текстовых команд с клавиатуры.


2. При помощи какой команды можно определить абсолютный путь текущего каталога? - при помощи команды pwd. Например pwd ~/ - абсолютный пусть домашнего каталога


3. При помощи какой команды и каких опций можно определить только тип файлов и их имена в текущем каталоге? - c помощь команды ls и ключа -F. Например ls -F


4. Какие файлы считаются скрытыми? Как получить информацию о скрытых файлах? - Файл считается скрытым, если его название начинается с «.». Например, «.myfile». Обычно такие файлы используются приложениями для хранения настроек, конфигураций и другой информации, которую нужно скрыть от пользователя. Чтобы увидеть скрытые файлы можно использовать команду ls с ключом -a. Для дополнительных данных можно использовать дополнительные ключи, например ls -aF


5. При помощи каких команд можно удалить файл и каталог? Можно ли это сделать одной и той же командой? - каталог можно удалить командой rmdir. Каталог и файл можно удалить командой rm (в случае с первым с ключом -r). Например rm -r home. Так же содержимое каталога удаляется если использовать ключ -s. Пример rmdir -s


6. Как определить, какие команды выполнил пользователь в сеансе работы? - использовать команду history


7. Каким образом можно исправить и запустить на выполнение команду, которую пользователь уже использовал в сеансе работы? - выполнить команду history. Посмотреть на номер интересующей и выполнить команду !<номер команды>


8. Можно ли в одной строке записать несколько команд? - да, через ";".

Например: cd / ; ls


9. Что такое символ экранирования? - символ который из символа вносящего логику в команду(специального), превращает его в обычный символ не влияющий на логику программы. Например !1:s/\//etc


10. Какая информация выводится на экран о файлах и каталогах, если используется опция l в команде ls? - выводится подробный список, в котором будет отображаться владелец, группа, дата создания, размер и другие параметры


11. Что такое относительный путь к файлу? - путь, который начинается, указывает на другой путь относительно своего местонахождения. Например мы находимся в корневом каталоге. Для того чтобы попасть в каталок etc мы можем указать относительный путь (cd etc) либо полный (cd /etc). В данном случае разница нет. Но если нам нужно будет перейти в каталог домашний, мы не сможем использовать относительные пути. Ибо мы находимся в другой локации. Нужно использовать абсолютный


12. Как получить информацию об интересующей вас команде? - ввести команду man <интересующая команда>


13. Какая клавиша или комбинация клавиш служит для автоматического дополнения вводимых команд? - клавиша tab если нет слов начинающихся на это слово


# Выводы


Приобрела практические навыки взаимодействия с системой посредством командной строки.
