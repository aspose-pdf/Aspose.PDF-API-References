---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Tm 运算符的类（设置文本矩阵）。"
type: docs
weight: 750
url: /zh/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

表示 Tm 运算符的类（设置文本矩阵）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | 初始化操作符。 |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | 初始化操作符。 |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | 通过矩阵初始化运算符。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getMatrix](#getMatrix--) | 运算符的矩阵参数。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 运算符的矩阵参数。 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

初始化操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a |  | A 系数 |
| b |  | B 系数 |
| c |  | C 系数 |
| d |  | D 系数 |
| e |  | E 系数 |
| f |  | F 系数 |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
初始化操作符。

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
通过矩阵初始化运算符。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

运算符的矩阵参数。

**Returns:**
Matrix 对象

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
运算符的矩阵参数。

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
