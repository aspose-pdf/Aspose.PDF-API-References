---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示字体集合。 </p> <hr> <pre> 示例演示如何将页面上声明的所有字体设为嵌入。 // Open document Document doc = new.</pre>"
type: docs
weight: 1670
url: /zh/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> 表示字体集合。 </p> <hr> <pre> 示例演示如何将页面上声明的所有字体设为嵌入。 // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save(\"D:\\\\Tests\\\\input.pdf\"); </pre> <hr> <p> 由 {@code FontCollection} 类表示的字体集合在多种场景中使用。例如，在 {@code Resources.Fonts} 属性的资源中。</p>

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | 向集合中添加字体。 |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | 向字体资源中添加新字体，并返回自动分配的字体资源名称。 |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | 向字体集合中添加新字体。 |
| [add](#add-java.lang.String-java.lang.String-) | 向字体资源中添加具有指定基础字体名称的新字体条目。 |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * 将字体添加到集合中。 / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | 确定集合是否包含特定值。 |
| [contains](#contains-java.lang.String-) | 检查字体是否存在于字体集合中。 |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | 将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。 |
| [delete](#delete-java.lang.String-) | 删除具有指定资源名称的字体 |
| [get_Item](#get_Item-int-) | 获取指定索引处的字体元素。 |
| [get_Item](#get_Item-java.lang.String-) | 通过字体名称从集合中获取字体。如果未找到字体，将抛出异常。 |
| [getFontsDictionary](#getFontsDictionary--) | 获取 IPdfDictionary 对象 |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问集合的对象。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值 |
| [isSynchronized](#isSynchronized--) | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 返回整个集合的枚举器。 |
| [iterator](#iterator--) | 返回整个集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.Font-) | 从集合中删除指定的项。 |
| [size](#size--) | 获取集合中实际包含的 {@code Font} 对象元素的数量。 |

### add {#add-com.aspose.pdf.Font-}
向集合中添加字体。

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
向字体资源中添加新字体，并返回自动分配的字体资源名称。

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
向字体集合中添加新字体。

### add {#add-java.lang.String-java.lang.String-}
向字体资源中添加具有指定基础字体名称的新字体条目。

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * 将字体添加到集合中。 / * / *

### contains {#contains-com.aspose.pdf.Font-}
确定集合是否包含特定值。

### contains {#contains-java.lang.String-}
检查字体是否存在于字体集合中。

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。

### delete {#delete-java.lang.String-}
删除具有指定资源名称的字体

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

获取指定索引处的字体元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
字体对象。

### get_Item {#get_Item-java.lang.String-}
通过字体名称从集合中获取字体。如果未找到字体，将抛出异常。

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

获取 IPdfDictionary 对象

**Returns:**
IPdfDictionary 对象

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问集合的对象。

**Returns:**
用于同步的对象

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示集合是否为只读的值

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取指示对集合的访问是否已同步（线程安全）的值。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### remove {#remove-com.aspose.pdf.Font-}
从集合中删除指定的项。

### size {#size--}
```
public int size()
```

获取集合中实际包含的 {@code Font} 对象元素的数量。

**Returns:**
int 值
