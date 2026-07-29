---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 d0 运算符的类（设置字形宽度）。"
type: docs
weight: 510
url: /zh/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

表示 d0 运算符的类（设置字形宽度）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | 构造函数。 |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getWx](#getWx--) | 字形坐标的水平位移。 |
| [getWy](#getWy--) | 字形坐标的垂直位移。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wx |  | 字形的水平位移。 |
| wy |  | 字形的垂直位移。 |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getWx {#getWx--}
```
public double getWx()
```

字形坐标的水平位移。

**Returns:**
double 值

### getWy {#getWy--}
```
public double getWy()
```

字形坐标的垂直位移。

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
