# sys27-mon
 ### Чусовитин Эдуард
# Домашнее задание к занятию «Система мониторинга Zabbix»
---

### Задание 1 

Установите Zabbix Server с веб-интерфейсом.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите PostgreSQL. Для установки достаточна та версия, что есть в системном репозитороии Debian 11.
3. Пользуясь конфигуратором команд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.
4. Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server.

#### Требования к результаты 
1. Прикрепите в файл README.md скриншот авторизации в админке.
2. Приложите в файл README.md текст использованных команд в GitHub.
### Ответ:
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zabbix_adm.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/Zabbix_web.PNG)



---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 вирт.машины, одной из них может быть ваш Zabbix Server.
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов.
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera.
5. Проверьте, что в разделе Latest Data начали появляться данные с добавленных агентов.
 
### Ответ:
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/hosts.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zab1_mon.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zab2_mon.PNG)
![alt text](https://github.com/ChusovitinEduard/sys27-mon/blob/main/zabb_log.PNG)

