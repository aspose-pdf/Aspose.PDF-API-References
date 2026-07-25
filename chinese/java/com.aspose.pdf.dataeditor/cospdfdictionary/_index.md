---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Aspose.PDF for Java API 参考"
description: "用于访问对象字典的类。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

用于访问对象字典的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | 从资源创建字典。@exception ArgumentNullException 资源为 null。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 将 ICosPdfPrimitive 设置到字典。 |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 将 {@link ICosPdfPrimitive} 设置到字典中。@exception ArgumentException 如果键/值无法编辑或删除则抛出异常。 |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 添加项对。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 添加项。 |
| [clear](#clear--) | 从 {@link CosPdfDictionary} 中移除所有项。 |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 确定 CosPdfDictionary 是否包含特定值。 |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 如果包含项则返回 true |
| [containsKey](#containsKey-java.lang.String-) | 确定 {@link CosPdfDictionary} 是否包含具有指定键的元素。 |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 将 CosPdfDictionary 的元素复制到数组中，从特定的数组索引开始。 |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 复制到数组 |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | 创建一个空字典，该字典将附加到文档。 |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | 创建一个空字典，该字典将附加到页面。 |
| [get_Item](#get_Item-java.lang.String-) | 获取或设置具有指定键的元素。 |
| [getAllKeys](#getAllKeys--) | 完整的键集合。包含可编辑和不可编辑的键。 |
| [getKeys](#getKeys--) | 可编辑键的集合。 |
| [getValues](#getValues--) | 获取一个 {@link ICollection}，其中包含 {@link CosPdfDictionary} 中的值。 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示 {@link CosPdfDictionary} 是否为只读。 |
| [iterator](#iterator--) | 返回一个遍历集合的枚举器。 |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 从 CosPdfDictionary 中移除特定对象的第一次出现。 |
| [remove](#remove-java.lang.String-) | 从 {@link CosPdfDictionary} 中移除具有指定键的元素。 |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 移除项目 |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | 按键移除项目。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 获取或设置具有指定键的元素。 @exception ArgumentNullException 键为 null。 @exception KeyNotFoundException 检索属性时未找到键。 @exception ArgumentException 如果键无法编辑/设置则抛出异常。 |
| [size](#size--) | 获取 {@link CosPdfDictionary} 中包含的元素数量。 |
| [toCosPdfDictionary](#toCosPdfDictionary--) | 尝试将此实例转换为 {@link CosPdfDictionary}。 |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | 用于访问诸如 string、name、bool、number 等简单数据类型。对其他类型返回 null。 |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 尝试获取值 |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
从资源创建字典。@exception ArgumentNullException 资源为 null。

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
将 ICosPdfPrimitive 设置到字典。

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
将 {@link ICosPdfPrimitive} 设置到字典中。@exception ArgumentException 如果键/值无法编辑或删除则抛出异常。

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
添加项对。

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
添加项。

### clear {#clear--}
```
public final void clear()
```

从 {@link CosPdfDictionary} 中移除所有项。

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
确定 CosPdfDictionary 是否包含特定值。

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
如果包含项则返回 true

### containsKey {#containsKey-java.lang.String-}
确定 {@link CosPdfDictionary} 是否包含具有指定键的元素。

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
将 CosPdfDictionary 的元素复制到数组中，从特定的数组索引开始。

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
复制到数组

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
创建一个空字典，该字典将附加到文档。

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
创建一个空字典，该字典将附加到页面。

### get_Item {#get_Item-java.lang.String-}
获取或设置具有指定键的元素。

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

完整的键集合。包含可编辑和不可编辑的键。

**Returns:**
String 值的列表

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

可编辑键的集合。

**Returns:**
String 值的列表

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

获取一个 {@link ICollection}，其中包含 {@link CosPdfDictionary} 中的值。

**Returns:**
ICosPdfPrimitive 实例的列表

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 {@link CosPdfDictionary} 是否为只读。

**Returns:**
如果 {@link CosPdfDictionary} 为只读，则为 true；否则为 false。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

返回一个遍历集合的枚举器。

**Returns:**
一个可用于遍历集合的枚举器。

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
从 CosPdfDictionary 中移除特定对象的第一次出现。

### remove {#remove-java.lang.String-}
从 {@link CosPdfDictionary} 中移除具有指定键的元素。

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
移除项目

### removeItemByKey {#removeItemByKey-java.lang.String-}
按键移除项目。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
获取或设置具有指定键的元素。 @exception ArgumentNullException 键为 null。 @exception KeyNotFoundException 检索属性时未找到键。 @exception ArgumentException 如果键无法编辑/设置则抛出异常。

### size {#size--}
```
public final int size()
```

获取 {@link CosPdfDictionary} 中包含的元素数量。

**Returns:**
int 值

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

尝试将此实例转换为 {@link CosPdfDictionary}。

**Returns:**
如果实例不是 {@link CosPdfDictionary} 则为 null，否则为 {@link CosPdfDictionary}。

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
用于访问诸如 string、name、bool、number 等简单数据类型。对其他类型返回 null。

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
尝试获取值
