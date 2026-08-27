---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Aspose.PDF for Java API 参考"
description: "PDF/A ValueType 架构是所有未在 XMP 2004 规范中定义的属性值类型所必需的，即以下列表之外的值类型：-。"
type: docs
weight: 5740
url: /zh/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

PDF/A ValueType 模式是所有未在 XMP 2004 规范中定义的属性值类型所必需的，即以下列表之外的值类型：- 数组类型（这些是可以包含一个或多个字段的容器类型）：Alt、Bag、Seq - 基本值类型：Boolean、（开放和闭合）Choice、Date、Dimensions、Integer、Lang Alt、Locale、MIMEType、ProperName、Real、Text、Thumbnail、URI、URL、XPath - 媒体管理值类型：AgentName、RenditionClass、ResourceEvent、ResourceRef、Version - 基本作业/工作流值类型：Job - EXIF 模式值类型：Flash、CFAPattern、DeviceSettings、GPSCoordinate、OECF/SFR、Rational 模式命名空间 URI: http://www.aiim.org/pdfa/ns/type# 必需的模式命名空间前缀: pdfaType

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化新对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | 添加新字段。 |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | 添加字段范围。 |
| [clear](#clear--) | 清除所有字段。 |
| [getFields](#getFields--) | 获取字段列表。 |
| [getNamespaceUri](#getNamespaceUri--) | 获取命名空间 URI。 |
| [getPrefix](#getPrefix--) | 获取前缀。 |
| [getType](#getType--) | 获取值类型。 |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 XML 树中字段的 xml 元素列表。 |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示值类型的 XML 元素列表（在 XML 树中）。 |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | 从字段列表中移除该字段。 |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
初始化新对象。

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
添加新字段。

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
添加字段范围。

### clear {#clear--}
```
public void clear()
```

清除所有字段。

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

获取字段列表。

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

获取命名空间 URI。

**Returns:**
字符串

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

获取前缀。

**Returns:**
字符串

### getType {#getType--}
```
public String getType()
```

获取值类型。

**Returns:**
字符串

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
返回表示 XML 树中字段的 xml 元素列表。

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
返回表示值类型的 XML 元素列表（在 XML 树中）。

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
从字段列表中移除该字段。
