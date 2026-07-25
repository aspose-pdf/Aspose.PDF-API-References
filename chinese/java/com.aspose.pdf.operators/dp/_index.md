---
title: "DP"
linktitle: "DP"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 DP 操作符的类（designamte marked content point）。"
type: docs
weight: 190
url: /zh/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

表示 DP 操作符的类（designamte marked content point）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | 操作符类的构造函数。 |
| [DP](#DP-java.lang.String-) | 初始化操作符。 |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getPropertiesDictionary](#getPropertiesDictionary--) | 获取属性字典 |
| [getTag](#getTag--) | 获取标记内容标签 |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | 设置属性字典 |
| [setTag](#setTag-java.lang.String-) | 设置标记内容标签 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 返回操作符的文本表示。 |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
操作符类的构造函数。

### DP {#DP-java.lang.String-}
初始化操作符。

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

获取属性字典

**Returns:**
IPdfDictionary 值

### getTag {#getTag--}
```
public String getTag()
```

获取标记内容标签

**Returns:**
字符串值

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
设置属性字典

### setTag {#setTag-java.lang.String-}
设置标记内容标签

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
