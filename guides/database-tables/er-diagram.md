# 毕业论文 ER 图怎么画，从实体到基数

[返回数据库图表与测试文档](README.md) · [查看总目录](../../README.md)

ER 图用于说明数据对象、它们的属性以及对象之间的关系。先画读者需要理解的业务关系，再决定哪些字段值得显示。

![学生选课 ER 图的可视化编辑与预览](../../images/student-examples/er-diagram.png)

截图展示对应工具的示例操作。

## 操作步骤

1. 从需求中挑出独立的数据对象，例如学生和课程。给每个实体选稳定的主键，再把名称、日期等信息作为属性。
2. 对每条关系分别询问两个方向。例如一个学生能选几门课，一门课可由多少名学生选择。多对多关系可通过选课记录实体展开。
3. 排版时让关联多的实体靠近，把连线交叉减到少量。导出后在论文的实际插图尺寸下阅读一遍。

## 示例

图书借阅含读者、图书副本和借阅记录。单个读者可有多条借阅记录，单个副本也可在不同时段关联不同借阅记录。

## 完成后检查

主键标识清楚，基数与业务规则一致，属性名称可以辨认。

[在线画 ER 实体关系图](https://hajimicode.cn/tools/er-diagram?utm_source=github&utm_medium=referral&utm_campaign=academic_tools&utm_content=guide_er-diagram_try) · [查看主站原教程](https://hajimicode.cn/tutorials/er-diagram?utm_source=github&utm_medium=referral&utm_campaign=academic_tools&utm_content=guide_er-diagram_source)
