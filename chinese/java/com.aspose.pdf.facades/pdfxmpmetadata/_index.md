---
title: PdfXmpMetadata
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于使用 XMP 元数据进行操作的类。
type: docs
weight: 54
url: /zh/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class PdfXmpMetadata extends SaveableFacade implements System.Collections.Generic.IGenericDictionary<String,XmpValue>
```

用于使用 XMP 元数据进行操作的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfXmpMetadata()](#PdfXmpMetadata--) | PdfXmpMetadata 的构造函数。 |
| [PdfXmpMetadata(IDocument document)](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfXmpMetadata 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription)](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | 将扩展字段添加到元数据中。 |
| [addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | 将带有键和值的对添加到字典中。 |
| [addItem(int key, XmpValue value)](#addItem-int-com.aspose.pdf.XmpValue-) | 为 XMP 元数据增加价值。 |
| [addItem(String key, XmpValue value)](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | 向字典对象添加新元素。 |
| [addItem(String key, Object value)](#addItem-java.lang.String-java.lang.Object-) | 向字典对象添加新元素。 |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [clear()](#clear--) | 从对象中移除所有元素。 |
| [close()](#close--) | 处理与外观绑定的文档。 |
| [contains(int property)](#contains-int-) | 检查字典是否包含指定的属性。 |
| [contains(String key)](#contains-java.lang.String-) | 检查字典是否包含指定的键。 |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | 检查指定的键值对是否包含在字典中。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 确定此字典是否包含指定的键。 |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-) | 将元数据复制到数组中。 |
| [dispose()](#dispose--) | 处理门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getByDefaultMetadataProperties(int key)](#getByDefaultMetadataProperties-int-) | 按键获取 XMP 元数据的值。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getExtensionFields()](#getExtensionFields--) | 获取扩展字段字典。 |
| [getKeys()](#getKeys--) | 从字典中获取键。 |
| [getNamespaceURIByPrefix(String prefix)](#getNamespaceURIByPrefix-java.lang.String-) | 通过前缀获取命名空间 URI。 |
| [getPrefixByNamespaceURI(String namespaceURI)](#getPrefixByNamespaceURI-java.lang.String-) | 通过名称空间 URI 获取前缀。 |
| [getSyncRoot()](#getSyncRoot--) | 获取集合的同步对象。 |
| [getValues()](#getValues--) | 获取字典中值的集合。 |
| [getXmpMetadata()](#getXmpMetadata--) | 以 xml 格式获取输入 pdf 的 XmpMetadata。 |
| [getXmpMetadata(String name)](#getXmpMetadata-java.lang.String-) | 根据meta name获取输入pdf的XmpMetadata的一部分。 |
| [get_Item(String key)](#get-Item-java.lang.String-) | 通过键获取值。 |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | 如果集合具有固定大小，则返回 true。 |
| [isReadOnly()](#isReadOnly--) | 如果集合是只读的，则返回 true。 |
| [isSynchronized()](#isSynchronized--) | 如果集合已同步，则返回 true。 |
| [iterator()](#iterator--) | 获取字典的枚举器对象。 |
| [iteratorIt()](#iteratorIt--) | 获取集合的枚举器对象。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceURI(String prefix, String namespaceURI)](#registerNamespaceURI-java.lang.String-java.lang.String-) | 注册命名空间 URI。 |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | 从集合中移除键/值对。 |
| [removeItemByKey(int key)](#removeItemByKey-int-) | 删除具有指定键的元素。 |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | 从字典中删除键。 |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定的流。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [setByDefaultMetadataProperties(int key, XmpValue value)](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | 按键设置 XMP 元数据的值。 |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.pdf.XmpValue-) | 通过键设置值。 |
| [size()](#size--) | 获取集合中项目的计数。 |
| [toString()](#toString--) |  |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | 尝试在字典中查找键并在找到时检索值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfXmpMetadata() {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```


PdfXmpMetadata 的构造函数。

--------------------

```
PdfXmlMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
```

### PdfXmpMetadata(IDocument document) {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
```
public PdfXmpMetadata(IDocument document)
```


在文档的基础上初始化新的 PdfXmpMetadata 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription) {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
```
public void add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription)
```


将扩展字段添加到元数据中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmpPdfAExtensionObject | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | 要添加的 pdf 扩展对象。 |
| namespacePrefix | java.lang.String | 架构的前缀。 |
| namespaceUri | java.lang.String | 模式的命名空间 uri。 |
| schemaDescription | java.lang.String | 模式的可选描述。 |

### addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


将带有键和值的对添加到字典中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | 要添加的项目。 |

### addItem(int key, XmpValue value) {#addItem-int-com.aspose.pdf.XmpValue-}
```
public void addItem(int key, XmpValue value)
```


为 XMP 元数据增加价值。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add(DefaultMetadataProperties.Nickname, "name1");
 xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | int | 密钥名称。 |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | 将被添加的值。 |

### addItem(String key, XmpValue value) {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void addItem(String key, XmpValue value)
```


向字典对象添加新元素。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add("xmp:Nickname", "Nickname1");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 新元素的键。 |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | 元素的值。 |

### addItem(String key, Object value) {#addItem-java.lang.String-java.lang.Object-}
```
public void addItem(String key, Object value)
```


向字典对象添加新元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 新元素的键。 |
| value | java.lang.Object | 元素的值。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### clear() {#clear--}
```
public void clear()
```


从对象中移除所有元素。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.clear();
```

### close() {#close--}
```
public void close()
```


处理与外观绑定的文档。

### contains(int property) {#contains-int-}
```
public boolean contains(int property)
```


检查字典是否包含指定的属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| property | int | 将检查的属性。 |

**退货：**
boolean - True - 如果字典包含指定的属性；否则，假的。
### contains(String key) {#contains-java.lang.String-}
```
public boolean contains(String key)
```


检查字典是否包含指定的键。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add("xmp:Nickname", "Nickname1");
 if (!xmp.contains("xmp:Nickname"))
   System.out.println("Key does not exists");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 将被检查的密钥。 |

**退货：**
boolean - True - 如果字典包含指定的键；否则，假的。
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
### copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)
```


将元数据复制到数组中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] | 目标数组。 |
| index | int | 起始索引。 |

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

此方法已过时，请改用 close() 。

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
### getByDefaultMetadataProperties(int key) {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```


按键获取 XMP 元数据的值。

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | int | 值的键。 |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - 来自 XMP 元数据的值。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getExtensionFields() {#getExtensionFields--}
```
public Hashtable<String,XmpPdfAExtensionSchema> getExtensionFields()
```


获取扩展字段字典。

**退货：**
java.util.Hashtable<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> - 哈希表对象
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


从字典中获取键。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - ICollection 元素
### getNamespaceURIByPrefix(String prefix) {#getNamespaceURIByPrefix-java.lang.String-}
```
public String getNamespaceURIByPrefix(String prefix)
```


通过前缀获取命名空间 URI。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 System.out.println(xmp.getNamespaceURIByPrefix("xmp"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | java.lang.String | 前缀。 |

**退货：**
java.lang.String - 命名空间 URI。
### getPrefixByNamespaceURI(String namespaceURI) {#getPrefixByNamespaceURI-java.lang.String-}
```
public String getPrefixByNamespaceURI(String namespaceURI)
```


通过名称空间 URI 获取前缀。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| namespaceURI | java.lang.String | 命名空间 URI。 |

**退货：**
java.lang.String - 前缀值。
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取集合的同步对象。

**退货：**
java.lang.Object - 对象元素
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XmpValue> getValues()
```


获取字典中值的集合。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XmpValue> - ICollection 对象
### getXmpMetadata() {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```


以 xml 格式获取输入 pdf 的 XmpMetadata。

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 byte[] data = pxm.getXmpMetadata();
```

**退货：**
字节[] - XmpMetadata 的字节数。
### getXmpMetadata(String name) {#getXmpMetadata-java.lang.String-}
```
public byte[] getXmpMetadata(String name)
```


根据meta name获取输入pdf的XmpMetadata的一部分。

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 byte[] data = pxm.getXmpMetadata("dc:creator");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 元数据名称。 |

**退货：**
字节[] - 元数据的字节数。
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


通过键获取值。

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item("xmp:Nickname"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要获取的密钥名称。 |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - 按键对象
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


如果集合具有固定大小，则返回 true。

**退货：**
boolean - 布尔值
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


如果集合是只读的，则返回 true。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


如果集合已同步，则返回 true。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iterator()
```


获取字典的枚举器对象。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> - 枚举器对象。
### iteratorIt() {#iteratorIt--}
```
public System.Collections.IEnumerator iteratorIt()
```


获取集合的枚举器对象。

**退货：**
com.aspose.ms.System.Collections.IEnumerator - IEnumerator 对象
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




### registerNamespaceURI(String prefix, String namespaceURI) {#registerNamespaceURI-java.lang.String-java.lang.String-}
```
public void registerNamespaceURI(String prefix, String namespaceURI)
```


注册命名空间 URI。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | java.lang.String | 前缀。 |
| namespaceURI | java.lang.String | 命名空间 URI。 |

### removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


从集合中移除键/值对。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | 要删除的键/值对。 |

**退货：**
boolean - 如果找到并删除了对，则为真。
### removeItemByKey(int key) {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```


删除具有指定键的元素。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.remove(DefaultMetadataProperties.Nickname);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | int | 将被删除的元素的键。 |

### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


从字典中删除键。

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.remove("xmp:Nickname");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 将被删除的密钥。 |

**退货：**
布尔值 - True - 如果删除了密钥；否则，假的。
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


将 PDF 文档保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 目标流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将 PDF 文档保存到指定文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 目标文件。 |

### setByDefaultMetadataProperties(int key, XmpValue value) {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
```
public void setByDefaultMetadataProperties(int key, XmpValue value)
```


按键设置 XMP 元数据的值。

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | int | DefaultMetadataProperties 值的键。 |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | 目的。 |

### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


通过键设置值。

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item("xmp:Nickname"));
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要设置的键名。 |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | 要设置的值。 |

### size() {#size--}
```
public int size()
```


获取集合中项目的计数。

**退货：**
int - 整数值

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println("Count = " + pxm.size());
```
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
