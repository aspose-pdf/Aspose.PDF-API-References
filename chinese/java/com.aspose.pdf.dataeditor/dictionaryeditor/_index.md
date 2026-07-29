---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "用于访问文档树字典（文档字典、页面字典、资源字典）的类。"
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

用于访问文档树字典（文档字典、页面字典、资源字典）的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException 资源为 null。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 将 ICosPdfPrimitive 设置到字典。 |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 将 {@link ICosPdfPrimitive} 设置到字典。 |
| [clear](#clear--) | 从 {@link DictionaryEditor} 中移除所有项。 |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 确定 DictionaryEditor 是否包含特定值。 |
| [containsKey](#containsKey-java.lang.String-) | 确定 {@link DictionaryEditor} 是否包含具有指定键的元素。 |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 将 DictionaryEditor 的元素复制到数组中，从特定的数组索引开始。 |
| [get_Item](#get_Item-java.lang.String-) | 获取或设置具有指定键的元素。 |
| [getAllKeys](#getAllKeys--) | 完整的键集合。包含可编辑和不可编辑的键。 |
| [getKeys](#getKeys--) | 可编辑键的集合。 |
| [getValues](#getValues--) | 获取包含 {@link DictionaryEditor} 中值的 {@link ICollection}。 |
| [isReadOnly](#isReadOnly--) | 获取指示 {@link DictionaryEditor} 是否只读的值。 |
| [iterator](#iterator--) | 返回一个遍历集合的枚举器。 |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 从 DictionaryEditor 中移除特定对象的第一次出现。 |
| [remove](#remove-java.lang.String-) | 从 {@link DictionaryEditor} 中移除具有指定键的元素。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | 获取或设置具有指定键的元素。 |
| [size](#size--) | 获取 {@link DictionaryEditor} 中包含的元素数量。 |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | 用于访问诸如 string、name、bool、number 等简单数据类型。对其他类型返回 null。 |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException 资源为 null。

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
将 ICosPdfPrimitive 设置到字典。

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
将 {@link ICosPdfPrimitive} 设置到字典。

### clear {#clear--}
```
public final void clear()
```

从 {@link DictionaryEditor} 中移除所有项。

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
确定 DictionaryEditor 是否包含特定值。

### containsKey {#containsKey-java.lang.String-}
确定 {@link DictionaryEditor} 是否包含具有指定键的元素。

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
将 DictionaryEditor 的元素复制到数组中，从特定的数组索引开始。

### get_Item {#get_Item-java.lang.String-}
获取或设置具有指定键的元素。

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

完整的键集合。包含可编辑和不可编辑的键。

**Returns:**
String 实例的可迭代对象

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

可编辑键的集合。

**Returns:**
String 实例的可迭代对象

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

获取包含 {@link DictionaryEditor} 中值的 {@link ICollection}。

**Returns:**
ICosPdfPrimitive 实例的可迭代对象

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取指示 {@link DictionaryEditor} 是否只读的值。

**Returns:**
如果 {@link DictionaryEditor} 为只读，则为 true；否则为 false。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

返回一个遍历集合的枚举器。

**Returns:**
一个可用于遍历集合的枚举器。

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
从 DictionaryEditor 中移除特定对象的第一次出现。

### remove {#remove-java.lang.String-}
从 {@link DictionaryEditor} 中移除具有指定键的元素。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
获取或设置具有指定键的元素。

### size {#size--}
```
public final int size()
```

获取 {@link DictionaryEditor} 中包含的元素数量。

**Returns:**
int 值

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
用于访问诸如 string、name、bool、number 等简单数据类型。对其他类型返回 null。
