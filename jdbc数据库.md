### 基本语法

	create table 表名（
	    列名 列的数据类型，
	...
	）character set 字符集名称 


### 连接查询时，内连接和外连接区别
### 内连接： 两张表的地位一致，
### 外连接：两张表的地位不一致，有一张是基础表，基础表的数据必须全部出现，没有匹配则用null补齐
### 左外连接和右外连接 ，第一张表示基础表

### 子查询 IN  Exist

### l联合查询

### UNION 可以把结果集连接在一体 列的数量和类型要兼容

### 日期和时间函数

### 符号函数 SIGN(X) 正数返回1 负数返回-1
### 随机函数 RAND(X) 如果是null 则是随机数 有X表示固定数字
### CELL(X) 找出一个不小于X的数，并且去最小的那是数
### FLOOR(X)找出一个不大于X的数，并且去一个最大的数


### trim 去掉两边的空隔，ltrim ,rtrim 左右的两边的空隔

### select count(id) from tab_name 获取指定列的数目大小




 