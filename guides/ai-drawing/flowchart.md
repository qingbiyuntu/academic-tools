# 系统流程图怎么画，从起点写到异常出口

[返回AI 绘图与业务流程](README.md) · [查看总目录](../../README.md)

流程图适合表达规则和执行顺序。先写动词短句，再把动作、判断和开始结束画成不同节点。

![系统流程图编辑器中的登录校验与分支](../../images/student-examples/login-flowchart.png)

截图展示对应工具的示例操作。

## 操作步骤

1. 用一句话定义起点和结果，例如从提交设备借用申请开始，以确认借用或通知失败结束。
2. 列出主流程。凡是下一步随条件变化的地方放一个判断节点，并给每条出口命名。
3. 补上失败、返回和终止步骤。把图放到报告里预览，确认小尺寸图中的字和箭头仍可阅读。

## 示例

收到设备借用申请后先查库存。库存足够则登记借用，库存不足则通知申请人并结束。

## 完成后检查

从每条判断出口都能顺着箭头走到下一步或结束。

[在线画系统流程图](https://hajimicode.cn/tools/systemflow?utm_source=github&utm_medium=referral&utm_campaign=academic_tools&utm_content=guide_flowchart_try) · [查看主站原教程](https://hajimicode.cn/tutorials/flowchart?utm_source=github&utm_medium=referral&utm_campaign=academic_tools&utm_content=guide_flowchart_source)
