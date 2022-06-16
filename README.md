# Convert RedMine Issue and Wiki to Html

1. Set settings in **config.cfg** (run once *.exe to create struct file)
   1. [host], IP or DNS RedMine name (example: **http://192.168.1.1**)
   2. [apikey], *RedMine - User - API key*, RESTAPI must by On (example: **aldjfoeiwgj9348gn348**)
   3. [issuesid], convert Issue ID and/or Wiki list split *";"* (example: **1;2;114;9123** or **id100/wiki/Help1;id103/wiki/Help2**)

2. Run

========================================================================
1. Настроить **config.cfg** (запустить единожды *.exe для создания шаблона файла)
   1. [host], IP или DNS имя RedMine (например: **http://192.168.1.1**)
   2. [apikey], *RedMine - Моя учетная запись - Ключ доступа к API*, RESTAPI должен быть глобально включен Администратором (например: **aldjfoeiwgj9348gn348**)
   3. [issuesid], список Issue ID и/или страниц Wiki разделенных *";"* (например: **1;2;114;9123** или **id100/wiki/Help1;id103/wiki/Help2**)

2. Запустить 

![alt text](https://github.com/MasyGreen/RedMine.ToHelp/blob/master/Settings%20manual%20(config.cfg).jpg)

## Sample config.cfg
```
[Settings]
host = http://192.168.1.1
apikey = dq3inqgnqe8igqngninkkvekmviewrgir9384
issuesid = 1677;318
```

# Result
Issue or Wiki page must have html table, there first column is [Help ID]. Util separate table to one file.

Util crete files name *"Help[Help ID].htm"* in new Folder

Issue или Wiki должна содержать html таблицу, первый столбец которой является [Help ID]. Утилита разбивает таблицу на отдельные файлы.

Утилита создает файлы *"Help[Help ID].htm"* в новом каталоге