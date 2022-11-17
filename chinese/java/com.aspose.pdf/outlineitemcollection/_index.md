---
title: OutlineItemCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 文档大纲层次结构中的大纲条目。
type: docs
weight: 240
url: /zh/java/com.aspose.pdf/outlineitemcollection/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Outlines](../../com.aspose.pdf/outlines)
```
public final class OutlineItemCollection extends Outlines
```

表示 PDF 文档大纲层次结构中的大纲条目。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OutlineItemCollection(IPdfObject outline)](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | 使用内部引擎大纲条目对象初始化此类的新实例。 |
| [OutlineItemCollection(OutlineCollection outlines)](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | 使用根层次结构对象初始化大纲项实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | 将大纲项添加到集合中。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | 尚不支持。 |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | 将大纲条目复制到 System.Array，从特定的 System.Array 索引开始。 |
| [delete()](#delete--) | 从文档大纲层次结构中删除此大纲项。 |
| [delete(String name)](#delete-java.lang.String-) | 从文档大纲层次结构中删除具有指定名称的大纲条目。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 获取此大纲项的操作。 |
| [getBold()](#getBold--) | 获取此大纲项的标题文本的粗体标记 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取此大纲项的标题文本的颜色。 |
| [getDestination()](#getDestination--) | 获取此大纲项的目的地。 |
| [getEngineDict()](#getEngineDict--) | 仅限内部 |
| [getEngineObj()](#getEngineObj--) | 仅限内部 |
| [getFirst()](#getFirst--) | 获取表示大纲层次结构中第一个顶级项的大纲项。 |
| [getItalic()](#getItalic--) | 获取此大纲项的标题文本的斜体标志 |
| [getLast()](#getLast--) | 获取表示大纲层次结构中最后一个顶级项的大纲项。 |
| [getLevel()](#getLevel--) | 获取大纲项的层次结构级别。 |
| [getNext()](#getNext--) | 获取表示大纲层次结构中相对于此项目的下一个项目的大纲项目。 |
| [getOpen()](#getOpen--) | 获取大纲项的打开状态（真/假）。 |
| [getParent()](#getParent--) | 获取大纲层次结构中此大纲项的父对象。 |
| [getPrev()](#getPrev--) | 获取表示大纲层次结构中相对于此项目的前一个项目的大纲项目。 |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对此集合的访问的对象。 |
| [getTitle()](#getTitle--) | 获取此大纲项的标题。 |
| [getVisibleCount()](#getVisibleCount--) | 获取文档大纲层次结构中所有级别的大纲项总数。 |
| [get_Item(int index)](#get-Item-int-) | 使用索引从集合中获取大纲项。 |
| [hasNext()](#hasNext--) | 检查大纲层次结构中代表下一个项目的大纲项目是否相对于此项目。 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, OutlineItemCollection outline)](#insert-int-com.aspose.pdf.OutlineItemCollection-) | 将大纲项插入到指定位置的集合中。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 获取指示对此集合的访问是否同步（线程安全）的值。 |
| [iterator()](#iterator--) | 返回循环访问集合的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [next()](#next--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | 尚不支持。 |
| [remove(int index)](#remove-int-) | 按索引删除项目。 |
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | 设置此大纲项的操作。 |
| [setBold(boolean value)](#setBold-boolean-) | 为该大纲项的标题文本设置粗体标志 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 设置此大纲项的标题文本的颜色。 |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | 设置此大纲项的目标。 |
| [setItalic(boolean value)](#setItalic-boolean-) | 为此大纲项的标题文本设置斜体标志 |
| [setOpen(boolean value)](#setOpen-boolean-) | 设置大纲项的打开状态（真/假）。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 设置此大纲项的标题。 |
| [size()](#size--) | 收集项目的计数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OutlineItemCollection(IPdfObject outline) {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
```
public OutlineItemCollection(IPdfObject outline)
```


使用内部引擎大纲条目对象初始化此类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outline | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | 大纲条目的内部引擎对象。 |

### OutlineItemCollection(OutlineCollection outlines) {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
```
public OutlineItemCollection(OutlineCollection outlines)
```


使用根层次结构对象初始化大纲项实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outlines | [OutlineCollection](../../com.aspose.pdf/outlinecollection) | 外出集合。 |

### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


将大纲项添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要添加的大纲项目。 |

### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public boolean contains(OutlineItemCollection item)
```


尚不支持。

总是抛出 NotImplementedException

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 要在集合中定位的对象 |

**退货：**
boolean - 布尔值 True - 如果找到项目；否则，假的。
### copyTo(OutlineItemCollection[] array, int index) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public void copyTo(OutlineItemCollection[] array, int index)
```


将大纲条目复制到 System.Array，从特定的 System.Array 索引开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | 作为目标的一维 System.Array。必须具有从零开始的索引。 |
| index | int | array 中从零开始的索引，复制从这里开始。 |

### delete() {#delete--}
```
public void delete()
```


从文档大纲层次结构中删除此大纲项。

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


从文档大纲层次结构中删除具有指定名称的大纲条目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 大纲条目的标题将被删除。 |

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
### getAction() {#getAction--}
```
public PdfAction getAction()
```


获取此大纲项的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 值
### getBold() {#getBold--}
```
public boolean getBold()
```


获取此大纲项的标题文本的粗体标记

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


获取此大纲项的标题文本的颜色。

**退货：**
[Color](../../java.awt/color) - 颜色值
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


获取此大纲项的目的地。

**退货：**
[IAppointment](../../com.aspose.pdf/iappointment) - 预约值
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


仅限内部

**退货：**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) IPdfDictionary 对象
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


仅限内部

**退货：**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) IPdfObject 对象
### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


获取表示大纲层次结构中第一个顶级项的大纲项。

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 值
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


获取此大纲项的标题文本的斜体标志

**退货：**
boolean - 布尔值
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


获取表示大纲层次结构中最后一个顶级项的大纲项。

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 值
### getLevel() {#getLevel--}
```
public int getLevel()
```


获取大纲项的层次结构级别。

**退货：**
int - 整数值
### getNext() {#getNext--}
```
public OutlineItemCollection getNext()
```


获取表示大纲层次结构中相对于此项目的下一个项目的大纲项目。

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 值
### getOpen() {#getOpen--}
```
public boolean getOpen()
```


获取大纲项的打开状态（真/假）。

**退货：**
boolean - 布尔值
### getParent() {#getParent--}
```
public Outlines getParent()
```


获取大纲层次结构中此大纲项的父对象。

**退货：**
[Outlines](../../com.aspose.pdf/outlines) 对象值
### getPrev() {#getPrev--}
```
public OutlineItemCollection getPrev()
```


获取表示大纲层次结构中相对于此项目的前一个项目的大纲项目。

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 值
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对此集合的访问的对象。

**退货：**
java.lang.Object - 对象值
### getTitle() {#getTitle--}
```
public String getTitle()
```


获取此大纲项的标题。

**退货：**
java.lang.String - 字符串值
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


获取文档大纲层次结构中所有级别的大纲项总数。

**退货：**
int - 整数值
### get_Item(int index) {#get-Item-int-}
```
public OutlineItemCollection get_Item(int index)
```


使用索引从集合中获取大纲项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中的索引。 |

**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) OutlineItemCollection 对象。
### hasNext() {#hasNext--}
```
public final boolean hasNext()
```


检查大纲层次结构中代表下一个项目的大纲项目是否相对于此项目。

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### insert(int index, OutlineItemCollection outline) {#insert-int-com.aspose.pdf.OutlineItemCollection-}
```
public void insert(int index, OutlineItemCollection outline)
```


将大纲项插入到指定位置的集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 指定插入位置的索引。 |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | 应插入大纲项目。 |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取指示对此集合的访问是否同步（线程安全）的值。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
```


返回循环访问集合的枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> - 一个 System.Collections.IEnumerator 对象，可用于遍历集合。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```




**退货：**
com.aspose.ms.System.Collections.IEnumerator
### next() {#next--}
```
public OutlineItemCollection next()
```




**退货：**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(OutlineItemCollection item) {#remove-com.aspose.pdf.OutlineItemCollection-}
```
public boolean remove(OutlineItemCollection item)
```


尚不支持。

总是抛出 NotImplementedException

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | OutlineItemCollection 实例 |

**退货：**
boolean - 布尔值 True - 如果项目被移除；否则，假的。
### remove(int index) {#remove-int-}
```
public final void remove(int index)
```


按索引删除项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的项目的索引。 |

### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


设置此大纲项的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PDF操作值 |

### setBold(boolean value) {#setBold-boolean-}
```
public void setBold(boolean value)
```


为该大纲项的标题文本设置粗体标志

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


设置此大纲项的标题文本的颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color | 颜色对象 |

### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


设置此大纲项的目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | 预约值 |

### setItalic(boolean value) {#setItalic-boolean-}
```
public void setItalic(boolean value)
```


为此大纲项的标题文本设置斜体标志

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


设置大纲项的打开状态（真/假）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


设置此大纲项的标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### size() {#size--}
```
public int size()
```


收集项目的计数。请不要与 VisibleCount 混淆：VisibleCount 获取所有级别的可见大纲项的数量。

**退货：**
整数
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
