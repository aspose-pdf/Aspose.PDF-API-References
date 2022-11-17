---
title: XmpPdfAExtensionSchema
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述由 PDF/A-1 提供的 XMP 扩展模式。
type: docs
weight: 423
url: /zh/java/com.aspose.pdf/xmppdfaextensionschema/
---
**遗产：**
java.lang.Object
```
public class XmpPdfAExtensionSchema
```

描述由 PDF/A-1 提供的 XMP 扩展模式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description)](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | 初始化新对象。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT-EXTENSION-NAMESPACE-PREFIX) | 默认扩展名称空间前缀。 |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT-EXTENSION-NAMESPACE-URI) | 默认扩展命名空间 uri。 |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT-FIELD-NAMESPACE-PREFIX) | 默认字段命名空间前缀。 |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT-FIELD-NAMESPACE-URI) | 默认扩展命名空间 uri。 |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT-PROPERTY-NAMESPACE-PREFIX) | 默认属性命名空间前缀。 |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT-PROPERTY-NAMESPACE-URI) | 默认属性命名空间 uri。 |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT-SCHEMA-NAMESPACE-PREFIX) | 默认架构命名空间前缀。 |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT-SCHEMA-NAMESPACE-URI) | 默认模式命名空间 uri。 |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT-VALUE-NAMESPACE-URI) | 默认值命名空间 uri。 |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT-VALUE-TYPE-NAMESPACE-PREFIX) | 默认值类型命名空间前缀。 |
| [RDF_NAMESPACE_URI](#RDF-NAMESPACE-URI) | 默认 rdf 命名空间 uri。 |
| [RDF_PREFIX](#RDF-PREFIX) | 默认 rdf 命名空间前缀。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(XmpPdfAExtensionObject obj)](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | 将新对象添加到架构中。 |
| [contains(XmpPdfAExtensionObject obj)](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | 确定 obj 是否存在于模式中。 |
| [createDescriptionValueXml(System.Xml.XmlDocument xmlDocument)](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | 为属性值块创建描述 xml 元素。 |
| [createDescriptionXml(System.Xml.XmlDocument xmlDocument)](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | 为所有模式创建描述 xml 元素。 |
| [createSchemasElement(System.Xml.XmlNode rootNode)](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | 从 xml 树创建模式元素列表。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取架构描述。 |
| [getObjects1()](#getObjects1--) | 获取对象列表（属性、值类型）。 |
| [getObjectsInternal()](#getObjectsInternal--) | 获取对象列表（属性、值类型）。 |
| [getProperty(String name)](#getProperty-java.lang.String-) | 按名称返回 PDF/A 属性。 |
| [getPropertyIndex(String name)](#getPropertyIndex-java.lang.String-) | 返回具有给定名称的属性的索引。 |
| [getSchemaXml(System.Xml.XmlDocument xmlDocument)](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中模式的 xml 元素 (tag - li)。 |
| [getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement)](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | 获取属性值作为 xml 树表示形式。 |
| [hashCode()](#hashCode--) |  |
| [initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema)](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | 初始化属性的值。 |
| [isPdfAExtensionPrefix(String localName)](#isPdfAExtensionPrefix-java.lang.String-) | 确定前缀值是否是 pdf-a 扩展名的一部分。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XmpPdfAExtensionObject obj)](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | 从架构中删除对象。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description) {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
```
public XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description)
```


初始化新对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| description | [XmpPdfAExtensionSchemaDescription](../../com.aspose.pdf/xmppdfaextensionschemadescription) | 架构描述。 |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT-EXTENSION-NAMESPACE-PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```


默认扩展名称空间前缀。

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT-EXTENSION-NAMESPACE-URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```


默认扩展命名空间 uri。

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT-FIELD-NAMESPACE-PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```


默认字段命名空间前缀。

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT-FIELD-NAMESPACE-URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```


默认扩展命名空间 uri。

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT-PROPERTY-NAMESPACE-PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```


默认属性命名空间前缀。

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT-PROPERTY-NAMESPACE-URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```


默认属性命名空间 uri。

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT-SCHEMA-NAMESPACE-PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```


默认架构命名空间前缀。

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT-SCHEMA-NAMESPACE-URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```


默认模式命名空间 uri。

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT-VALUE-NAMESPACE-URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```


默认值命名空间 uri。

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT-VALUE-TYPE-NAMESPACE-PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```


默认值类型命名空间前缀。

### RDF_NAMESPACE_URI {#RDF-NAMESPACE-URI}
```
public static final String RDF_NAMESPACE_URI
```


默认 rdf 命名空间 uri。

### RDF_PREFIX {#RDF-PREFIX}
```
public static final String RDF_PREFIX
```


默认 rdf 命名空间前缀。

### add(XmpPdfAExtensionObject obj) {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void add(XmpPdfAExtensionObject obj)
```


将新对象添加到架构中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | 新对象。 |

### contains(XmpPdfAExtensionObject obj) {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public boolean contains(XmpPdfAExtensionObject obj)
```


确定 obj 是否存在于模式中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | 要查找的对象。 |

**退货：**
boolean - True - 对象存在于模式中；否则，假的。
### createDescriptionValueXml(System.Xml.XmlDocument xmlDocument) {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public static System.Xml.XmlElement createDescriptionValueXml(System.Xml.XmlDocument xmlDocument)
```


为属性值块创建描述 xml 元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
com.aspose.ms.System.Xml.XmlElement - 描述 xml 元素。
### createDescriptionXml(System.Xml.XmlDocument xmlDocument) {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public static System.Xml.XmlElement createDescriptionXml(System.Xml.XmlDocument xmlDocument)
```


为所有模式创建描述 xml 元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
com.aspose.ms.System.Xml.XmlElement - 描述 xml 元素。
### createSchemasElement(System.Xml.XmlNode rootNode) {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
```
public static HashDictionary<String,XmpPdfAExtensionSchema> createSchemasElement(System.Xml.XmlNode rootNode)
```


从 xml 树创建模式元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rootNode | com.aspose.ms.System.Xml.XmlNode | 架构元素的根节点。 |

**退货：**
[HashDictionary](../../com.aspose.pdf.engine.collections/hashdictionary) - 格式为（键，值）的模式元素字典：模式\_prefix，架构值。
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
public XmpPdfAExtensionSchemaDescription getDescription()
```


获取架构描述。

**退货：**
[XmpPdfAExtensionSchemaDescription](../../com.aspose.pdf/xmppdfaextensionschemadescription) - XmpPdfAExtensionSchemaDescription
### getObjects1() {#getObjects1--}
```
public List getObjects1()
```


获取对象列表（属性、值类型）。

**退货：**
java.util.List - 数组列表
### getObjectsInternal() {#getObjectsInternal--}
```
public System.Collections.Generic.List<XmpPdfAExtensionObject> getObjectsInternal()
```


获取对象列表（属性、值类型）。

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.XmpPdfAExtensionObject> - ArrayList
### getProperty(String name) {#getProperty-java.lang.String-}
```
public final XmpPdfAExtensionProperty getProperty(String name)
```


按名称返回 PDF/A 属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 物业名称。 |

**退货：**
[XmpPdfAExtensionProperty](../../com.aspose.pdf/xmppdfaextensionproperty) - XmpPdfAExtensionProperty 实例 属性。
### getPropertyIndex(String name) {#getPropertyIndex-java.lang.String-}
```
public final int getPropertyIndex(String name)
```


返回具有给定名称的属性的索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 物业名称。 |

**退货：**
int - 对象列表中的属性索引，
### getSchemaXml(System.Xml.XmlDocument xmlDocument) {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Xml.XmlElement getSchemaXml(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中模式的 xml 元素 (tag - li)。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
com.aspose.ms.System.Xml.XmlElement - xml 元素。
### getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement) {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
```
public void getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement)
```


获取属性值作为 xml 树表示形式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |
| rootElement | com.aspose.ms.System.Xml.XmlElement | 属性值列表的根节点。 |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema) {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
```
public static void initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema)
```


初始化属性的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| node | com.aspose.ms.System.Xml.XmlNode | 存储属性值的当前节点。 |
| schema | [XmpPdfAExtensionSchema](../../com.aspose.pdf/xmppdfaextensionschema) | 包含属性定义的模式。 |

### isPdfAExtensionPrefix(String localName) {#isPdfAExtensionPrefix-java.lang.String-}
```
public static boolean isPdfAExtensionPrefix(String localName)
```


确定前缀值是否是 pdf-a 扩展名的一部分。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| localName | java.lang.String | 要验证的前缀值。 |

**退货：**
boolean - True - 前缀是 pdf-a 扩展的一部分；否则，假的。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XmpPdfAExtensionObject obj) {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void remove(XmpPdfAExtensionObject obj)
```


从架构中删除对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | 要删除的对象。 |

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
