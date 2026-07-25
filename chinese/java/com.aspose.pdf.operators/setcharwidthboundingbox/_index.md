---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 d1 运算符的类（设置字形和边界框）。"
type: docs
weight: 520
url: /zh/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

表示 d1 运算符的类（设置字形和边界框）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | 初始化 SetCharWidthBoundingBox 操作符。 |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getLlx](#getLlx--) | 边界矩形左下角的水平坐标。 |
| [getLly](#getLly--) | 边界矩形左下角的垂直坐标。 |
| [getUrx](#getUrx--) | 边界矩形右上角的水平坐标。 |
| [getUry](#getUry--) | 边界矩形右上角的垂直坐标。 |
| [getWx](#getWx--) | 字形的水平位移。 |
| [getWy](#getWy--) | 字形的垂直位移。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

初始化 SetCharWidthBoundingBox 操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wx |  | 表示字形坐标系中的水平位移。 |
| wy |  | 表示字形坐标系中的垂直位移。应为 0。 |
| llx |  | 表示左下角的 X 坐标。 |
| lly |  | 表示左下角的 Y 坐标。 |
| urx |  | 表示右上角的 X 坐标。 |
| ury |  | 表示右上角的 Y 坐标。 |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getLlx {#getLlx--}
```
public double getLlx()
```

边界矩形左下角的水平坐标。

**Returns:**
double 值

### getLly {#getLly--}
```
public double getLly()
```

边界矩形左下角的垂直坐标。

**Returns:**
double 值

### getUrx {#getUrx--}
```
public double getUrx()
```

边界矩形右上角的水平坐标。

**Returns:**
double 值

### getUry {#getUry--}
```
public double getUry()
```

边界矩形右上角的垂直坐标。

**Returns:**
double 值

### getWx {#getWx--}
```
public double getWx()
```

字形的水平位移。

**Returns:**
double 值

### getWy {#getWy--}
```
public double getWy()
```

字形的垂直位移。

**Returns:**
double 值

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

仅供内部使用！

**Returns:**
ICommand 值 ICommand 对象

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
文本表示的表示
