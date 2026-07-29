---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于描边操作的灰度级别的类。"
type: docs
weight: 650
url: /zh/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

表示用于描边操作的灰度级别的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | 使用指定的颜色初始化运算符。 |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getColor](#getColor--) | 返回运算符指定的颜色。 |
| [getGray](#getGray--) | 获取或设置灰度值的级别。 |
| [setGray](#setGray-double-) | 获取或设置灰度值的级别。 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

使用指定的颜色初始化运算符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 灰色 |  | 灰度值的级别。 |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getColor {#getColor--}
```
public Color getColor()
```

返回运算符指定的颜色。

**Returns:**
运算符指定的颜色。

### getGray {#getGray--}
```
public final double getGray()
```

获取或设置灰度值的级别。

**Returns:**
double 值

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

获取或设置灰度值的级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
