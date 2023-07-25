* MongoDB 命令行可以使用 `mongorestore` 工具来恢复备份数据

   - `<database_name>`：要恢复的数据库名称。
   - `<path_to_backup_directory>`：备份文件所在的目录路径。

```
mongorestore --db=<database_name> <path_to_backup_directory>
```


MongoDB版本号 4.2.24