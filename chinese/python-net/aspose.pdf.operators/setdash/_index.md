---
title: "SetDash"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示 d 操作符的类（设置线段虚线模式）。"
type: docs
weight: 580
url: /zh/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

表示 d 操作符的类（设置线段虚线模式）。

SetDash 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| SetDash(pattern, phase) | 初始化 SetDash 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| index | 页面操作符列表中的操作符索引。 |
| 模式 | 虚线模式。数组的元素应为指定交替虚线和间隙长度的数字。<br/>            如果数组只有一个元素，则虚线和间隙的长度相等。 |
| 相位 | 虚线相位。在开始描绘路径之前，需遍历虚线数组，累计虚线和间隙的长度。<br/>            当累计长度等于虚线相位指定的值时，路径的描绘开始，<br/>            此后虚线数组将循环使用。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| accept(visitor) | 接受访问者对象以处理运算符。 |
| is_text_show_operator(op) | 确定该操作符是否负责文本输出的操作符 (Tj, TJ, 等) |

### 另请参阅

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

