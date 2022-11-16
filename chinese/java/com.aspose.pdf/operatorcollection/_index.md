---
title: OperatorCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示运算符的集合
type: docs
weight: 233
url: /zh/java/com.aspose.pdf/operatorcollection/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public class OperatorCollection extends BaseOperatorCollection
```

类表示运算符的集合
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OperatorCollection(IPdfPrimitive contents)](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | 仅供内部使用！ |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | 接受 IOperatorSelector 访问者对象以处理运算符。 |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | 将新运算符添加到集合中。 |
| [add(Operator[] ops)](#add-com.aspose.pdf.Operator---) | 在内容运算符的末尾添加运算符。 |
| [add(Iterable<Operator> ops)](#add-java.lang.Iterable-com.aspose.pdf.Operator--) | 将来自其他集合的所有运算符添加到集合中。 |
| [cancelUpdate()](#cancelUpdate--) | 取消上次更新。 |
| [clear()](#clear--) | 从列表中删除所有运算符。 |
| [contains(Operator op)](#contains-com.aspose.pdf.Operator-) | 如果集合包含给定的运算符，则返回 true。 |
| [delete(Operator[] ops)](#delete-com.aspose.pdf.Operator---) | 从集合中删除运算符。 |
| [delete(int index)](#delete-int-) | 从集合中删除运算符。 |
| [delete(Iterable<Operator> list)](#delete-java.lang.Iterable-com.aspose.pdf.Operator--) | 从集合中删除运算符。 |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | Delete(index) 的内部无限制版本 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | 索引器的内部无限制版本 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引获取运算符。 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | 将运算符插入集合。 |
| [insert(int at, Operator[] ops)](#insert-int-com.aspose.pdf.Operator---) | 在给定位置插入运算符。 |
| [insert(int at, Iterable<Operator> ops)](#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--) | 在给定位置插入运算符。 |
| [isBracketed()](#isBracketed--) | 获取运算符序列的括号状态，即此运算符是否在 q - Q 块内 |
| [isCommandsParsed()](#isCommandsParsed--) | 获取解析的命令 |
| [isEmpty()](#isEmpty--) | 如果集合为空，则返回 TRUE。 |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | 指示天气集合仅限于快速文本提取 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [iterator()](#iterator--) | 返回集合的枚举器 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator op)](#remove-com.aspose.pdf.Operator-) | 从集合中删除运算符。 |
| [replace(Operator[] operators)](#replace-com.aspose.pdf.Operator---) | 用其他运算符替换集合中的运算符。 |
| [replace(Iterable<Operator> operators)](#replace-java.lang.Iterable-com.aspose.pdf.Operator--) | 用其他运算符替换集合中的运算符。 |
| [resumeUpdate()](#resumeUpdate--) | 恢复文档更新。 |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | 通过索引设置运算符。 |
| [size()](#size--) | 获取集合中运算符的计数。 |
| [suppressUpdate()](#suppressUpdate--) | 禁止更新内容数据 内容流在调用 ResumeUpdate 之前不会更新 |
| [toList()](#toList--) | 返回运算符列表。 |
| [toString()](#toString--) | 返回运算符的文本表示。 |
| [updateData()](#updateData--) | 更新对象流。 |
| [updateNormalizedData()](#updateNormalizedData--) | 通过修复缺少的 GSave/GRestore 运算符来更新对象流。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OperatorCollection(IPdfPrimitive contents) {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public OperatorCollection(IPdfPrimitive contents)
```


仅供内部使用！

OperatorCollection 的构造函数。从原语构造运算符包含运算符列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contents | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPDF原始对象 |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


接受 IOperatorSelector 访问者对象以处理运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | 访客对象 |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


将新运算符添加到集合中。

--------------------

示例演示了如何将运算符添加到 page.contents 的末尾。

文档 doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q());

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 必须添加的运算符 |

### add(Operator[] ops) {#add-com.aspose.pdf.Operator---}
```
public void add(Operator[] ops)
```


在内容运算符的末尾添加运算符。

--------------------

示例演示如何将运算符添加到页面内容的末尾。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(新运算符[]\ { 新的 com.aspose.pdf.operators.q(), 新的 com.aspose.pdf.operators.Q()\});

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | 要添加的运算符数组。每个运算符可以有任何索引（默认为 -1），因为它们到达内容运算符的末尾，即自动分配索引。 |

### add(Iterable<Operator> ops) {#add-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void add(Iterable<Operator> ops)
```


将来自其他集合的所有运算符添加到集合中。

--------------------

```
Example demonstrates how to add operator collection to the page contents.

 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages(1).getContents();
 ArrayList opList = new ArrayList();
 opList.add(new com.aspose.pdf.operators.q());
 opList.add(new com.aspose.pdf.operators.Q());
 oc.add(opList);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ops | java.lang.Iterable<com.aspose.pdf.Operator> | 包含将添加的运算符的集合。 |

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


取消上次更新。当更改不应该引发内容更新时，可以调用此方法。

### clear() {#clear--}
```
public void clear()
```


从列表中删除所有运算符。

--------------------

示例演示如何清除页面内容。

文档 doc = new Document("input.pdf"); doc.getPages().get(1).clear();

### contains(Operator op) {#contains-com.aspose.pdf.Operator-}
```
public boolean contains(Operator op)
```


如果集合包含给定的运算符，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 算子实例 |

**退货：**
boolean - 布尔值 True - 如果找到运算符；否则，假的。
### delete(Operator[] ops) {#delete-com.aspose.pdf.Operator---}
```
public void delete(Operator[] ops)
```


从集合中删除运算符。

--------------------

示例演示了如何从页面内容中删除运算符。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(新运算符[]\oc[ 1]\});

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | 要删除的运算符数组 |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


从集合中删除运算符。

--------------------

示例演示如何通过其索引删除运算符。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3);

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 必须删除的运算符索引。运算符编号从1开始。 |

### delete(Iterable<Operator> list) {#delete-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void delete(Iterable<Operator> list)
```


从集合中删除运算符。

--------------------

示例演示了如何从页面内容中删除运算符。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents();数组列表<Operator>opList = new ArrayList<Operator>(); opList.add(oc[1]); oc.delete(opList);

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| list | java.lang.Iterable<com.aspose.pdf.Operator> | 要删除的操作员列表 |

### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


Delete(index) 的内部无限制版本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```


索引器的内部无限制版本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |

**退货：**
[Operator](../../com.aspose.pdf/operator) - 操作员对象
### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


通过其索引获取运算符。

--------------------

示例演示如何通过索引获取页面内容的运算符。

```
Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get(1).getContents();
 Operator first = oc.get_Item(1);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 运算符索引。编号从1开始。 |

**退货：**
[Operator](../../com.aspose.pdf/operator) - 来自请求索引的运算符
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public void insert(int index, Operator op)
```


将运算符插入集合。

--------------------

示例演示如何将运算符插入页面内容。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q());

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 必须添加新运算符的索引 |
| op | [Operator](../../com.aspose.pdf/operator) | 将被插入的运算符 |

### insert(int at, Operator[] ops) {#insert-int-com.aspose.pdf.Operator---}
```
public void insert(int at, Operator[] ops)
```


在给定位置插入运算符。

--------------------

示例演示如何将运算符插入页面内容。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, 新运算符[]\ { 新的 com.aspose.pdf.operators.q(), 新的 com.aspose.pdf.operators.Q()\});

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| at | int | 运算符从中开始插入的索引。 |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | 要插入的运算符数组。每个运算符都可以有任何索引（默认情况下为 -1），因为它们的索引从 at 开始自动调整。 |

### insert(int at, Iterable<Operator> ops) {#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void insert(int at, Iterable<Operator> ops)
```


在给定位置插入运算符。

--------------------

示例演示如何将运算符插入页面内容。

文档 doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents();数组列表<Operator> opList = 新列表<Operator>(); opList.add(new com.aspose.pdf.operators.q()); opList.add(new com.aspose.pdf.operators.Q()); oc.insert(1, opList);

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| at | int | 运算符从中开始插入的索引。 |
| ops | java.lang.Iterable<com.aspose.pdf.Operator> | 要插入的运算符数组。 |

### isBracketed() {#isBracketed--}
```
public boolean isBracketed()
```


获取运算符序列的括号状态，即此运算符是否在 q - Q 块内

**退货：**
boolean - 布尔值
### isCommandsParsed() {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```


获取解析的命令

**退货：**
boolean - 布尔值
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


如果集合为空，则返回 TRUE。

**退货：**
boolean - 布尔值
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


指示天气集合仅限于快速文本提取

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Operator> iterator()
```


返回集合的枚举器

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.Operator> - 集合枚举器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Operator op) {#remove-com.aspose.pdf.Operator-}
```
public boolean remove(Operator op)
```


从集合中删除运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 要删除的运算符。 |

**退货：**
boolean - 如果找到并删除了运算符则为真。如果运算符不属于集合，则为 False。
### replace(Operator[] operators) {#replace-com.aspose.pdf.Operator---}
```
public void replace(Operator[] operators)
```


用其他运算符替换集合中的运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operators | [操作员\[\]](../../com.aspose.pdf/operator) | Operator[ 数组，它将替换集合中当前包含的运算符。列表中的每个运算符必须在范围内具有正确的索引[1..N] 其中 N 是集合中运算符的计数 |

### replace(Iterable<Operator> operators) {#replace-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void replace(Iterable<Operator> operators)
```


用其他运算符替换集合中的运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| operators | java.lang.Iterable<com.aspose.pdf.Operator> | 将替换当前包含在集合中的运算符的运算符列表。列表中的每个运算符必须在范围内具有正确的索引[1..N] 其中 N 是集合中运算符的计数 |

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


恢复文档更新。如果有任何未决更改，则更新内容流。

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public void set_Item(int index, Operator value)
```


通过索引设置运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 整数值 |
| value | [Operator](../../com.aspose.pdf/operator) | 运算符对象 |

### size() {#size--}
```
public int size()
```


获取集合中运算符的计数。

**退货：**
int - 整数值
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


禁止更新内容数据 内容流在调用 ResumeUpdate 之前不会更新

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


返回运算符列表。

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - 运算符列表。
### toString() {#toString--}
```
public String toString()
```


返回运算符的文本表示。

**退货：**
java.lang.String - 运算符的文本表示。
### updateData() {#updateData--}
```
public void updateData()
```


更新对象流。

### updateNormalizedData() {#updateNormalizedData--}
```
public void updateNormalizedData()
```


通过修复缺少的 GSave/GRestore 运算符来更新对象流。

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
