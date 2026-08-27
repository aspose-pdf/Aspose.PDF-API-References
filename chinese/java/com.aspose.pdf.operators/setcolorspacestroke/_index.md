---
title: "SetColorSpaceStroke"
linktitle: "SetColorSpaceStroke"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 CS 运算符的类（为描边操作设置颜色）。"
type: docs
weight: 590
url: /zh/java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpaceStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpaceStroke

```
public class SetColorSpaceStroke extends Operator
```

表示 CS 运算符的类（为描边操作设置颜色）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetColorSpaceStroke](#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-) | 操作符类的构造函数。 |
| [SetColorSpaceStroke](#SetColorSpaceStroke-java.lang.String-) | 初始化操作符。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理运算符。 |
| [getName](#getName--) | 获取颜色空间名称。 |
| [setName](#setName-java.lang.String-) | 设置颜色空间名称。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |

### SetColorSpaceStroke {#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-}
操作符类的构造函数。

### SetColorSpaceStroke {#SetColorSpaceStroke-java.lang.String-}
初始化操作符。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理运算符。

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
