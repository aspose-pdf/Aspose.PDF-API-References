---
title: "Operator"
linktitle: "Operator"
second_title: "Aspose.PDF for Java API 参考"
description: "表示运算符的抽象类。"
type: docs
weight: 3180
url: /zh/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

表示运算符的抽象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 仅供内部使用！ |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者 IOperatorSelector，提供运算符处理。 |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 通过名称创建 com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand 实例的操作符。 |
| [equals](#equals-com.aspose.pdf.Operator-) | 将此实例与给定对象进行比较。 |
| [getCommand](#getCommand--) | 获取命令 |
| [getCommandName](#getCommandName--) | 获取操作符名称。 |
| [getIndex](#getIndex--) | 获取页面操作符列表中的操作符索引。 |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | 确定该操作符是否负责文本输出的操作符（Tj、TJ 等）。 |
| [setIndex](#setIndex-int-) | 设置页面操作符列表中的操作符索引。 |
| [toString](#toString--) | 将命令和参数转换为字符串表示形式。 |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | 将此实例与给定对象进行比较。 |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
仅供内部使用！

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者 IOperatorSelector，提供运算符处理。

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
通过名称创建 com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand 实例的操作符。

### equals {#equals-com.aspose.pdf.Operator-}
将此实例与给定对象进行比较。

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

获取命令

**Returns:**
ICommand 对象

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

获取操作符名称。

**Returns:**
字符串值

### getIndex {#getIndex--}
```
public int getIndex()
```

获取页面操作符列表中的操作符索引。

**Returns:**
int 值

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
确定该操作符是否负责文本输出的操作符（Tj、TJ 等）。

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

设置页面操作符列表中的操作符索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### toString {#toString--}
```
public String toString()
```

将命令和参数转换为字符串表示形式。

**Returns:**
操作符文本

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
将此实例与给定对象进行比较。
