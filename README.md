# Mybatis-Table-Generate
使用Js批量生成Mybatis-Generate中的&lt;table>&lt;/table>

* 实际效果（数据库表名下划线分隔，其他分隔符号记得改index.html中js的table.replace('_', '');）
<kbd>
  <div style="border: 1px solid gainsboro;border-radius: 5px;" align="center">
    <img width="80%" height="auto" src="https://github.com/xxlllq/Mybatis-Table-Generate/blob/master/generate.png"/>
  </div>
</kbd>

* 获取数据库中的所有表
select table_name from information_schema.tables where table_schema='数据库名称' and table_type='base table';
