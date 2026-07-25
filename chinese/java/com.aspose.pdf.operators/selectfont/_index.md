---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Aspose.PDF for Java API 参考"
description: "表示运算符 Tf 的类（设置文本字体和大小）。"
type: docs
weight: 470
url: /zh/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

表示运算符 Tf 的类（设置文本字体和大小）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | 操作符类的构造函数。 |
| [SelectFont](#SelectFont-java.lang.String-double-) | 用于编写程序的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getName](#getName--) | 获取字体名称。 |
| [getSize](#getSize--) | 获取文本大小。 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
操作符类的构造函数。

### SelectFont {#SelectFont-java.lang.String-double-}
用于编写程序的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getName {#getName--}
```
public String getName()
```

获取字体名称。

**Returns:**
字符串值

### getSize {#getSize--}
```
public double getSize()
```

获取文本大小。

**Returns:**
double 值

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
