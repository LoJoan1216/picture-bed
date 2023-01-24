* 查询所有模式名

  > SELECT DISTINCT object_name FROM ALL_OBJECTS WHERE OBJECT_TYPE = 'SCH'

* 根据模式名查询表名

  > SELECT table_name FROM dba_tables WHERE owner = '模式名'

* 查询某个模式名下面的某个表的所有字段

  > SELECT COLUMN_NAME FROM all_tab_columns WHERE onwer = '模式名' AND Table_Name = '表名'