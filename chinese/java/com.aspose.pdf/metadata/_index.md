---
title: Metadata
second_title: 用于 Java API 参考的 Aspose.PDF
description: 提供对 XMP 元数据流的访问。
type: docs
weight: 220
url: /zh/java/com.aspose.pdf/metadata/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class Metadata implements System.Collections.Generic.IGenericDictionary<String,XmpValue>
```

提供对 XMP 元数据流的访问。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | 将带有键和值的对添加到字典中。 |
| [addItem(String prefix, XmpPdfAExtensionObject value)](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | 向元数据添加 pdf 扩展名。 |
| [addItem(String key, XmpValue value)](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | 为元数据增加价值。 |
| [addItem(String key, Object value)](#addItem-java.lang.String-java.lang.Object-) | 为元数据增加价值。 |
| [clear()](#clear--) | 清除元数据。 |
| [contains(String key)](#contains-java.lang.String-) | 检查密钥是否包含在元数据中。 |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | 检查指定的键值对是否包含在字典中。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 确定此字典是否包含指定的键。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合的元素复制到数组中。 |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-) | 将集合的元素复制到数组中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtensionFields()](#getExtensionFields--) | 获取扩展字段字典。 |
| [getExtensionFields_Internal()](#getExtensionFields-Internal--) | 仅供内部使用。 |
| [getKeys()](#getKeys--) | 获取元数据键的集合。 |
| [getNamespaceUriByPrefix(String prefix)](#getNamespaceUriByPrefix-java.lang.String-) | 按前缀返回命名空间 URI。 |
| [getPrefixByNamespaceUri(String namespaceUri)](#getPrefixByNamespaceUri-java.lang.String-) | 按名称空间 URI 返回前缀。 |
| [getSyncRoot()](#getSyncRoot--) | 获取集合同步对象。 |
| [getValues()](#getValues--) | 获取元数据中的值。 |
| [get_Item(String key)](#get-Item-java.lang.String-) | 从元数据中获取数据。 |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | 检查 colleciton 是否具有固定大小。 |
| [isReadOnly()](#isReadOnly--) | 检查集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 检查集合是否同步。 |
| [iterator()](#iterator--) | 返回字典枚举器。 |
| [iteratorIE()](#iteratorIE--) | 获取集合的枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | 注册命名空间 URI。 |
| [registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription)](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | 注册命名空间 URI。 |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | 从集合中删除键/值对。 |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | 从元数据中删除条目。 |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.pdf.XmpValue-) | 从元数据设置数据。 |
| [size()](#size--) | 获取集合中元素的计数。 |
| [toString()](#toString--) |  |
| [tryGetValue(String key, XmpValue[] value)](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue---) | 尝试在字典中查找键并在找到时检索值。 |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | 尝试在字典中查找键并在找到时检索值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


将带有键和值的对添加到字典中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | 要添加的项目。 |

### addItem(String prefix, XmpPdfAExtensionObject value) {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void addItem(String prefix, XmpPdfAExtensionObject value)
```


向元数据添加 pdf 扩展名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | java.lang.String | 扩展的前缀。 |
| value | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | 将被添加的值。 |

### addItem(String key, XmpValue value) {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void addItem(String key, XmpValue value)
```


为元数据增加价值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要添加的密钥。 |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | 将被添加的值。 |

### addItem(String key, Object value) {#addItem-java.lang.String-java.lang.Object-}
```
public void addItem(String key, Object value)
```


为元数据增加价值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要添加的密钥。 |
| value | java.lang.Object | 将被添加的值。 |

### clear() {#clear--}
```
public void clear()
```


清除元数据。

### contains(String key) {#contains-java.lang.String-}
```
public boolean contains(String key)
```


检查密钥是否包含在元数据中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 找到入口的钥匙。 |

**退货：**
boolean - 如果键包含在元数据中则为真。
### containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


检查指定的键值对是否包含在字典中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | 键值对。 |

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
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


将集合的元素复制到数组中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 起始索引。 |

### copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)
```


将集合的元素复制到数组中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] | 目标数组。 |
| index | int | 起始索引。 |

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
### getExtensionFields() {#getExtensionFields--}
```
public Hashtable<String,XmpPdfAExtensionSchema> getExtensionFields()
```


获取扩展字段字典。

**退货：**
java.util.Hashtable<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> - 哈希表对象
### getExtensionFields_Internal() {#getExtensionFields-Internal--}
```
public System.Collections.Generic.IGenericDictionary<String,XmpPdfAExtensionSchema> getExtensionFields_Internal()
```


仅供内部使用。

获取扩展字段字典。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> - 内部对象
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


获取元数据键的集合。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - ICollection 对象
### getNamespaceUriByPrefix(String prefix) {#getNamespaceUriByPrefix-java.lang.String-}
```
public String getNamespaceUriByPrefix(String prefix)
```


按前缀返回命名空间 URI。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | java.lang.String | 前缀的值。 |

**退货：**
java.lang.String - 命名空间 URI 的值。
### getPrefixByNamespaceUri(String namespaceUri) {#getPrefixByNamespaceUri-java.lang.String-}
```
public String getPrefixByNamespaceUri(String namespaceUri)
```


按名称空间 URI 返回前缀。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 命名空间 URI。 |

**退货：**
java.lang.String - 前缀的值。
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取集合同步对象。

**退货：**
java.lang.Object - 同步对象
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XmpValue> getValues()
```


获取元数据中的值。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XmpValue> - ICollection 对象
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


从元数据中获取数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 密钥名称。 |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - 元数据对象。
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


检查 colleciton 是否具有固定大小。

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


检查集合是否为只读。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


检查集合是否同步。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iterator()
```


返回字典枚举器。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> - 枚举器。
### iteratorIE() {#iteratorIE--}
```
public Iterator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iteratorIE()
```


获取集合的枚举器。

**退货：**
java.util.Iterator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> - IEnumerator 对象
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```




**退货：**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


注册命名空间 URI。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | java.lang.String | 前缀的值。 |
| namespaceUri | java.lang.String | 命名空间 URI 的值。 |

### registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription) {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription)
```


注册命名空间 URI。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | java.lang.String | 前缀的值。 |
| namespaceUri | java.lang.String | 命名空间 URI 的值。 |
| schemaDescription | java.lang.String | 模式描述的值。 |

### removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


从集合中删除键/值对。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | 要删除的键/值对。 |

**退货：**
boolean - 如果找到并删除了对，则为真。
### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


从元数据中删除条目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要删除的条目的键。 |

**退货：**
布尔值 - True - 如果删除了密钥；否则，假的。
### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


从元数据设置数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 键名 |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | 值对象 |

### size() {#size--}
```
public int size()
```


获取集合中元素的计数。

**退货：**
int - 整数值
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### tryGetValue(String key, XmpValue[] value) {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue---}
```
public boolean tryGetValue(String key, XmpValue[] value)
```


尝试在字典中查找键并在找到时检索值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 在字典中搜索的键。 |
| value | [XmpValue\[\]](../../com.aspose.pdf/xmpvalue) | 检索值。 |

**退货：**
布尔值 - 如果找到密钥则为真。
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
