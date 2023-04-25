# Домашнее задание к занятию 10.3 «Pacemaker» - Липин Роман

Домашнее задание выполните в Google Docs и отправьте в личном кабинете на проверку ссылку на ваш документ.

Название файла должно содержать номер лекции и фамилию студента. Пример названия: «10.3 Pacemaker — Александр Александров»

Перед тем как выслать ссылку, убедитесь, что её содержимое не приватно, т. е. открыто на просмотр всем, у кого есть ссылка. Если нужно прикрепить дополнительные ссылки, просто добавьте их в Google Docs.

Любые вопросы по решению задач задавайте в чате учебной группы.

Задание 1

Опишите основные функции и назначение Pacemaker.

Приведите ответ в свободной форме.

Pacemaker - менеджер ресурсов кластера. Может обнаруживать сбои на уровне узлов и сервисов и проводить их восстановление.

Задание 2

Опишите основные функции и назначение Corosync.

Приведите ответ в свободной форме.

Corosync предназначен для реализации функционала кластера, он знает и передает состояние всех его узлов. Умеет отслеживать состояние приложенийй, синхронизировать конфигурационные файлы, оповещать приложения о смене активно ноды.

Задание 3

Соберите модель, состоящую из двух виртуальных машин. Установите Pacemaker, Corosync, Pcs. Настройте HA кластер.

Пришлите скриншот рабочей конфигурации и состояния сервиса для каждого нода.

![103-01](https://github.com/LipinRoman/10.3/blob/main/img/103-01.png)

![103-02](https://github.com/LipinRoman/10.3/blob/main/img/103-02.png)

![103-03](https://github.com/LipinRoman/10.3/blob/main/img/103-03.png)

Задания со звёздочкой*

Эти задания дополнительные. Выполнять их не обязательно. Это не повлияет на зачёт. Вы можете их выполнить, если хотите глубже разобраться в материале.
Задание 4

Установите и настройте DRBD-сервис для настроенного кластера.

Пришлите скриншот рабочей конфигурации и состояние сервиса для каждого нода.