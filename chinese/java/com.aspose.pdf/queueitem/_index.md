---
title: PdfASymbolicFontEncodingStrategy.QueueItem
second_title: 用于 Java API 参考的 Aspose.PDF
description: 指定编码子表。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**遗产：**
java.lang.Object
```
public static class PdfASymbolicFontEncodingStrategy.QueueItem
```

指定编码子表。每个编码子表都有唯一的参数组合（PlatformID、PlatformSpecificID）。实施枚举 CMapEncodingTableType 和属性 CMapEncodingTable 以简化所需的编码子表集。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QueueItem()](#QueueItem--) | 构造函数，默认指定mac subtable(1,0) |
| [QueueItem(int platformID, int platformSpecificID)](#QueueItem-int-int-) | 构造函数 |
| [QueueItem(short cmapTable)](#QueueItem-short-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCMapEncodingTable()](#getCMapEncodingTable--) | 通过 CMapEncodingTableType 枚举指定编码子表 |
| [getClass()](#getClass--) |  |
| [getPlatformId()](#getPlatformId--) | 编码子表的平台标识符 |
| [getPlatformSpecificId()](#getPlatformSpecificId--) | 编码子表的平台特定编码标识符 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCMapEncodingTable(short value)](#setCMapEncodingTable-short-) | 通过 CMapEncodingTableType 枚举指定编码子表 |
| [setPlatformId(int value)](#setPlatformId-int-) | 编码子表的平台标识符 |
| [setPlatformSpecificId(int value)](#setPlatformSpecificId-int-) | 编码子表的平台特定编码标识符 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QueueItem() {#QueueItem--}
```
public QueueItem()
```


构造函数，默认指定mac subtable(1,0)

### QueueItem(int platformID, int platformSpecificID) {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| platformID | int | 编码子表的平台标识符 |
| platformSpecificID | int | 编码子表的平台特定编码标识符 |

### QueueItem(short cmapTable) {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cmapTable | short | 编码子表 |

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
### getCMapEncodingTable() {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```


通过 CMapEncodingTableType 枚举指定编码子表

**退货：**
短编码子表
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getPlatformId() {#getPlatformId--}
```
public int getPlatformId()
```


编码子表的平台标识符

**退货：**
int - 整数值
### getPlatformSpecificId() {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```


编码子表的平台特定编码标识符

**退货：**
int - 整数值
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




### setCMapEncodingTable(short value) {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```


通过 CMapEncodingTableType 枚举指定编码子表

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 编码子表 |

### setPlatformId(int value) {#setPlatformId-int-}
```
public void setPlatformId(int value)
```


编码子表的平台标识符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPlatformSpecificId(int value) {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```


编码子表的平台特定编码标识符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

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
