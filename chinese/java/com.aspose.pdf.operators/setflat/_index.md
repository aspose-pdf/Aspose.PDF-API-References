---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 i 运算符的类（设置平坦度容差）。"
type: docs
weight: 620
url: /zh/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

表示 i 运算符的类（设置平坦度容差）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetFlat](#SetFlat-double-) | 初始化操作符。 |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理运算符。 |
| [getFlatness](#getFlatness--) | 获取平整度。 |
| [setFlatness](#setFlatness-double-) | 设置平整度。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

初始化操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 平整度 |  | 平整度的值。 |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理运算符。

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

获取平整度。

**Returns:**
double 值

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

设置平整度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

仅供内部使用！

**Returns:**
ICommand 值 ICommand 对象
