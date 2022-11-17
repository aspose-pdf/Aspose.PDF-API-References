---
title: AppearanceDictionary
second_title: 用于 Java API 参考的 Aspose.PDF
description: 注释外观字典，指定注释应如何在页面上以可视方式呈现。
type: docs
weight: 24
url: /zh/java/com.aspose.pdf/appearancedictionary/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class AppearanceDictionary implements System.Collections.Generic.IGenericDictionary<String,XForm>
```

注释外观字典，指定注释应如何在页面上以可视方式呈现。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Object key, Object value)](#add-java.lang.Object-java.lang.Object-) | 添加具有提供的键和值的元素。 |
| [addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | 将带有键和值的对添加到字典中。 |
| [addItem(String key, XForm value)](#addItem-java.lang.String-com.aspose.pdf.XForm-) | 为指定键添加 X 表单。 |
| [clear()](#clear--) | 从字典中删除所有元素。 |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | 检查指定的键值对是否包含在字典中。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 确定此字典是否包含指定的键。 |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | 将字典的元素复制到一个数组，从特定的数组索引开始。 |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-) | 将 ICollection 的元素复制到数组，从特定的数组索引开始。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDict()](#getDict--) | 获取pdf字典 |
| [getKeys()](#getKeys--) | 获取字典的键。 |
| [getKeys_()](#getKeys---) | 获取字典的键。 |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步对字典的访问的对象。 |
| [getValues()](#getValues--) | 获取字典值的列表。 |
| [getValues_()](#getValues---) | 获取字典值的列表。 |
| [get_Item(String key)](#get-Item-java.lang.String-) | 表示获取外观流的便捷形式。 |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | 获取一个值，该值指示字典是否具有固定大小。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示字典是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对字典的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回字典的 IDictionaryEnumerator 对象。 |
| [iterator__Rename_Namesake()](#iterator--Rename-Namesake--) | 集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | 从集合中移除键/值对。 |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | 从字典中删除键。 |
| [set_Item(String key, XForm value)](#set-Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size()](#size--) | 获取字典中包含的元素数。 |
| [toString()](#toString--) |  |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | 尝试在字典中查找键并在找到时检索值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object key, Object value) {#add-java.lang.Object-java.lang.Object-}
```
public void add(Object key, Object value)
```


添加具有提供的键和值的元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.Object | 元素键。 |
| value | java.lang.Object | 元素值。 |

### addItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


将带有键和值的对添加到字典中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | 要添加的项目。 |

### addItem(String key, XForm value) {#addItem-java.lang.String-com.aspose.pdf.XForm-}
```
public void addItem(String key, XForm value)
```


为指定键添加 X 表单。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 元素键。 |
| value | [XForm](../../com.aspose.pdf/xform) | XForm 对象值。 |

### clear() {#clear--}
```
public void clear()
```


从字典中删除所有元素。

### containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


检查指定的键值对是否包含在字典中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | 键值对。 |

**退货：**
boolean - 如果找到这个 pauir 则为真。
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


确定此字典是否包含指定的键。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 在字典中搜索的键。 |

**退货：**
布尔值 - 如果找到密钥则为真。
### copyTo(XForm[] array, int index) {#copyTo-com.aspose.pdf.XForm---int-}
```
public void copyTo(XForm[] array, int index)
```


将字典的元素复制到一个数组，从特定的数组索引开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [XForm\[\]](../../com.aspose.pdf/xform) | 必须复制项目的数组。 |
| index | int | 必须复制项目的索引。 |

### copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)
```


将 ICollection 的元素复制到数组，从特定的数组索引开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>[] | 作为从 ICollection 复制的元素的目标的一维数组。 Array 必须具有从零开始的索引。 |
| arrayIndex | int | array 中从零开始的索引，复制从这里开始。 |

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
### getDict() {#getDict--}
```
public IPdfDictionary getDict()
```


获取pdf字典

**退货：**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) IPdfDictionary 对象
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


获取字典的键。如果外观字典有子目录，则 Keys 包含 (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - 字符串值列表
### getKeys_() {#getKeys---}
```
public List<String> getKeys_()
```


获取字典的键。如果外观字典有子目录，则 Keys 包含 (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**退货：**
java.util.List<java.lang.String> - 字符串值列表
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步对字典的访问的对象。

**退货：**
java.lang.Object - 同步对象
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XForm> getValues()
```


获取字典值的列表。结果集合包含 XForm 对象的列表。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XForm> - XForm 值列表
### getValues_() {#getValues---}
```
public List<XForm> getValues_()
```


获取字典值的列表。结果集合包含 XForm 对象的列表。

**退货：**
java.util.List<com.aspose.pdf.XForm> - XForm 值列表
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XForm get_Item(String key)
```


表示获取外观流的便捷形式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 表示外观流的路径。如果外观字典有子字典，则路径必须包含 2 个部分（键），否则路径只有一个部分。 |

**退货：**
[XForm](../../com.aspose.pdf/xform) - 对应于给定键的 XForm 对象（外观流）。
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


获取一个值，该值指示字典是否具有固定大小。

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示字典是否为只读。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对字典的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator()
```


返回字典的 IDictionaryEnumerator 对象。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - 字典的枚举器。
### iterator__Rename_Namesake() {#iterator--Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator__Rename_Namesake()
```


集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - 集合项的枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


从集合中移除键/值对。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | 要删除的键/值对。 |

**退货：**
boolean - 如果找到并删除了对，则为真。
### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


从字典中删除键。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要从字典中删除的键。 |

**退货：**
布尔值 - 如果密钥已成功删除，则为 true。
### set_Item(String key, XForm value) {#set-Item-java.lang.String-com.aspose.pdf.XForm-}
```
public void set_Item(String key, XForm value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String |  |
| value | [XForm](../../com.aspose.pdf/xform) |  |

### size() {#size--}
```
public int size()
```


获取字典中包含的元素数。

**退货：**
int - 整数值
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public boolean tryGetValue(String key, Object[] value)
```


尝试在字典中查找键并在找到时检索值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 在字典中搜索的键。 |
| value | java.lang.Object[] | 检索值。 |

**退货：**
布尔值 - 如果找到密钥则为真。
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
