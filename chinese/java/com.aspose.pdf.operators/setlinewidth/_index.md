---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 w 运算符的类（设置线宽）。"
type: docs
weight: 690
url: /zh/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

表示 w 运算符的类（设置线宽）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | 使用宽度值初始化运算符。 |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getWidth](#getWidth--) | 获取线条的宽度。 |
| [setWidth](#setWidth-double-) | 设置线条的宽度。 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

使用宽度值初始化运算符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 宽度的值。 |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getWidth {#getWidth--}
```
public double getWidth()
```

获取线条的宽度。

**Returns:**
线条的宽度。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置线条的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 线条的宽度。 |

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
