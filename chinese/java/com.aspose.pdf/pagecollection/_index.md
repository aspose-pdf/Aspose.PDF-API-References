---
title: PageCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: PDF文档页面的集合。
type: docs
weight: 259
url: /zh/java/com.aspose.pdf/pagecollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable，com.aspose.pdf.ISupportsMemoryCleanup
```
public final class PageCollection implements Iterable<Page>, ISupportsMemoryCleanup
```

PDF文档页面的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | 接受 AnnotationSelector 访问者对象，该对象提供使用注释的功能。 |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | 接受 ImagePlacementAbsorber 访问者对象，该访问者对象提供处理图像放置对象的功能。 |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | 接受提供处理文本对象功能的 TextAbsorber 访问者对象。 |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | 接受提供处理文本对象功能的 TextFragmentAbsorber 访问者对象。 |
| [add()](#add--) | 添加空白页 |
| [add(Page entity)](#add-com.aspose.pdf.Page-) | 将页面添加到集合。 |
| [add(Page[] pages)](#add-com.aspose.pdf.Page---) | 将数组中的所有页面添加到集合中。 |
| [add(Iterable<Page> pages)](#add-java.lang.Iterable-com.aspose.pdf.Page--) | 将列表中的所有页面添加到集合中。 |
| [add(List<Page> pages)](#add-java.util.List-com.aspose.pdf.Page--) | 将列表中的所有页面添加到集合中。 |
| [add_Rename_Namesake(Page entity)](#add-Rename-Namesake-com.aspose.pdf.Page-) | 将页面添加到集合。 |
| [clear()](#clear--) | 清除页面集合。 |
| [contains(Page item)](#contains-com.aspose.pdf.Page-) | 确定此实例是否包含该对象。 |
| [copyTo(Page[] array, int index)](#copyTo-com.aspose.pdf.Page---int-) | 将页面复制到文档中。 |
| [delete()](#delete--) | 从集合中删除所有页面。 |
| [delete(int index)](#delete-int-) | 删除指定页面。 |
| [delete(Integer[] pages)](#delete-java.lang.Integer---) | 删除指定数组中指定编号的页面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByPdfObject(IPdfObject pdfObject)](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten()](#flatten--) | 删除位于页面上的所有字段并改为放置它们的值。 |
| [freeMemory()](#freeMemory--) | 清除缓存数据 |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取集合的同步对象。 |
| [getUnrestricted(int index)](#getUnrestricted-int-) | 按索引返回页面。 |
| [get_Item(int index)](#get-Item-int-) | 按索引获取页面。 |
| [hashCode()](#hashCode--) |  |
| [indexOf(Page entity)](#indexOf-com.aspose.pdf.Page-) | 返回指定页面的索引。 |
| [insert(int pageNumber)](#insert-int-) | 将空的 apge 插入到指定位置的集合中。 |
| [insert(int pageNumber, Page entity)](#insert-int-com.aspose.pdf.Page-) | 在指定位置将页面插入页面集合。 |
| [insert(int pageNumber, Page[] pages)](#insert-int-com.aspose.pdf.Page---) | 将数组的页面插入到文档中。 |
| [insert(int pageNumber, Iterable<Page> pages)](#insert-int-java.lang.Iterable-com.aspose.pdf.Page--) | 将集合中的页面插入到文档中。 |
| [insert(int pageNumber, List<Page> pages)](#insert-int-java.util.List-com.aspose.pdf.Page--) | 将集合中的页面插入到文档中。 |
| [isEmpty()](#isEmpty--) | 如果集合为空，则返回 TRUE。 |
| [isReadOnly()](#isReadOnly--) | 获取表示集合的值是只读的。 |
| [isSynchronized()](#isSynchronized--) | 返回 true 对象已同步。 |
| [iterator()](#iterator--) | 返回页面的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Page item)](#remove-com.aspose.pdf.Page-) | 删除指定的项目，抛出异常。 |
| [size()](#size--) | 获取文档中的页数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


接受 AnnotationSelector 访问者对象，该对象提供使用注释的功能。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | AnnotationSelector 访问者 |

### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


接受 ImagePlacementAbsorber 访问者对象，该访问者对象提供处理图像放置对象的功能。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) | 图像放置对象。 |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


接受提供处理文本对象功能的 TextAbsorber 访问者对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) | 文本吸收器对象。 |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


接受提供处理文本对象功能的 TextFragmentAbsorber 访问者对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) | 文本片段吸收器对象。 |

### add() {#add--}
```
public Page add()
```


添加空白页

**退货：**
[Page](../../com.aspose.pdf/page) - 添加页面。
### add(Page entity) {#add-com.aspose.pdf.Page-}
```
public Page add(Page entity)
```


将页面添加到集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | 应添加的页面。 |

**退货：**
[Page](../../com.aspose.pdf/page) - 添加页面。
### add(Page[] pages) {#add-com.aspose.pdf.Page---}
```
public void add(Page[] pages)
```


将数组中的所有页面添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pages | [Page\[\]](../../com.aspose.pdf/page) | 将添加的页面数组。 |

### add(Iterable<Page> pages) {#add-java.lang.Iterable-com.aspose.pdf.Page--}
```
public void add(Iterable<Page> pages)
```


将列表中的所有页面添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pages | java.lang.Iterable<com.aspose.pdf.Page> | 包含必须添加的所有页面的列表。 |

### add(List<Page> pages) {#add-java.util.List-com.aspose.pdf.Page--}
```
public void add(List<Page> pages)
```


将列表中的所有页面添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pages | java.util.List<com.aspose.pdf.Page> | 包含必须添加的所有页面的列表。 |

### add_Rename_Namesake(Page entity) {#add-Rename-Namesake-com.aspose.pdf.Page-}
```
public void add_Rename_Namesake(Page entity)
```


将页面添加到集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | 应添加的页面。 |

### clear() {#clear--}
```
public void clear()
```


清除页面集合。

### contains(Page item) {#contains-com.aspose.pdf.Page-}
```
public boolean contains(Page item)
```


确定此实例是否包含该对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Page](../../com.aspose.pdf/page) | 页面实例 |

**退货：**
boolean - 布尔值 true 如果[包含][指明项目]；否则，假的。
### copyTo(Page[] array, int index) {#copyTo-com.aspose.pdf.Page---int-}
```
public void copyTo(Page[] array, int index)
```


将页面复制到文档中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [Page\[\]](../../com.aspose.pdf/page) | 包含要插入到文档中的 Pages 对象的数组。它必须是对象[或页面[]. |
| index | int | 将插入页面的起始索引 |

### delete() {#delete--}
```
public void delete()
```


从集合中删除所有页面。

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


删除指定页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将被删除的页数。页码从 1 开始。 |

### delete(Integer[] pages) {#delete-java.lang.Integer---}
```
public void delete(Integer[] pages)
```


删除指定数组中指定编号的页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pages | java.lang.Integer[] | 要删除的页面数组。 |

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
### findByPdfObject(IPdfObject pdfObject) {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}
```
public final Page findByPdfObject(IPdfObject pdfObject)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfObject | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

**退货：**
[Page](../../com.aspose.pdf/page)
### flatten() {#flatten--}
```
public void flatten()
```


删除位于页面上的所有字段并改为放置它们的值。

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


清除缓存数据

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取集合的同步对象。

**退货：**
java.lang.Object - 同步对象
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```


按索引返回页面。页 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 请求页面的索引。页码从 1 开始。 |

**退货：**
[Page](../../com.aspose.pdf/page) - 请求的页面
### get_Item(int index) {#get-Item-int-}
```
public Page get_Item(int index)
```


按索引获取页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 页面索引。 |

**退货：**
[Page](../../com.aspose.pdf/page) - 检索页面。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### indexOf(Page entity) {#indexOf-com.aspose.pdf.Page-}
```
public int indexOf(Page entity)
```


返回指定页面的索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | 页面对象。页码从 1 开始。

--------------------

页码从 1 开始。如果集合不包含该页，则返回 0。|

**退货：**
int - 集合中页面的索引。
### insert(int pageNumber) {#insert-int-}
```
public Page insert(int pageNumber)
```


将空的 apge 插入到指定位置的集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 新页面的位置。 |

**退货：**
[Page](../../com.aspose.pdf/page) - 插入的页面。
### insert(int pageNumber, Page entity) {#insert-int-com.aspose.pdf.Page-}
```
public Page insert(int pageNumber, Page entity)
```


在指定位置将页面插入页面集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 集合中必需的页面索引。 |
| entity | [Page](../../com.aspose.pdf/page) | 要插入的页面。 |

**退货：**
[Page](../../com.aspose.pdf/page) - 插入的页面。
### insert(int pageNumber, Page[] pages) {#insert-int-com.aspose.pdf.Page---}
```
public void insert(int pageNumber, Page[] pages)
```


将数组的页面插入到文档中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 新页面的起始编号。 |
| pages | [Page\[\]](../../com.aspose.pdf/page) | 将插入的页面数组。 |

### insert(int pageNumber, Iterable<Page> pages) {#insert-int-java.lang.Iterable-com.aspose.pdf.Page--}
```
public void insert(int pageNumber, Iterable<Page> pages)
```


将集合中的页面插入到文档中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 新页面的起始位置。 |
| pages | java.lang.Iterable<com.aspose.pdf.Page> | 页面集合。 |

### insert(int pageNumber, List<Page> pages) {#insert-int-java.util.List-com.aspose.pdf.Page--}
```
public void insert(int pageNumber, List<Page> pages)
```


将集合中的页面插入到文档中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 新页面的起始位置。 |
| pages | java.util.List<com.aspose.pdf.Page> | 页面集合。 |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


如果集合为空，则返回 TRUE。

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取表示集合的值是只读的。总是返回错误。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


返回 true 对象已同步。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public Iterator<Page> iterator()
```


返回页面的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.Page> - 页面枚举器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Page item) {#remove-com.aspose.pdf.Page-}
```
public boolean remove(Page item)
```


删除指定的项目，抛出异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [Page](../../com.aspose.pdf/page) | 页面实例 |

**退货：**
boolean - 布尔值
### size() {#size--}
```
public int size()
```


获取文档中的页数。

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
