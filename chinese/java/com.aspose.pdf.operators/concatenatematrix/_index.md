---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 cm 操作符的类（concatenate matrix to current transformation matrix）。"
type: docs
weight: 140
url: /zh/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

表示 cm 操作符的类（concatenate matrix to current transformation matrix）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | 操作符类的构造函数。 |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | 操作符类的构造函数。 |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | 通过矩阵初始化运算符。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getMatrix](#getMatrix--) | 运算符的矩阵参数。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 运算符的矩阵参数。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 返回操作符的文本表示。 |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

操作符类的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a |  | A 系数 |
| b |  | B 系数 |
| c |  | C 系数 |
| d |  | D 系数 |
| e |  | E 系数 |
| f |  | F 系数 |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
操作符类的构造函数。

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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
