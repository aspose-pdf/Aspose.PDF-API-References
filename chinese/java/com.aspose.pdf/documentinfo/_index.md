---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档的元信息。"
type: docs
weight: 1160
url: /zh/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

表示 PDF 文档的元信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | 初始化 DocumentInfo 实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | 向集合中添加具有指定键和值的元素。 |
| [clear](#clear--) | 清除文档信息。 |
| [clearCustomData](#clearCustomData--) | 仅清除自定义数据，保留所有其他预定义值（Title、Author 等）。 |
| [get_Item](#get_Item-java.lang.String-) | 获取与指定键关联的值。 |
| [getAuthor](#getAuthor--) | 获取文档作者。 |
| [getCreationDate](#getCreationDate--) | 获取文档创建日期。 |
| [getCreationTimeZone](#getCreationTimeZone--) | 创建日期的时区（以毫秒为单位）。 |
| [getCreator](#getCreator--) | 获取文档创建者。 |
| [getKeywords](#getKeywords--) | 获取文档的关键字。 |
| [getModDate](#getModDate--) | 获取文档修改日期。 |
| [getModTimeZone](#getModTimeZone--) | 修改日期的时区。 |
| [getProducer](#getProducer--) | 获取文档生成器。 |
| [getSubject](#getSubject--) | 获取文档主题。 |
| [getTitle](#getTitle--) | 获取文档标题。 |
| [getTrapped](#getTrapped--) | 获取 trapped 标志。 |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | 确定键是否为预定义（Title、Author 等），而非自定义。 |
| [remove](#remove-java.lang.String-) | 从集合中移除具有指定键的元素。 |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | 设置与指定键关联的值。 |
| [setAuthor](#setAuthor-java.lang.String-) | 设置文档作者。 |
| [setCreationDate](#setCreationDate-java.util.Date-) | 设置文档创建日期。 |
| [setCreationTimeZone](#setCreationTimeZone-double-) | 创建日期的时区（以毫秒为单位）。 |
| [setCreator](#setCreator-java.lang.String-) | 设置文档创建者。 |
| [setKeywords](#setKeywords-java.lang.String-) | 设置文档的关键字。 |
| [setModDate](#setModDate-java.util.Date-) | 设置文档修改日期。 |
| [setModTimeZone](#setModTimeZone-double-) | 修改日期的时区。 |
| [setProducer](#setProducer-java.lang.String-) | 设置文档生成器。 |
| [setSubject](#setSubject-java.lang.String-) | 设置文档主题。 |
| [setTitle](#setTitle-java.lang.String-) | 设置文档标题。 |
| [setTrapped](#setTrapped-java.lang.String-) | 设置 trapped 标志。 |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
初始化 DocumentInfo 实例。

### addItem {#addItem-java.lang.String-java.lang.String-}
向集合中添加具有指定键和值的元素。

### clear {#clear--}
```
public void clear()
```

清除文档信息。

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

仅清除自定义数据，保留所有其他预定义值（Title、Author 等）。

### get_Item {#get_Item-java.lang.String-}
获取与指定键关联的值。

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

获取文档作者。

**Returns:**
字符串值

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

获取文档创建日期。

**Returns:**
Date 对象

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

创建日期的时区（以毫秒为单位）。

**Returns:**
double 值

### getCreator {#getCreator--}
```
public String getCreator()
```

获取文档创建者。

**Returns:**
字符串值

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

获取文档的关键字。

**Returns:**
字符串值

### getModDate {#getModDate--}
```
public Date getModDate()
```

获取文档修改日期。

**Returns:**
Date 对象

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

修改日期的时区。

**Returns:**
double 值

### getProducer {#getProducer--}
```
public String getProducer()
```

获取文档生成器。

**Returns:**
字符串值

### getSubject {#getSubject--}
```
public String getSubject()
```

获取文档主题。

**Returns:**
字符串值

### getTitle {#getTitle--}
```
public String getTitle()
```

获取文档标题。

**Returns:**
字符串值

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

获取 trapped 标志。

**Returns:**
字符串值

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
确定键是否为预定义（Title、Author 等），而非自定义。

### remove {#remove-java.lang.String-}
从集合中移除具有指定键的元素。

### set_Item {#set_Item-java.lang.String-java.lang.String-}
设置与指定键关联的值。

### setAuthor {#setAuthor-java.lang.String-}
设置文档作者。

### setCreationDate {#setCreationDate-java.util.Date-}
设置文档创建日期。

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

创建日期的时区（以毫秒为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 以毫秒为单位 |

### setCreator {#setCreator-java.lang.String-}
设置文档创建者。

### setKeywords {#setKeywords-java.lang.String-}
设置文档的关键字。

### setModDate {#setModDate-java.util.Date-}
设置文档修改日期。

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

修改日期的时区。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setProducer {#setProducer-java.lang.String-}
设置文档生成器。

### setSubject {#setSubject-java.lang.String-}
设置文档主题。

### setTitle {#setTitle-java.lang.String-}
设置文档标题。

### setTrapped {#setTrapped-java.lang.String-}
设置 trapped 标志。
