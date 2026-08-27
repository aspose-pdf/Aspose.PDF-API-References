---
title: "元数据"
linktitle: "元数据"
second_title: "Aspose.PDF for Java API 参考"
description: "提供对 XMP 元数据流的访问。"
type: docs
weight: 3050
url: /zh/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

提供对 XMP 元数据流的访问。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 向字典中添加键和值对。 |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | 向元数据添加值。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | 向元数据添加 pdf 扩展。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | 向元数据添加值。 |
| [clear](#clear--) | 清除元数据。 |
| [contains](#contains-java.lang.String-) | 检查键是否包含在元数据中。 |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 检查指定的键值对是否包含在字典中。 |
| [containsKey](#containsKey-java.lang.String-) | 确定此字典是否包含指定的键。 |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | 将集合的元素复制到数组中。 |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 将集合的元素复制到数组中。 |
| [get_Item](#get_Item-java.lang.String-) | 从元数据获取数据。 |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | 仅供内部使用。获取扩展字段的字典。 |
| [getExtensionFields](#getExtensionFields--) | <p> 获取扩展字段的字典。 </p> |
| [getItem](#getItem-java.lang.String-) | 从元数据获取数据。 |
| [getKeys](#getKeys--) | 获取元数据键的集合。 |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | 通过前缀返回命名空间 URI。 |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | 通过命名空间 URI 返回前缀。 |
| [getSyncRoot](#getSyncRoot--) | 获取集合同步对象。 |
| [getValues](#getValues--) | 获取元数据中的值。 |
| [isFixedSize](#isFixedSize--) | 检查 colleciton 是否具有固定大小。 |
| [isReadOnly](#isReadOnly--) | 检查集合是否为只读。 |
| [isSynchronized](#isSynchronized--) | 检查集合是否已同步。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | 返回字典枚举器。 |
| [iteratorIE](#iteratorIE--) | 获取集合的枚举器。 |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | 注册命名空间 URI。 |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | 注册命名空间 URI。 |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 从 colleciton 中移除键/值对。 |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | 从元数据中移除条目。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | 从元数据设置数据。 |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | 从元数据设置数据。 |
| [size](#size--) | 获取集合中元素的计数。 |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 尝试在字典中查找键，如果找到则检索值。 |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | 尝试在字典中查找键，如果找到则检索值。 |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
向字典中添加键和值对。

### addItem {#addItem-java.lang.String-java.lang.Object-}
向元数据添加值。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
向元数据添加 pdf 扩展。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
向元数据添加值。

### clear {#clear--}
```
public void clear()
```

清除元数据。

### contains {#contains-java.lang.String-}
检查键是否包含在元数据中。

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
检查指定的键值对是否包含在字典中。

### containsKey {#containsKey-java.lang.String-}
确定此字典是否包含指定的键。

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
将集合的元素复制到数组中。

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
将集合的元素复制到数组中。

### get_Item {#get_Item-java.lang.String-}
从元数据获取数据。

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

仅供内部使用。获取扩展字段的字典。

**Returns:**
内部对象

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> 获取扩展字段的字典。 </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} 对象

### getItem {#getItem-java.lang.String-}
从元数据获取数据。

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

获取元数据键的集合。

**Returns:**
ICollection 对象

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
通过前缀返回命名空间 URI。

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
通过命名空间 URI 返回前缀。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取集合同步对象。

**Returns:**
用于同步的对象

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

获取元数据中的值。

**Returns:**
ICollection 对象

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

检查 colleciton 是否具有固定大小。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

检查集合是否为只读。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

检查集合是否已同步。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

返回字典枚举器。

**Returns:**
枚举器。

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

获取集合的枚举器。

**Returns:**
IEnumerator 对象 @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
注册命名空间 URI。

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
注册命名空间 URI。

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
从 colleciton 中移除键/值对。

### removeItemByKey {#removeItemByKey-java.lang.String-}
从元数据中移除条目。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
从元数据设置数据。

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
从元数据设置数据。

### size {#size--}
```
public int size()
```

获取集合中元素的计数。

**Returns:**
int 值

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
尝试在字典中查找键，如果找到则检索值。

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
尝试在字典中查找键，如果找到则检索值。
