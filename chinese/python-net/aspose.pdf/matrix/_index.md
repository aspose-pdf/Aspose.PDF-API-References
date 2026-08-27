---
title: "Matrix"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "类表示变换矩阵。"
type: docs
weight: 900
url: /zh/python-net/aspose.pdf/matrix/
---

## Matrix class

类表示变换矩阵。

Matrix 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Matrix() | Constructor<br/>            创建标准 1 对 1 矩阵：<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | 初始化 Matrix 类的新实例 |
| Matrix(matrix_array) | 初始化 Matrix 类的新实例 |
| Matrix(matrix) | 初始化 Matrix 类的新实例 |
| Matrix(a, b, c, d, e, f) | 初始化 Matrix 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| data | 获取 Matrix 数据为数组。 |
| a | 变换矩阵的 A 成员。 |
| b | 变换矩阵的 B 成员。 |
| c | 变换矩阵的 C 成员。 |
| d | 变换矩阵的 D 成员。 |
| e | 变换矩阵的 E 成员。 |
| f | 变换矩阵的 F 成员。 |
| 元素 | 矩阵的元素。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| rotation(alpha) | 为给定的旋转角度创建矩阵。 |
| rotation(rotation) | 为给定的旋转角度创建矩阵。 |
| transform(p) | 使用此矩阵对点进行变换。 |
| transform(rect) | 变换矩形。<br/>            如果角度不是 90 * N 度，则返回包围矩形。 |
| skew(alpha, beta) | 为给定的旋转角度创建矩阵。 |
| get_angle(rotation) | 将旋转转换为角度（度） |
| multiply(other) | 将矩阵乘以另一个矩阵。 |
| add(other) | 将矩阵加到另一个矩阵。 |
| reverse() | 计算逆矩阵。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

