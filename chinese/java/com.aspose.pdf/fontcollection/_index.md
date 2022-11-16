---
title: FontCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示字体集合。
type: docs
weight: 132
url: /zh/java/com.aspose.pdf/fontcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class FontCollection implements Iterable<Font>
```

表示字体集合。

--------------------

```
The example demonstrates how to make all font declared on page as embedded.


 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // ensure all fonts declared on page resources are embedded
 // note that if fonts are declared on form resources they are not accessible from page resources
 for(com.aspsoe.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts())
 {
     if(!font.isEmbedded())
         font.isEmbedded(true);
 }
 doc.save("D:\\Tests\\input.pdf");
```

--------------------

FontCollection 类表示的字体集合用于多种场景。例如，在具有 Resources.Fonts 属性的资源中。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Font fragment)](#add-com.aspose.pdf.Font-) | 将字体添加到集合中。 |
| [add(Font newFont, String[] resName)](#add-com.aspose.pdf.Font-java.lang.String---) | 向字体资源添加新字体并返回自动分配的字体资源名称。 |
| [add(String resName, IPdfObject newFont)](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | 将新字体添加到字体集合中。 |
| [add(String resName, String baseFontName)](#add-java.lang.String-java.lang.String-) | 向字体资源添加具有指定基本字体名称的新字体条目。 |
| [clear_Rename_Namesake()](#clear-Rename-Namesake--) | 清除集合中的所有项目。 |
| [contains(Font item)](#contains-com.aspose.pdf.Font-) | 确定集合是否包含特定值。 |
| [contains(String name)](#contains-java.lang.String-) | 检查字体集合中是否存在字体。 |
| [copyTo(Font[] array, int index)](#copyTo-com.aspose.pdf.Font---int-) | 将整个集合复制到兼容的一维数组，从目标数组的指定索引开始 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHash()](#getHash--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对集合的访问的对象。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的字体元素。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 按字体名称从集合中获取字体。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回整个集合的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | 返回整个集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Font item)](#remove-com.aspose.pdf.Font-) | 从集合中删除指定的项目。 |
| [size()](#size--) | 获取集合中实际包含的 Font 对象元素的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Font fragment) {#add-com.aspose.pdf.Font-}
```
public void add(Font fragment)
```


将字体添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fragment | [Font](../../com.aspose.pdf/font) | 字体对象 |

### add(Font newFont, String[] resName) {#add-com.aspose.pdf.Font-java.lang.String---}
```
public void add(Font newFont, String[] resName)
```


向字体资源添加新字体并返回自动分配的字体资源名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newFont | [Font](../../com.aspose.pdf/font) | 字体对象。 |
| resName | java.lang.String[] | 自动分配的资源项名称。 |

### add(String resName, IPdfObject newFont) {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
```
public void add(String resName, IPdfObject newFont)
```


将新字体添加到字体集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resName | java.lang.String | 字符串对象 |
| newFont | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | IPDFObject 对象 |

### add(String resName, String baseFontName) {#add-java.lang.String-java.lang.String-}
```
public void add(String resName, String baseFontName)
```


向字体资源添加具有指定基本字体名称的新字体条目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resName | java.lang.String | 字符串对象 |
| baseFontName | java.lang.String | 字符串对象 |

### clear_Rename_Namesake() {#clear-Rename-Namesake--}
```
public void clear_Rename_Namesake()
```


清除集合中的所有项目。

### contains(Font item) {#contains-com.aspose.pdf.Font-}
```
public boolean contains(Font item)
```


确定集合是否包含特定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Font](../../com.aspose.pdf/font) | 要在集合中定位的对象 |

**退货：**
boolean - 如果在集合中找到项目则为 true；否则，假的。
### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


检查字体集合中是否存在字体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字体名称。 |

**退货：**
布尔值 - 如果集合包含具有指定名称的字体，则为真。
### copyTo(Font[] array, int index) {#copyTo-com.aspose.pdf.Font---int-}
```
public void copyTo(Font[] array, int index)
```


将整个集合复制到兼容的一维数组，从目标数组的指定索引开始

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [Font\[\]](../../com.aspose.pdf/font) | 将被复制的对象数组。 |
| index | int | 将从其开始复制的起始索引。 |

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
### getHash() {#getHash--}
```
public HashDictionary<String,Font> getHash()
```




**退货：**
[HashDictionary](../../com.aspose.pdf.engine.collections/hashdictionary)
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对集合的访问的对象。

**退货：**
java.lang.Object - 同步对象
### get_Item(int index) {#get-Item-int-}
```
public Font get_Item(int index)
```


获取指定索引处的字体元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中的索引。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public Font get_Item(String name)
```


按字体名称从集合中获取字体。如果找不到字体，则抛出异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字体名称。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 找到字体。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对集合的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public Iterator<Font> iterator()
```


返回整个集合的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.Font> - 枚举器对象。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


返回整个集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator - 枚举器对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Font item) {#remove-com.aspose.pdf.Font-}
```
public boolean remove(Font item)
```


从集合中删除指定的项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Font](../../com.aspose.pdf/font) | 要删除的对象 |

**退货：**
布尔值 - 如果项目已从集合中删除，则为 true；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中实际包含的 Font 对象元素的数量。

**退货：**
int - 整数值
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
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
