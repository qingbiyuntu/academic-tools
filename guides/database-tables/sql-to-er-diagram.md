# MySQL 没写外键，如何补全 ER 图的表关系

[返回数据库图表与测试文档](README.md) · [查看总目录](../../README.md)

旧项目可能只在业务设计中约定关联字段。导入建表语句后，可以把已有表结构作为起点，再依据规则补关系。

![学生选课 ER 图案例公开介绍页](images/student-course.jpg)

截图来自主站对应的工具介绍或公开示例。

## 操作步骤

1. 先导入所需的 CREATE TABLE 语句，核对表名、字段、主键和联合键是否齐全。把无关的初始化数据留在示例之外。
2. 对照字段含义和唯一性确认关联。例如选课记录的 student_id 指向学生主键，学生可以对应多条选课记录。字段同名时也要逐一核对。
3. 在图中选定关系两端的字段，补上基数。再用一笔典型记录走查表关系，并检查是否遗漏课程一侧。

## 示例

同一份选课示例可以做两份建表文本，一份显式写外键，一份只保留字段和主键。两次导入后对照已有连线并补齐关联。

## 完成后检查

每条连线都能说清为什么需要、关联哪个字段、两端允许多少条记录。

[导入 SQL 并补表关系](https://hajimicode.cn/tools/er-diagram?utm_source=github&utm_medium=referral&utm_campaign=academic_tools&utm_content=guide_sql-to-er-diagram_try) · [查看主站原教程](https://hajimicode.cn/tutorials/sql-to-er-diagram?utm_source=github&utm_medium=referral&utm_campaign=academic_tools&utm_content=guide_sql-to-er-diagram_source)
