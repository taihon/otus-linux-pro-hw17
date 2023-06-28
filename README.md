## OTUS Administrator Linux. Professional ДЗ №17: DHCP, PXE

**Задание**

Для выполнения домашнего задания используйте методичку
https://docs.google.com/document/d/1f5I8vbWAk8ah9IFpAQWN3dcWDHMqXzGb/edit?usp=share_link&ouid=104106368295333385634&rtpof=true&sd=true
Что нужно сделать?

1. Следуя шагам из документа https://docs.centos.org/en-US/8-docs/advanced-install/assembly_preparing-for-a-network-install установить и настроить загрузку по сети для дистрибутива CentOS8.
2. В качестве шаблона воспользуйтесь репозиторием https://github.com/nixuser/virtlab/tree/main/centos_pxe.
3. Поменять установку из репозитория NFS на установку из репозитория HTTP.
4. Настроить автоматическую установку для созданного kickstart файла (\*) Файл загружается по HTTP.
5. (\*) автоматизировать процесс установки Cobbler cледуя шагам из документа https://cobbler.github.io/quickstart/.

Формат сдачи ДЗ - vagrant + ansible

Критерии оценки:
Статус "Принято" ставится при выполнении следующих условий:

1. Ссылка на репозиторий github.
2. Vagrantfile с шагами установки необходимых компонентов
3. Исходный код scripts для настройки сервера (если необходимо)
4. Если какие-то шаги невозможно или сложно автоматизировать, то инструкции по ручным шагам для настройки
   Задание со звездочкой выполняется по желанию.

**_Решение_**
