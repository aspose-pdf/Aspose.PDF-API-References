---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 TL 运算符的类（设置文本行距）。"
type: docs
weight: 740
url: /zh/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

表示 TL 运算符的类（设置文本行距）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | 文本行距操作符的构造函数。 |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getLeading](#getLeading--) | 获取文本行距。 |
| [setLeading](#setLeading-double-) | 设置文本行距。 |
| [toString](#toString--) | 生成操作符的文本代码。 |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

文本行距操作符的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leading |  | 文本行距。 |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getLeading {#getLeading--}
```
public double getLeading()
```

获取文本行距。

**Returns:**
double 值

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

设置文本行距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toString {#toString--}
```
public String toString()
```

生成操作符的文本代码。

**Returns:**
运算符的文本表示。
