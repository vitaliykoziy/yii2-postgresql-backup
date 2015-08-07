# yii2-postgresql-backup
Yii2 PostgreSql create backup
-------------------------------
Class for generate and save/download PostgreSql database backup file.
Simply to use.
``` code
        $path = 'full/path/dump.sql';
        $doDbBackup = new DoBackup($path);
        $doDbBackup->create();
```
Enjoy :)

