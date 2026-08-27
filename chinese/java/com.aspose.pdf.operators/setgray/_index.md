---
title: "SetGray"
linktitle: "SetGray"
second_title: "Aspose.PDF for Java API 参考"
description: "为非描边操作设置灰度级别。"
type: docs
weight: 640
url: /zh/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

为非描边操作设置灰度级别。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetGray](#SetGray-double-) | 写入程序的构造函数。 |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getColor](#getColor--) | 返回运算符指定的颜色。 |
| [getGray](#getGray--) | 获取或设置灰度值的级别。 |
| [setGray](#setGray-double-) | 获取或设置灰度值的级别。 |
| [toString](#toString--) | 返回操作符的字符串表示。 |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

写入程序的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 灰色 |  | 灰度值的级别。 |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
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

返回操作符的字符串表示。

**Returns:**
操作符的字符串表示。
