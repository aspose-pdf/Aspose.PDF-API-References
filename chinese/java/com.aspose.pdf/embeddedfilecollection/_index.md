---
title: EmbeddedFileCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示嵌入式文件集合的类。
type: docs
weight: 97
url: /zh/java/com.aspose.pdf/embeddedfilecollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public class EmbeddedFileCollection implements Iterable<FileSpecification>
```

表示嵌入式文件集合的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(FileSpecification file)](#add-com.aspose.pdf.FileSpecification-) | 将嵌入式文件规范添加到集合中。 |
| [add(String key, FileSpecification file)](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | 使用指定的密钥将文件添加到嵌入文件。 |
| [clear()](#clear--) | 从文档中删除所有嵌入的文件。 |
| [contains(FileSpecification item)](#contains-com.aspose.pdf.FileSpecification-) | 确定集合是否包含指定的 FileSpecification。 |
| [copyTo(FileSpecification[] array, int index)](#copyTo-com.aspose.pdf.FileSpecification---int-) | 将 FileSpecification 对象数组复制到集合中。 |
| [delete()](#delete--) | 从文档中删除所有嵌入的文件。 |
| [delete(String name)](#delete-java.lang.String-) | 按名称删除嵌入文件。 |
| [deleteByKey(String key)](#deleteByKey-java.lang.String-) | 通过集合中的键从集合中删除文件。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByName(String name)](#findByName-java.lang.String-) | 按名称返回嵌入文件。 |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | 返回文件附件密钥列表。 |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对此集合的访问的对象。 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引获取嵌入文件。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 通过名称获取嵌入文件。 |
| [hashCode()](#hashCode--) |  |
| [isEmbeddedFilesExist()](#isEmbeddedFilesExist--) | 检查是否存在嵌入式文件结构。 |
| [isReadOnly()](#isReadOnly--) | 确定集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对此集合的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回集合枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | 返回集合枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(FileSpecification item)](#remove-com.aspose.pdf.FileSpecification-) | 从集合中移除指定的 FileSpecification。 |
| [size()](#size--) | 获取集合中嵌入文件的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(FileSpecification file) {#add-com.aspose.pdf.FileSpecification-}
```
public void add(FileSpecification file)
```


将嵌入式文件规范添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | [FileSpecification](../../com.aspose.pdf/filespecification) | 应添加到集合中的 FileSpecification。 |

### add(String key, FileSpecification file) {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
```
public void add(String key, FileSpecification file)
```


使用指定的密钥将文件添加到嵌入文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 键入嵌入的文件。 |
| file | [FileSpecification](../../com.aspose.pdf/filespecification) | 文件规范。 |

### clear() {#clear--}
```
public void clear()
```


从文档中删除所有嵌入的文件。

### contains(FileSpecification item) {#contains-com.aspose.pdf.FileSpecification-}
```
public boolean contains(FileSpecification item)
```


确定集合是否包含指定的 FileSpecification。不支持。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification 实例 |

**退货：**
boolean - 布尔值
### copyTo(FileSpecification[] array, int index) {#copyTo-com.aspose.pdf.FileSpecification---int-}
```
public void copyTo(FileSpecification[] array, int index)
```


将 FileSpecification 对象数组复制到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [FileSpecification\[\]](../../com.aspose.pdf/filespecification) | 将被复制的对象数组。 |
| index | int | 将从其开始复制的起始索引。 |

### delete() {#delete--}
```
public void delete()
```


从文档中删除所有嵌入的文件。

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


按名称删除嵌入文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 应删除的嵌入文件的名称。 |

### deleteByKey(String key) {#deleteByKey-java.lang.String-}
```
public void deleteByKey(String key)
```


通过集合中的键从集合中删除文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 字符串对象键名。 |

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
### findByName(String name) {#findByName-java.lang.String-}
```
public final FileSpecification findByName(String name)
```


按名称返回嵌入文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 文件的名称。 |

**退货：**
[FileSpecification](../../com.aspose.pdf/filespecification) - FileSpecification 实例文件规范对象（如果找到）；否则为空。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getKeys() {#getKeys--}
```
public final List<String> getKeys()
```


返回文件附件密钥列表。

**退货：**
java.util.List<java.lang.String> - 字符串值列表
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对此集合的访问的对象。

**退货：**
java.lang.Object - 同步对象
### get_Item(int index) {#get-Item-int-}
```
public FileSpecification get_Item(int index)
```


通过其索引获取嵌入文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 嵌入文件的索引。编号从1开始。 |

**退货：**
[FileSpecification](../../com.aspose.pdf/filespecification) - 检索嵌入式文件规范
### get_Item(String name) {#get-Item-java.lang.String-}
```
public FileSpecification get_Item(String name)
```


通过名称获取嵌入文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 嵌入式文件名。 |

**退货：**
[FileSpecification](../../com.aspose.pdf/filespecification) - 检索了嵌入式文件规范。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isEmbeddedFilesExist() {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```


检查是否存在嵌入式文件结构。如果结构存在则返回 TRUE，否则返回 FALSE。如果文档从未包含嵌入文件 - 此结构未创建且不存在。

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


确定集合是否为只读。总是返回错误。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对此集合的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<FileSpecification> iterator()
```


返回集合枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.FileSpecification> - colleciton 的枚举器。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<FileSpecification> iterator_Rename_Namesake()
```


返回集合枚举器。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.FileSpecification> - colleciton 的枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(FileSpecification item) {#remove-com.aspose.pdf.FileSpecification-}
```
public boolean remove(FileSpecification item)
```


从集合中移除指定的 FileSpecification。不支持。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification 实例 |

**退货：**
boolean - 布尔值
### size() {#size--}
```
public int size()
```


获取集合中嵌入文件的数量。

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
