---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示显式目标，该目标显示页面，并将坐标 (left, top) 定位在窗口的左上角，页面内容按 zoom 因子放大。对于参数 left、top 或 zoom 的任何空值，表示保留该参数的当前值不变。zoom 为 0 的值具有与空值相同的含义。"
type: docs
weight: 880
url: /zh/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

表示显式目标，该目标显示页面，并将坐标 (left, top) 定位在窗口的左上角，页面内容按 zoom 因子放大。对于参数 left、top 或 zoom 的任何空值，表示保留该参数的当前值不变。zoom 为 0 的值具有与空值相同的含义。

XYZExplicitDestination 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | 初始化 XYZExplicitDestination 类的新实例 |
| XYZExplicitDestination(document, page_number, left, top, zoom) | 初始化 XYZExplicitDestination 类的新实例 |
| XYZExplicitDestination(page_number, left, top, zoom) | 初始化 XYZExplicitDestination 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| 获取包含 TextFragment 的页面。 | 获取目标页面对象 |
| page_number | 获取目标页面编号 |
| left | 获取窗口左上角的水平左坐标。 |
| top | 获取窗口左上角的垂直上坐标。 |
| zoom | 获取缩放因子。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | 创建目标到页面的指定位置，如有需要则考虑页面旋转。 |
| create_destination(page, type, values) | 创建 ExplicitDestination 派生类的实例。 |
| create_destination(doc, page_number, type, values) | 创建 ExplicitDestination 派生类的实例。 |
| create_destination(page_number, type, values) | 创建 ExplicitDestination 派生类的实例。 |
| create_destination_to_upper_left_corner(page, zoom) | 创建目标到指定页面的左上角。 |
| create_destination_to_upper_left_corner(page) | 创建目标到指定页面的左上角。 |
| to_string() | 将对象状态转换为字符串值。例如："1 XYZ 100 200 3"。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

