---
title: "FitRExplicitDestination"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示显式目标，该目标在水平和垂直方向上将页面内容放大到恰好使由 left、bottom、right、top 坐标指定的矩形完全适合窗口。如果所需的水平和垂直放大因子不同，则使用较小的因子，并在另一维度上将矩形居中于窗口。任意参数为 null 值可能导致不可预测的行为。"
type: docs
weight: 230
url: /zh/python-net/aspose.pdf.annotations/fitrexplicitdestination/
---

## FitRExplicitDestination class

表示显式目标，该目标在水平和垂直方向上将页面内容放大到恰好使由 left、bottom、right、top 坐标指定的矩形完全适合窗口。如果所需的水平和垂直放大因子不同，则使用较小的因子，并在另一维度上将矩形居中于窗口。任意参数为 null 值可能导致不可预测的行为。

FitRExplicitDestination 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| FitRExplicitDestination(page, left, bottom, right, top) | 初始化 FitRExplicitDestination 类的新实例 |
| FitRExplicitDestination(document, page_number, left, bottom, right, top) | 初始化 FitRExplicitDestination 类的新实例 |
| FitRExplicitDestination(page_number, left, bottom, right, top) | 初始化 FitRExplicitDestination 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| 获取包含 TextFragment 的页面。 | 获取目标页面对象 |
| page_number | 获取目标页面编号 |
| left | 获取可见矩形的左水平坐标。 |
| bottom | 获取可见矩形的底部垂直坐标。 |
| 右 | 获取可见矩形的右水平坐标。 |
| top | 获取可见矩形的顶部垂直坐标。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| create_destination(page, type, values) | 创建 ExplicitDestination 派生类的实例。 |
| create_destination(doc, page_number, type, values) | 创建 ExplicitDestination 派生类的实例。 |
| create_destination(page_number, type, values) | 创建 ExplicitDestination 派生类的实例。 |
| to_string() | 将对象状态转换为字符串值。示例："1 FitR 100 200 300 400"。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

