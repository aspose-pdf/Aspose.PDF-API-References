---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示运算符的集合。"
type: docs
weight: 3190
url: /zh/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

类表示运算符的集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | 仅供内部使用！ |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | 仅供内部使用！ |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受 IOperatorSelector 访问者对象以处理操作符。 |
| [add](#add-java.lang.Iterable-) | 将其他集合中的所有操作符添加到集合中。 |
| [add](#add-com.aspose.pdf.Operator-) | <p> 向集合中添加新的操作符。 </p> <hr> <p> 示例演示如何将操作符添加到 page.contents 的末尾。 <p> Document doc = new Document(\"input.pdf\"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> 在内容操作符的末尾添加操作符。 </p> <hr> <p> 示例演示如何将操作符添加到页面内容的末尾。 </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | 取消上一次更新。当更改不应触发内容更新时可以调用此方法。 |
| [clear](#clear--) | <p> 从列表中移除所有操作符。 </p> <hr> <p> 示例演示如何清除页面内容。 </p> <p> Document doc = new Document(\"input.pdf\"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | 执行应用程序定义的任务，涉及释放、释放或重置非托管资源。 |
| [contains](#contains-com.aspose.pdf.Operator-) | 如果集合包含给定的操作符，则返回 true。 |
| [delete](#delete-int-) | <p> 从集合中删除操作符。 </p> <hr> <p> 示例演示如何通过索引删除操作符。 <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | 从集合中删除操作符。 |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> 从集合中删除操作符。 </p> <hr> <p> 示例演示如何从页面内容中移除操作符。 </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | Delete(index) 的内部无限制版本 |
| [dispose](#dispose--) | 执行应用程序定义的任务，涉及释放、释放或重置非托管资源。 |
| [get_Item](#get_Item-int-) | <p> 通过索引获取操作符。 </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | 索引器的内部无限制版本 |
| [insert](#insert-int-java.lang.Iterable-) | 在给定位置插入操作符。 |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> 向集合中插入操作符。 </p> <hr> <p> 示例演示如何向页面内容插入操作符。 <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> 在给定位置插入操作符。 </p> <hr> <p> 示例演示如何向页面内容插入操作符。 </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | 获取操作符序列的括号状态，即这些操作符是否位于 q - Q 块内部。 |
| [isCommandsParsed](#isCommandsParsed--) | 获取已解析的命令 |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | 指示集合是否受限于快速文本提取 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
| [iterator](#iterator--) | 返回集合的枚举器 |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | 获取描述页面内容的操作符数量，而无需对它们进行初始化。 |
| [remove](#remove-com.aspose.pdf.Operator-) | 从集合中移除操作符。 |
| [replace](#replace-java.lang.Iterable-) | 用其他操作符替换集合中的操作符。 |
| [replace](#replace-com.aspose.pdf.Operator:A-) | 用其他操作符替换集合中的操作符。 |
| [resumeUpdate](#resumeUpdate--) | 恢复文档更新。如果有任何挂起的更改，则更新内容流。 |
| [resumeUpdate](#resumeUpdate-boolean-) | 恢复文档更新。如果有任何挂起的更改，则更新内容流。如果 invalidate 参数为 true，则将所有操作符标记为"changed"。 |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | 通过索引设置操作符。 |
| [size](#size--) | 获取集合中操作符的计数。 |
| [suppressUpdate](#suppressUpdate--) | 抑制内容更新数据，直到调用 ResumeUpdate 前，内容流不会被更新。 |
| [toList](#toList--) | 返回操作符列表。 |
| [toString](#toString--) | 返回运算符的文本表示。 |
| [updateData](#updateData--) | 更新对象流。 |
| [updateNormalizedData](#updateNormalizedData--) | 更新对象流并修复缺失的 GSave/GRestore 运算符。 |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
仅供内部使用！

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
仅供内部使用！

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受 IOperatorSelector 访问者对象以处理操作符。

### add {#add-java.lang.Iterable-}
将其他集合中的所有操作符添加到集合中。

### add {#add-com.aspose.pdf.Operator-}
<p> 向集合中添加新的操作符。 </p> <hr> <p> 示例演示如何将操作符添加到 page.contents 的末尾。 <p> Document doc = new Document(\"input.pdf\"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> 在内容操作符的末尾添加操作符。 </p> <hr> <p> 示例演示如何将操作符添加到页面内容的末尾。 </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

取消上一次更新。当更改不应触发内容更新时可以调用此方法。

### clear {#clear--}
```
public void clear()
```

<p> 从列表中移除所有操作符。 </p> <hr> <p> 示例演示如何清除页面内容。 </p> <p> Document doc = new Document(\"input.pdf\"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

执行应用程序定义的任务，涉及释放、释放或重置非托管资源。

### contains {#contains-com.aspose.pdf.Operator-}
如果集合包含给定的操作符，则返回 true。

### delete {#delete-int-}
```
public void delete(int index)
```

<p> 从集合中删除操作符。 </p> <hr> <p> 示例演示如何通过索引删除操作符。 <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 必须删除的运算符的索引。运算符编号从 1 开始。 |

### delete {#delete-java.lang.Iterable-}
从集合中删除操作符。

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> 从集合中删除操作符。 </p> <hr> <p> 示例演示如何从页面内容中移除操作符。 </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

Delete(index) 的内部无限制版本

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

### dispose {#dispose--}
```
public final void dispose()
```

执行应用程序定义的任务，涉及释放、释放或重置非托管资源。

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> 通过索引获取操作符。 </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 运算符的索引。编号从 1 开始。 |

**Returns:**
来自请求索引的运算符

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

索引器的内部无限制版本

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

**Returns:**
运算符对象

### insert {#insert-int-java.lang.Iterable-}
在给定位置插入操作符。

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> 向集合中插入操作符。 </p> <hr> <p> 示例演示如何向页面内容插入操作符。 <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> 在给定位置插入操作符。 </p> <hr> <p> 示例演示如何向页面内容插入操作符。 </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

获取操作符序列的括号状态，即这些操作符是否位于 q - Q 块内部。

**Returns:**
布尔值

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

获取已解析的命令

**Returns:**
布尔值

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

指示集合是否受限于快速文本提取

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取一个值，指示集合是否为只读。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

返回集合的枚举器

**Returns:**
集合枚举器

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

获取描述页面内容的操作符数量，而无需对它们进行初始化。

**Returns:**
int 值

### remove {#remove-com.aspose.pdf.Operator-}
从集合中移除操作符。

### replace {#replace-java.lang.Iterable-}
用其他操作符替换集合中的操作符。

### replace {#replace-com.aspose.pdf.Operator:A-}
用其他操作符替换集合中的操作符。

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

恢复文档更新。如果有任何挂起的更改，则更新内容流。

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

恢复文档更新。如果有任何挂起的更改，则更新内容流。如果 invalidate 参数为 true，则将所有操作符标记为"changed"。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updateAll |  | 如果为 true，则集合中的所有运算符标记为已更新。 |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
通过索引设置操作符。

### size {#size--}
```
public int size()
```

获取集合中操作符的计数。

**Returns:**
int 值

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

抑制内容更新数据，直到调用 ResumeUpdate 前，内容流不会被更新。

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

返回操作符列表。

**Returns:**
运算符列表。

### toString {#toString--}
```
public String toString()
```

返回运算符的文本表示。

**Returns:**
运算符的文本表示。

### updateData {#updateData--}
```
public void updateData()
```

更新对象流。

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

更新对象流并修复缺失的 GSave/GRestore 运算符。
