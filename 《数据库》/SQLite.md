# SQLite

1. [SQLite之主键与唯一约束](http://blog.csdn.net/lianghe_work/article/details/45979987)
	- 惟一地标识一行(一张表中只能有一个主键)
	- 主键应当是对用户没有意义的（常用于索引）
	- 永远不要更新主键，否则违反对用户没有意义原则
	- 主键不应包含动态变化的数据，如时间戳、创建时间列、修改时间列等
	- 在两个表的关系中，主关键字用来在一个表中引用来自于另一个表中的特定记录