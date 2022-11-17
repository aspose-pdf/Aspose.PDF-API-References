---
title: DocumentInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 文档的元信息。
type: docs
weight: 94
url: /zh/java/com.aspose.pdf/documentinfo/
---
**遗产：**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary
```
public final class DocumentInfo extends System.Collections.Generic.Dictionary<String,String>
```

表示 PDF 文档的元信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentInfo(IDocument document)](#DocumentInfo-com.aspose.pdf.IDocument-) | 初始化 DocumentInfo 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem(TKey arg0, TValue arg1)](#addItem-TKey-TValue-) |  |
| [addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [addItem(String key, String value)](#addItem-java.lang.String-java.lang.String-) | 将具有指定键和值的元素添加到集合中。 |
| [clear()](#clear--) | 清除文档信息。 |
| [clearCustomData()](#clearCustomData--) | 仅清除自定义数据，保留所有其他预定义值（标题、作者等）。 |
| [containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [containsKey(TKey arg0)](#containsKey-TKey-) |  |
| [containsValue(TValue arg0)](#containsValue-TValue-) |  |
| [copyTo(System.Array arg0, int arg1)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue----int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthor()](#getAuthor--) | 获取文档作者。 |
| [getClass()](#getClass--) |  |
| [getComparer()](#getComparer--) |  |
| [getCreationDate()](#getCreationDate--) | 获取文档创建日期。 |
| [getCreationTimeZone()](#getCreationTimeZone--) | 创建日期的时区（以毫秒为单位）。 |
| [getCreator()](#getCreator--) | 获取文档创建者。 |
| [getDictionaryEntryEnumerator()](#getDictionaryEntryEnumerator--) |  |
| [getKeys()](#getKeys--) |  |
| [getKeywords()](#getKeywords--) | 获取文档的关键字。 |
| [getModDate()](#getModDate--) | 获取文档修改日期。 |
| [getModTimeZone()](#getModTimeZone--) | 修改日期的时区。 |
| [getProducer()](#getProducer--) | 获取文档制作者。 |
| [getSubject()](#getSubject--) | 获取文档的主题。 |
| [getSyncRoot()](#getSyncRoot--) |  |
| [getTitle()](#getTitle--) | 获取文档标题。 |
| [getTrapped()](#getTrapped--) | 获得被困旗帜。 |
| [getValues()](#getValues--) |  |
| [get_Item(TKey arg0)](#get-Item-TKey-) |  |
| [get_Item(String key)](#get-Item-java.lang.String-) | 获取与指定键关联的值。 |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) |  |
| [isPredefinedKey(String key)](#isPredefinedKey-java.lang.String-) | 确定密钥是否是预定义的（标题、作者等），而不是自定义的。 |
| [isReadOnly()](#isReadOnly--) |  |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 从集合中移除具有指定键的元素。 |
| [removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [removeItemByKey(TKey arg0)](#removeItemByKey-TKey-) |  |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 设置文档作者。 |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | 设置文档创建日期。 |
| [setCreationTimeZone(double value)](#setCreationTimeZone-double-) | 创建日期的时区（以毫秒为单位）。 |
| [setCreator(String value)](#setCreator-java.lang.String-) | 设置文档创建者。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 设置文档的关键字。 |
| [setModDate(Date value)](#setModDate-java.util.Date-) | 设置文档修改日期。 |
| [setModTimeZone(double value)](#setModTimeZone-double-) | 修改日期的时区。 |
| [setProducer(String value)](#setProducer-java.lang.String-) | 设置文档制作者。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 设置文档的主题。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 设置文档标题。 |
| [setTrapped(String value)](#setTrapped-java.lang.String-) | 设置被困标志。 |
| [set_Item(TKey arg0, TValue arg1)](#set-Item-TKey-TValue-) |  |
| [set_Item(String key, String value)](#set-Item-java.lang.String-java.lang.String-) | 设置与指定键关联的值。 |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [tryGetValue(TKey arg0, Object[] arg1)](#tryGetValue-TKey-java.lang.Object---) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentInfo(IDocument document) {#DocumentInfo-com.aspose.pdf.IDocument-}
```
public DocumentInfo(IDocument document)
```


初始化 DocumentInfo 实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 该文档的信息将用于初始化。 |

### addItem(TKey arg0, TValue arg1) {#addItem-TKey-TValue-}
```
public void addItem(TKey arg0, TValue arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | TValue |  |

### addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

### addItem(String key, String value) {#addItem-java.lang.String-java.lang.String-}
```
public void addItem(String key, String value)
```


将具有指定键和值的元素添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要添加的元素的键。 |
| value | java.lang.String | 要添加的元素的值。该值可以为空。 |

### clear() {#clear--}
```
public void clear()
```


清除文档信息。

### clearCustomData() {#clearCustomData--}
```
public void clearCustomData()
```


仅清除自定义数据，保留所有其他预定义值（标题、作者等）。

### containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

**退货：**
布尔值
### containsKey(TKey arg0) {#containsKey-TKey-}
```
public boolean containsKey(TKey arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TKey |  |

**退货：**
布尔值
### containsValue(TValue arg0) {#containsValue-TValue-}
```
public boolean containsValue(TValue arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TValue |  |

**退货：**
布尔值
### copyTo(System.Array arg0, int arg1) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Array |  |
| arg1 | int |  |

### copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue>[] |  |
| arg1 | int |  |

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
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


获取文档作者。

**退货：**
java.lang.String - 字符串值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getComparer() {#getComparer--}
```
public System.Collections.Generic.IGenericEqualityComparer<TKey> getComparer()
```




**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEqualityComparer<TKey>
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


获取文档创建日期。

**退货：**
[Date](../../java.util/date) - 日期对象
### getCreationTimeZone() {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```


创建日期的时区（以毫秒为单位）。

**退货：**
双倍价值
### getCreator() {#getCreator--}
```
public String getCreator()
```


获取文档创建者。

**退货：**
java.lang.String - 字符串值
### getDictionaryEntryEnumerator() {#getDictionaryEntryEnumerator--}
```
public System.Collections.IEnumerable<System.Collections.DictionaryEntry> getDictionaryEntryEnumerator()
```




**退货：**
com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.DictionaryEntry>
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<TKey,TValue> getKeys()
```




**退货：**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<TKey,TValue>
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


获取文档的关键字。

**退货：**
java.lang.String - 字符串值
### getModDate() {#getModDate--}
```
public Date getModDate()
```


获取文档修改日期。

**退货：**
[Date](../../java.util/date) - 日期对象
### getModTimeZone() {#getModTimeZone--}
```
public double getModTimeZone()
```


修改日期的时区。

**退货：**
双倍价值
### getProducer() {#getProducer--}
```
public String getProducer()
```


获取文档制作者。

**退货：**
java.lang.String - 字符串值
### getSubject() {#getSubject--}
```
public String getSubject()
```


获取文档的主题。

**退货：**
java.lang.String - 字符串值
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**退货：**
java.lang.Object
### getTitle() {#getTitle--}
```
public String getTitle()
```


获取文档标题。

**退货：**
java.lang.String - 字符串值
### getTrapped() {#getTrapped--}
```
public String getTrapped()
```


获得被困旗帜。

**退货：**
java.lang.String - 字符串值
### getValues() {#getValues--}
```
public System.Collections.Generic.Dictionary.ValueCollection<TKey,TValue> getValues()
```




**退货：**
com.aspose.ms.System.Collections.Generic.Dictionary.ValueCollection<TKey,TValue>
### get_Item(TKey arg0) {#get-Item-TKey-}
```
public TValue get_Item(TKey arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TKey |  |

**退货：**
值
### get_Item(String key) {#get-Item-java.lang.String-}
```
public String get_Item(String key)
```


获取与指定键关联的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要获取或设置其值的键。 |

**退货：**
java.lang.String - 值对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```




**退货：**
布尔值
### isPredefinedKey(String key) {#isPredefinedKey-java.lang.String-}
```
public static boolean isPredefinedKey(String key)
```


确定密钥是否是预定义的（标题、作者等），而不是自定义的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 选定键 |

**退货：**
布尔值 - 如果密钥是预定义的，则为 True。
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**退货：**
布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**退货：**
布尔值
### iterator() {#iterator--}
```
public System.Collections.Generic.Dictionary.Enumerator<TKey,TValue> iterator()
```




**退货：**
com.aspose.ms.System.Collections.Generic.Dictionary.Enumerator<TKey,TValue>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public void remove(String key)
```


从集合中移除具有指定键的元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要删除的元素的键。 |

### removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

**退货：**
布尔值
### removeItemByKey(TKey arg0) {#removeItemByKey-TKey-}
```
public boolean removeItemByKey(TKey arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TKey |  |

**退货：**
布尔值
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


设置文档作者。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


设置文档创建日期。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期对象 |

### setCreationTimeZone(double value) {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```


创建日期的时区（以毫秒为单位）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 以毫秒为单位 |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


设置文档创建者。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


设置文档的关键字。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


设置文档修改日期。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期对象 |

### setModTimeZone(double value) {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```


修改日期的时区。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setProducer(String value) {#setProducer-java.lang.String-}
```
public void setProducer(String value)
```


设置文档制作者。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


设置文档的主题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


设置文档标题。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTrapped(String value) {#setTrapped-java.lang.String-}
```
public void setTrapped(String value)
```


设置被困标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### set_Item(TKey arg0, TValue arg1) {#set-Item-TKey-TValue-}
```
public void set_Item(TKey arg0, TValue arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | TValue |  |

### set_Item(String key, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public void set_Item(String key, String value)
```


设置与指定键关联的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 字符串对象 |
| value | java.lang.String | 目的 |

### size() {#size--}
```
public int size()
```




**退货：**
整数
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### tryGetValue(TKey arg0, Object[] arg1) {#tryGetValue-TKey-java.lang.Object---}
```
public boolean tryGetValue(TKey arg0, Object[] arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | java.lang.Object[] |  |

**退货：**
布尔值
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
