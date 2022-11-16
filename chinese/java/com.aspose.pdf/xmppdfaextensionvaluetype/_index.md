---
title: XmpPdfAExtensionValueType
second_title: 用于 Java API 参考的 Aspose.PDF
description: PDF/A ValueType 架构对于 XMP 2004 规范中未定义的所有属性值类型都是必需的，即对于以下列表之外的值类型 - 数组类型，这些是容器类型，可能包含一个或多个字段 Alt Bag Seq - Basic值类型 Boolean 打开和关闭 Choice Dimensions Integer Lang Alt Locale MIMEType ProperName Real Text Thumbnail URI URL XPath - Media Management 值类型 AgentName RenditionClass ResourceEvent ResourceRef Version - Basic Job/Workflow 值类型 Job - EXIF 模式值类型 Flash CFAPattern DeviceSettings GPSCoordinate OECF/ SFR Rational Schema 命名空间 URI http//www.aiim.orgdfa/ns/type 必需的架构命名空间前缀 pdfaType
type: docs
weight: 425
url: /zh/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject)
```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

PDF/A ValueType 架构对于 XMP 2004 规范中未定义的所有属性值类型都是必需的，即对于以下列表之外的值类型： - 数组类型（这些是容器类型，可能包含一个或多个字段）： Alt、Bag、Seq - 基本值类型：Boolean、（开放式和封闭式）Choice、Date、Dimensions、Integer、Lang Alt、Locale、MIMEType、ProperName、Real、Text、Thumbnail、URI、URL、XPath - Media Management 值类型：AgentName、RenditionClass、ResourceEvent、ResourceRef、Version - 基本作业/工作流值类型：作业 - EXIF 模式值类型：Flash、CFAPattern、DeviceSettings、GPSCoordinate、OECF/SFR、Rational Schema 命名空间 URI：http://www.aiim.org/pdfa/ns/type\#必需的架构命名空间前缀：pdfaType
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description)](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化新对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(XmpPdfAExtensionField field)](#add-com.aspose.pdf.XmpPdfAExtensionField-) | 添加新字段。 |
| [addRange(XmpPdfAExtensionField[] fields)](#addRange-com.aspose.pdf.XmpPdfAExtensionField---) | 添加字段范围。 |
| [clear()](#clear--) | 清除所有字段。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取描述。 |
| [getFields()](#getFields--) | 获取字段列表。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getType()](#getType--) | 获取值类型。 |
| [getValue()](#getValue--) | 获取值。 |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中值类型的 xml 元素列表。 |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中字段的 xml 元素列表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XmpPdfAExtensionField field)](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | 从字段列表中删除该字段。 |
| [setValue(String value)](#setValue-java.lang.String-) | 设置值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description) {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description)
```


初始化新对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | java.lang.String | 值类型。 |
| namespaceUri | java.lang.String | 命名空间 URI。 |
| prefix | java.lang.String | 前缀。 |
| description | java.lang.String | 说明。 |

### add(XmpPdfAExtensionField field) {#add-com.aspose.pdf.XmpPdfAExtensionField-}
```
public void add(XmpPdfAExtensionField field)
```


添加新字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield) | 要添加的字段。 |

### addRange(XmpPdfAExtensionField[] fields) {#addRange-com.aspose.pdf.XmpPdfAExtensionField---}
```
public void addRange(XmpPdfAExtensionField[] fields)
```


添加字段范围。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | [XmpPdfAExtensionField\[\]](../../com.aspose.pdf/xmppdfaextensionfield) | 要添加的字段。 |

### clear() {#clear--}
```
public void clear()
```


清除所有字段。

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


获取描述。

**退货：**
java.lang.String - 字符串
### getFields() {#getFields--}
```
public System.Collections.Generic.List<XmpPdfAExtensionField> getFields()
```


获取字段列表。

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.XmpPdfAExtensionField> - IList
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取命名空间 URI。

**退货：**
java.lang.String - 字符串
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**退货：**
java.lang.String - 字符串
### getType() {#getType--}
```
public String getType()
```


获取值类型。

**退货：**
java.lang.String - 字符串
### getValue() {#getValue--}
```
public String getValue()
```


获取值。

**退货：**
java.lang.String - 字符串
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中值类型的 xml 元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - xml 元素列表。
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List getXml_(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中字段的 xml 元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
java.util.List - 字段列表。
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




### remove(XmpPdfAExtensionField field) {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
```
public void remove(XmpPdfAExtensionField field)
```


从字段列表中删除该字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield) | 要删除的字段。 |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


设置值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.细绳 | String |

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
