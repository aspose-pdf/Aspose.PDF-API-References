---
title: "BT"
linktitle: "BT"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 BT 操作符的类（Begin of text block）。"
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.operators/bt/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.operators.BlockTextOperator, com.aspose.pdf.operators.BT

```
public class BT extends BlockTextOperator
```

表示 BT 操作符的类（Begin of text block）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BT](#BT--) | 写入程序的构造函数。 |
| [BT](#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 写入程序的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 生成操作符的文本代码。 |

### BT {#BT--}
```
public BT()
```

写入程序的构造函数。

### BT {#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
写入程序的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

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

生成操作符的文本代码。

**Returns:**
运算符的文本表示。
