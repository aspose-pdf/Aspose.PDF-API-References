---
title: PdfASymbolicFontEncodingStrategy
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类描述了在 TrueType 符号字体具有多种编码的情况下可用于调整复制编码数据过程的规则。
type: docs
weight: 274
url: /zh/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**遗产：**
java.lang.Object
```
public class PdfASymbolicFontEncodingStrategy
```

此类描述了在 TrueType 符号字体具有多种编码的情况下可用于调整复制编码数据过程的规则。某些 PDF 文档在转换为 PDF/A 格式后可能会出现错误“符号 TrueType 字体的 cmap 中有不止一种编码”。这个错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有特殊的表“cmap”。该表将字符代码映射到字形索引。并且该表可以包含不同的编码子表，这些子表描述了所使用的编码。请在 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html 查看有关 cmap 表的高级信息。通常cmap表包含多个编码子表，但PDF/A标准要求PDF/A文档中该字体只能留一个编码子表(3,0)。这里的关键问题 - 必须从另一个子表中获取哪些数据才能复制到目标编码表 (3,0) 中？大多数字体都有“格式良好”的 cmap 表，其中每个编码子表都与另一个子表完全一致。但是有些字体的 cmap 表存在冲突——例如，一个子表的 unicode 100 的字形索引为 100，而另一个子表的 unicode 100 的字形索引为 200。要解决这个问题，需要特殊的策略。默认使用以下策略：查找 mac subtable(1,0)。如果找到此表，则仅此数据用于填充目标表 (3,0)。如果没有找到 mac 子表，则迭代除 (3,0) 之外的所有子表并用于将数据复制到目标 (3,0) 子表中。此外，仅当目标表当前没有此 unicode 时，才会将每个 unicode(unicode, glyph index) 的映射复制到目标表中。因此，例如，如果第一个子表的 unicode 100 的字形索引为 100，而下一个子表的相同 unicode 100 的字形索引为 200，则仅复制第一个子表（unicode = 100，字形索引 = 100）中的数据。因此，之前的每个子表都优先于下一个。此类 PdfASymbolicFontEncodingStrategy 的属性有助于调整默认行为。如果设置了 QueueItem.CMapEncodingTableType 类型的属性 PreferredCmapEncodingTable，则相关子表将优先于 mac subtable(1,0) 使用。枚举 QueueItem.CMapEncodingTableType 中的值“MacTable”在这种情况下没有意义，因为它指向默认使用的同一个 mac 子表 (1,0)。属性 CmapEncodingTablesPriorityQueue 丢弃任何子表的所有优先级。如果设置了此属性，则只会按指定顺序使用已声明队列中的子表。如果未找到指定的子表，则将使用上述所有子表的默认迭代和复制策略。对象 QueueItem 指定使用的编码子表。该子表可以通过成员组合（PlatformID、PlatformSpecificID）或通过 QueueItem.CMapEncodingTableType 枚举来设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy()](#PdfASymbolicFontEncodingStrategy--) | 构造函数。 |
| [PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue)](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--) | 构造函数 |
| [PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)](#PdfASymbolicFontEncodingStrategy-short-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCmapEncodingTablesPriorityQueue()](#getCmapEncodingTablesPriorityQueue--) | 指定要处理的编码子表队列。 |
| [getPreferredCmapEncodingTable()](#getPreferredCmapEncodingTable--) | 指定优先于 mac subtable(1,0) 使用的子表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value)](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--) | 指定要处理的编码子表队列。 |
| [setPreferredCmapEncodingTable(short value)](#setPreferredCmapEncodingTable-short-) | 指定优先于 mac subtable(1,0) 使用的子表。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfASymbolicFontEncodingStrategy() {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```


构造函数。设置默认子表 (mac 1,0)

### PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue) {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--}
```
public PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| priorityQueue | com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> | 要迭代的编码子表队列 |

### PdfASymbolicFontEncodingStrategy(short preferredEncodingTable) {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| preferredEncodingTable | short | 优先于 mac subtable(1,0) 使用的编码子表 |

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
### getCmapEncodingTablesPriorityQueue() {#getCmapEncodingTablesPriorityQueue--}
```
public System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> getCmapEncodingTablesPriorityQueue()
```


指定要处理的编码子表队列。

**退货：**
com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> - QueueItem 的队列
### getPreferredCmapEncodingTable() {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```


指定优先于 mac subtable(1,0) 使用的子表。在这种情况下，枚举 QueueItem.CMapEncodingTableType 中的值“MacTable”没有任何意义。

**退货：**
short - CMapEncodingTableType 元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value) {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--}
```
public void setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value)
```


指定要处理的编码子表队列。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> | QueueItem 的队列 |

### setPreferredCmapEncodingTable(short value) {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```


指定优先于 mac subtable(1,0) 使用的子表。在这种情况下，枚举 QueueItem.CMapEncodingTableType 中的值“MacTable”没有任何意义。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | short | preferredEncodingTable 编码子表将优先于 mac 子表（1,0）使用 |

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
