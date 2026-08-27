---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Aspose.PDF for Java API 参考"
description: "用于操作 XMP 元数据的类。"
type: docs
weight: 620
url: /zh/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

用于操作 XMP 元数据的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> PdfXmpMetadata 的构造函数。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> PdfXmpMetadata 的构造函数。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | 向元数据中添加扩展字段。 |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> 向 XMP 元数据添加值。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 向字典中添加键和值对。 |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | 向字典对象添加新元素。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> 向字典对象添加新元素。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> 从对象中移除所有元素。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | 检查字典是否包含指定的属性。 |
| [contains](#contains-java.lang.String-) | <p> 检查字典是否包含指定的键。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 检查指定的键值对是否包含在字典中。 |
| [containsKey](#containsKey-java.lang.String-) | 确定此字典是否包含指定的键。 |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 将元数据复制到数组中。 |
| [get_Item](#get_Item-java.lang.String-) | <p> 通过键获取值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> 通过键获取 XMP 元数据的值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> 获取扩展字段的字典。 </p> |
| [getKeys](#getKeys--) | 从字典获取键。 |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> 通过前缀获取命名空间 URI。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> 通过命名空间 URI 获取前缀。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | 获取集合的同步对象。 |
| [getValues](#getValues--) | 获取字典中的值集合。 |
| [getXmpMetadata](#getXmpMetadata--) | <p> 获取输入 PDF 的 XmpMetadata（XML 格式）。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> 获取输入 PDF 的 XmpMetadata（XML 格式）。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | 如果集合具有固定大小，则返回 true。 |
| [isReadOnly](#isReadOnly--) | 如果集合为只读，则返回 true。 |
| [isSynchronized](#isSynchronized--) | 如果集合已同步，则返回 true。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | 获取字典的枚举器对象。 |
| [iteratorIt](#iteratorIt--) | 获取集合的枚举器对象。 |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> 注册命名空间 URI。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(\"input.pdf\"); xmp.registerNamespaceURI(\"xmp\", \"http://ns.adobe.com/xap/1.0/\"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 从集合中移除键/值对。 |
| [removeItemByKey](#removeItemByKey-int-) | <p> 删除具有指定键的元素。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> 从字典中删除键。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.remove(\"xmp:Nickname\"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> 通过键设置值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(\"xmp:Nickname\")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> 通过键设置 XMP 元数据的值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> 获取集合中项目的计数。 </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 尝试在字典中查找键，如果找到则检索值。 |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> PdfXmpMetadata 的构造函数。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> PdfXmpMetadata 的构造函数。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
向元数据中添加扩展字段。

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> 向 XMP 元数据添加值。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
向字典中添加键和值对。

### addItem {#addItem-java.lang.String-java.lang.Object-}
向字典对象添加新元素。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> 向字典对象添加新元素。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> 从对象中移除所有元素。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

检查字典是否包含指定的属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 |  | 将被检查的属性。 |

**Returns:**
True - 如果字典包含指定的属性；否则为 false。

### contains {#contains-java.lang.String-}
<p> 检查字典是否包含指定的键。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
检查指定的键值对是否包含在字典中。

### containsKey {#containsKey-java.lang.String-}
确定此字典是否包含指定的键。

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
将元数据复制到数组中。

### get_Item {#get_Item-java.lang.String-}
<p> 通过键获取值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> 通过键获取 XMP 元数据的值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 |  | 值的键。 |

**Returns:**
来自 XMP 元数据的值。 @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> 获取扩展字段的字典。 </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} 对象

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

从字典获取键。

**Returns:**
ICollection 元素

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> 通过前缀获取命名空间 URI。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> 通过命名空间 URI 获取前缀。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取集合的同步对象。

**Returns:**
对象元素

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

获取字典中的值集合。

**Returns:**
ICollection 对象

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> 获取输入 PDF 的 XmpMetadata（XML 格式）。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
XmpMetadata 的字节。

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> 获取输入 PDF 的 XmpMetadata（XML 格式）。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
XmpMetadata 的字节。

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

如果集合具有固定大小，则返回 true。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

如果集合为只读，则返回 true。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

如果集合已同步，则返回 true。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

获取字典的枚举器对象。

**Returns:**
枚举器对象。

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

获取集合的枚举器对象。

**Returns:**
IEnumerator 对象

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> 注册命名空间 URI。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(\"input.pdf\"); xmp.registerNamespaceURI(\"xmp\", \"http://ns.adobe.com/xap/1.0/\"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
从集合中移除键/值对。

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> 删除具有指定键的元素。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 |  | 将被删除的元素的键。 @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> 从字典中删除键。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.remove(\"xmp:Nickname\"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> 通过键设置值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(\"xmp:Nickname\")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> 通过键设置 XMP 元数据的值。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> 获取集合中项目的计数。 </p>

**Returns:**
int 值 <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(\"Count = \" + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
尝试在字典中查找键，如果找到则检索值。
