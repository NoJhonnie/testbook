* 查看当前数据库名称

```
db
```

* 查看所有数据库

```
show dbs
```

* 创建数据库，如果不存在，则指向但不创建，直到插入数据时才被创建

```
use 数据库名称
```

* 默认数据库为test，没有创建新的数据库，则将存放在test中

### 数据库删除

* 删除当前指向数据库，如果不存在，则什么都不做

```
db.dropDatabase()
```



