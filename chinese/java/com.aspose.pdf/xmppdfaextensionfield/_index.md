---
title: "XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "Aspose.PDF for Java API 参考"
description: "此模式描述结构化类型中的字段。它与 PDF/A 属性值类型模式非常相似，但在结构中定义字段而不是属性。模式。"
type: docs
weight: 5690
url: /zh/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

此模式描述结构化类型中的字段。它与 PDF/A Property Value Type 模式非常相似，但在结构中定义字段而不是属性。模式命名空间 URI: http://www.aiim.org/pdfa/ns/field# 必需的模式命名空间前缀: pdfaField。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getName](#getName--) | 字段名称。字段名称必须是有效的 XML 元素名称。 |
| [getValueType](#getValueType--) | 字段值类型，取自 XMP 规范 2004，或嵌入的 PDF/A 值类型扩展模式。预定义的 XMP 类型名称或自定义类型名称。 |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 XML 树中字段的 xml 元素列表。 |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 XML 树中字段的 xml 元素列表。 |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
初始化对象。

### getName {#getName--}
```
public String getName()
```

字段名称。字段名称必须是有效的 XML 元素名称。

**Returns:**
字符串

### getValueType {#getValueType--}
```
public String getValueType()
```

字段值类型，取自 XMP 规范 2004，或嵌入的 PDF/A 值类型扩展模式。预定义的 XMP 类型名称或自定义类型名称。

**Returns:**
字符串

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
返回表示 XML 树中字段的 xml 元素列表。

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
返回表示 XML 树中字段的 xml 元素列表。
