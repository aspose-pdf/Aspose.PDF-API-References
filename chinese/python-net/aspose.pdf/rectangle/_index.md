---
title: "Rectangle"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "类表示矩形。"
type: docs
weight: 1320
url: /zh/python-net/aspose.pdf/rectangle/
---

## Rectangle class

类表示矩形。

Rectangle 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | 初始化 Rectangle 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| width | 矩形的宽度。 |
| 高度 | 矩形的高度。 |
| llx | 左下角的 X 坐标。 |
| lly | 左下角的 Y 坐标。 |
| urx | 右上角的 X 坐标。 |
| ury | 右上角的 Y 坐标。 |
| 平凡的 | 初始化平凡矩形，即位置和大小均为零的矩形。 |
| is_trivial | 检查矩形是否为平凡，即大小和位置为零。 |
| is_empty | 检查矩形是否为空。 |
| is_point | 检查矩形是否为点，即 LLX 等于 URX 且 LLY 等于 URY。 |
| 空 | 空矩形 |
## 方法
| 名称 | 描述 |
| :- | :- |
| rotate(angle) | 按指定角度旋转矩形。 |
| rotate(angle) | 按指定角度旋转矩形。 |
| to_rect() | 将矩形转换为 System.Drawing.Rectangle 的实例。浮点数位置和大小将被截断。 |
| from_rect(src) | 从给定的 System.Drawing.Rectangle 实例初始化新矩形。 |
| parse(value) | 尝试解析字符串并从中提取矩形组件 llx、lly、urx、ury。 |
| equals(other) | 检查矩形是否相等，即位置和大小相同。 |
| near_equals(other, delta) | 检查矩形是否近似相等，即位置和大小（在 delta 范围内）几乎相同。 |
| intersect(other_rect) | 判断两个矩形是否相交。 |
| join(other_rect) | 合并矩形。 |
| is_intersect(other_rect) | 确定此矩形是否与另一个矩形相交。 |
| contains(point) | 确定给定点是否在矩形内部。 |
| center() | 返回矩形中心的坐标。 |
| clone() | 克隆 Rectangle 对象。 |
| to_points() | 将矩形转换为点数组（"QuadPoints"）。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

