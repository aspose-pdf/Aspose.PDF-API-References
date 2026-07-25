---
title: "BDC"
linktitle: "BDC"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 BDC 操作符的类（Begin marked-content sequence）"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.operators/bdc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.BDC, com.aspose.pdf.Operator, com.aspose.pdf.operators.BDC

```
public class BDC extends Operator
```

表示 BDC 操作符的类（Begin marked-content sequence）

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BDC](#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.BeginMarkedContentWithProperties-) | 初始化操作符。 |
| [BDC](#BDC-java.lang.String-) | 初始化操作符。 |
| [BDC](#BDC-java.lang.String-com.aspose.pdf.facades.BDCProperties-) |  |
| [BDC](#BDC-java.lang.String-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getProperties](#getProperties--) |  |
| [getTag](#getTag--) | 获取标记内容标签 |
| [setTag](#setTag-java.lang.String-) | 设置标记内容标签 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### BDC {#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.BeginMarkedContentWithProperties-}
初始化操作符。

### BDC {#BDC-java.lang.String-}
初始化操作符。

### BDC {#BDC-java.lang.String-com.aspose.pdf.facades.BDCProperties-}


### BDC {#BDC-java.lang.String-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getProperties {#getProperties--}
```
public final BDCProperties getProperties()
```



### getTag {#getTag--}
```
public String getTag()
```

获取标记内容标签

**Returns:**
字符串值

### setTag {#setTag-java.lang.String-}
设置标记内容标签

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
