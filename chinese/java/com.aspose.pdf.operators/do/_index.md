---
title: "执行"
linktitle: "执行"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Do 操作符的类（Invoke XObject）。"
type: docs
weight: 180
url: /zh/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

表示 Do 操作符的类（Invoke XObject）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Do](#Do--) | 构造新的 Do 操作符。用于检索所有 Do 操作符，即不检查它们的参数名称。 |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | 构造新的 Do 操作符。用于检索所有 Do 操作符，即不检查它们的参数名称。 |
| [Do](#Do-java.lang.String-) | 构造新的 Do 操作符。用于检索所有 Do 操作符，即不检查它们的参数名称。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getCommandName](#getCommandName--) | 获取命令名称 |
| [getName](#getName--) | 获取操作符的 XObject 参数的名称。 |
| [setName](#setName-java.lang.String-) | 设置操作符的 XObject 参数的名称。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 返回操作符的文本表示。 |

### Do {#Do--}
```
public Do()
```

构造新的 Do 操作符。用于检索所有 Do 操作符，即不检查它们的参数名称。

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
构造新的 Do 操作符。用于检索所有 Do 操作符，即不检查它们的参数名称。

### Do {#Do-java.lang.String-}
构造新的 Do 操作符。用于检索所有 Do 操作符，即不检查它们的参数名称。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

获取命令名称

**Returns:**
字符串值

### getName {#getName--}
```
public String getName()
```

获取操作符的 XObject 参数的名称。

**Returns:**
字符串值

### setName {#setName-java.lang.String-}
设置操作符的 XObject 参数的名称。

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
运算符的文本表示。
