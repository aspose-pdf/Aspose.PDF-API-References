---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Aspose.PDF for Java API 参考"
description: "描述 PDF/A-1 提供的 XMP 扩展模式。"
type: docs
weight: 5720
url: /zh/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

描述 PDF/A-1 提供的 XMP 扩展模式。

## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | 默认扩展命名空间前缀。 |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | 默认扩展命名空间 URI。 |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | 默认字段命名空间前缀。 |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | 默认扩展命名空间 URI。 |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | 默认属性命名空间前缀。 |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | 默认属性命名空间 URI。 |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | 默认模式命名空间前缀。 |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | 默认模式命名空间 URI。 |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | 默认值命名空间 URI。 |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | 默认值类型命名空间前缀。 |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | 默认 RDF 命名空间 URI。 |
| [RDF_PREFIX](#RDF_PREFIX) | 默认 RDF 命名空间前缀。 |
| [XMLNS](#XMLNS) |  |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | 初始化新对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | 向模式中添加新对象。 |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | 确定对象是否存在于模式中。 |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | 为属性值块创建描述性 XML 元素。 |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | 为所有模式创建描述性 XML 元素。 |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | 从 XML 树创建模式元素列表。 |
| [getDescription](#getDescription--) | 获取模式描述。 |
| [getObjects1](#getObjects1--) | 获取对象列表（属性、值类型）。 |
| [getObjectsInternal](#getObjectsInternal--) | 获取对象列表（属性、值类型）。 |
| [getProperty](#getProperty-java.lang.String-) | 按名称返回 PDF/A 属性。 |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | 返回具有给定名称的属性索引。 |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | 返回在 XML 树中表示模式的 XML 元素（标签 - li）。 |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | 以 XML 树形式获取属性的值。 |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | 初始化属性的值。 |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | 确定前缀值是否是 PDF/A 扩展的一部分。 |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | 从模式中移除对象。 |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

默认扩展命名空间前缀。

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

默认扩展命名空间 URI。

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

默认字段命名空间前缀。

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

默认扩展命名空间 URI。

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

默认属性命名空间前缀。

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

默认属性命名空间 URI。

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

默认模式命名空间前缀。

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

默认模式命名空间 URI。

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

默认值命名空间 URI。

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

默认值类型命名空间前缀。

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

默认 RDF 命名空间 URI。

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

默认 RDF 命名空间前缀。

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
初始化新对象。

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
向模式中添加新对象。

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
确定对象是否存在于模式中。

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
为属性值块创建描述性 XML 元素。

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
为所有模式创建描述性 XML 元素。

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
从 XML 树创建模式元素列表。

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

获取模式描述。

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

获取对象列表（属性、值类型）。

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

获取对象列表（属性、值类型）。

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
按名称返回 PDF/A 属性。

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
返回具有给定名称的属性索引。

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
返回在 XML 树中表示模式的 XML 元素（标签 - li）。

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
以 XML 树形式获取属性的值。

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
初始化属性的值。

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
确定前缀值是否是 PDF/A 扩展的一部分。

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
从模式中移除对象。
