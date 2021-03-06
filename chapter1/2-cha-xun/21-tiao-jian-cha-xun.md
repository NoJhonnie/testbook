使用where对数据进行筛选

```
select * from table_name where 条件
```

##### 可以用比较运算符

* 等于=
* 大于&gt;
* 小于&lt;
* 小于或等于&lt;=
* 不等于!=或&lt;&gt;

##### 逻辑运算符

* and
* or
* not

##### 模糊查询

like + %或\_

* %表示任意多个字符

```
select * from students where sname like '黄%';
```

* \_表示一个任意字符

```
select * from students where sname like '黄_';
```

##### 范围查询

* in表示在一个非连续的范围内

```
select * from students where id in(1,3,8);
```

* between...and...表示在一个连续的范围内

```
select * from students where id between 3 and 8;
```

##### 空判断

因为null与其他是不同的，例如：‘’

is null进行判空

```
select * from students where hometown is null;
```

is not null判非空

```
select * from students where hometown is not null;
```

##### 优先级

小括号，not，比较运算符，逻辑运算符

and 比 or 先运算，这时就要用\(\)结合使用



