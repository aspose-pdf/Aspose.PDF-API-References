---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 cs 运算符的类（为非描边操作设置颜色空间）"
type: docs
weight: 580
url: /zh/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

表示 cs 运算符的类（为非描边操作设置颜色空间）

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | 操作符类的构造函数。 |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | 初始化操作符。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getCommandName](#getCommandName--) | 获取命令名称。 |
| [getName](#getName--) | 获取颜色空间名称。 |
| [setName](#setName-java.lang.String-) | 设置颜色空间名称。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
操作符类的构造函数。

### SetColorSpace {#SetColorSpace-java.lang.String-}
初始化操作符。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

获取命令名称。

**Returns:**
字符串值

### getName {#getName--}
```
public String getName()
```

获取颜色空间名称。

**Returns:**
字符串值

### setName {#setName-java.lang.String-}
设置颜色空间名称。

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

仅供内部使用！

**Returns:**
ICommand 值 ICommand 对象
