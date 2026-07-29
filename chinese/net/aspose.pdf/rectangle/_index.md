---
title: "类 Rectangle"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Rectangle 类。类表示矩形"
type: docs
weight: 9900
url: /zh/net/aspose.pdf/rectangle/
---
## Rectangle class

表示矩形的类。

```csharp
public sealed class Rectangle : ICloneable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Rectangle 的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | 空矩形 |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | 初始化平凡矩形，即位置和大小均为零的矩形。 |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | 矩形的高度。 |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | 检查矩形是否为空。 |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | 检查矩形是否为点，即 LLX 等于 URX 且 LLY 等于 URY。 |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | 检查矩形是否为平凡，即大小和位置均为零。 |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | 左下角的 X 坐标。 |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | 左下角的 Y 坐标。 |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | 右上角的 X 坐标。 |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | 右上角的 Y 坐标。 |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | 矩形的宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | 从给定的 System.Drawing.Rectangle 实例初始化新矩形。 |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | 从给定的 System.Drawing.Rectangle 实例初始化新矩形。 |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | 尝试解析字符串并从中提取矩形组件 llx、lly、urx、ury。 |
| [Center](../../aspose.pdf/rectangle/center/)() | 返回矩形中心的坐标。 |
| [Clone](../../aspose.pdf/rectangle/clone/)() | 克隆 Rectangle 对象。 |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | 确定给定点是否在矩形内部。 |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | 确定矩形是否包含由两点表示的线段。 |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | 确定给定点是否位于矩形内部。 |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | 检查矩形是否相等，即位置和大小相同。 |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | 两个矩形相交。 |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | 确定此矩形是否与另一个矩形相交。 |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | 合并矩形。 |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | 按指定的增量平移矩形。 |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | 检查矩形是否近似相等，即位置和大小在（至多 delta）范围内接近相同。 |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | 按指定角度旋转矩形。 |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | 按指定角度旋转矩形。 |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | 将矩形转换为点数组（"QuadPoints"）。 |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | 将矩形转换为 System.Drawing.Rectangle 实例。浮点位置和尺寸将被截断。 |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | 获取矩形的字符串表示。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


