---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Aspose.PDF for Java API 参考"
description: "注释外观字典，指定注释在页面上的视觉呈现方式。"
type: docs
weight: 150
url: /zh/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

注释外观字典，指定注释在页面上的视觉呈现方式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | 添加具有提供的键和值的元素。 |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 向字典中添加键和值对。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | 为指定的键添加 X 表单。 |
| [clear](#clear--) | 从字典中移除所有元素。 |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 检查指定的键值对是否包含在字典中。 |
| [containsKey](#containsKey-java.lang.String-) | 确定此字典是否包含指定的键。 |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * 返回字典的 IDictionaryEnumerator 对象。 / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 将 ICollection 的元素复制到数组中，从特定的数组索引开始。 |
| [get_Item](#get_Item-java.lang.String-) | 表示获取外观流的便捷形式。 |
| [getDict](#getDict--) | 获取 pdf 字典 |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state 值，其中 N - 正常外观，R - 悬停外观，D - 按下外观，state - 状态的名称（例如复选框的 On、Off）。 |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state 值，其中 N - 正常外观，R - 悬停外观，D - 按下外观，state - 状态的名称（例如复选框的 On、Off）。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问字典的对象。 |
| [getValues_](#getValues_--) | 获取字典值的列表。结果集合包含 XForm 对象的列表。 |
| [getValues](#getValues--) | 获取字典值的列表。结果集合包含 XForm 对象的列表。 |
| [isFixedSize](#isFixedSize--) | 获取指示字典是否具有固定大小的值。 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示字典是否为只读。 |
| [isSynchronized](#isSynchronized--) | 获取一个值，指示对字典的访问是否已同步（线程安全）。 |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | 集合的枚举器。 |
| [iterator](#iterator--) | 返回字典的 IDictionaryEnumerator 对象。 |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 从集合中移除键/值对。 |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | 从字典中移除键。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | 获取字典中包含的元素数量。 |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 尝试在字典中查找键，如果找到则检索值。 |

### add {#add-java.lang.Object-java.lang.Object-}
添加具有提供的键和值的元素。

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
向字典中添加键和值对。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
为指定的键添加 X 表单。

### clear {#clear--}
```
public void clear()
```

从字典中移除所有元素。

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
检查指定的键值对是否包含在字典中。

### containsKey {#containsKey-java.lang.String-}
确定此字典是否包含指定的键。

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * 返回字典的 IDictionaryEnumerator 对象。 / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
将 ICollection 的元素复制到数组中，从特定的数组索引开始。

### get_Item {#get_Item-java.lang.String-}
表示获取外观流的便捷形式。

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

获取 pdf 字典

**Returns:**
IPdfDictionary 对象

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

获取字典的键。如果外观字典具有子字典，则 {@code Keys} 包含 (N|R|D).state 值，其中 N 表示普通外观，R 表示悬停外观，D 表示按下外观，state 表示状态的名称（例如复选框的 On、Off）。

**Returns:**
String 值的列表

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

获取字典的键。如果外观字典具有子字典，则 {@code Keys} 包含 (N|R|D).state 值，其中 N 表示普通外观，R 表示悬停外观，D 表示按下外观，state 表示状态的名称（例如复选框的 On、Off）。

**Returns:**
String 值的列表

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问字典的对象。

**Returns:**
用于同步的对象

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

获取字典值的列表。结果集合包含 XForm 对象的列表。

**Returns:**
XForm 值的列表

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

获取字典值的列表。结果集合包含 XForm 对象的列表。

**Returns:**
XForm 值的列表

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

获取指示字典是否具有固定大小的值。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取一个值，指示字典是否为只读。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取一个值，指示对字典的访问是否已同步（线程安全）。

**Returns:**
布尔值

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

集合的枚举器。

**Returns:**
集合项的枚举器。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

返回字典的 IDictionaryEnumerator 对象。

**Returns:**
字典的枚举器。

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
从集合中移除键/值对。

### removeItemByKey {#removeItemByKey-java.lang.String-}
从字典中移除键。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

获取字典中包含的元素数量。

**Returns:**
int 值

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
尝试在字典中查找键，如果找到则检索值。
