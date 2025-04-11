---
title: Class XmpPdfAExtensionProperty
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionProperty 类。描述单个属性。模式命名空间 URI http//www.aiim.org/pdfa/ns/property 必需的模式命名空间前缀 pdfaProperty
type: docs
weight: 11460
url: /zh/net/aspose.pdf/xmppdfaextensionproperty/
---
## XmpPdfAExtensionProperty 类

描述单个属性。模式命名空间 URI: http://www.aiim.org/pdfa/ns/property# 必需的模式命名空间前缀: pdfaProperty

```csharp
public sealed class XmpPdfAExtensionProperty : XmpPdfAExtensionField
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmpPdfAExtensionProperty](xmppdfaextensionproperty/)(string, string, string, XmpPdfAExtensionCategoryType, string) | 初始化新对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Category](../../aspose.pdf/xmppdfaextensionproperty/category/) { get; } | 获取属性类别。 |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 获取描述。 |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | 字段名称。字段名称必须是有效的 XML 元素名称。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 获取或设置值。 |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | 字段值类型，来自 XMP 规范 2004，或嵌入的 PDF/A 值类型扩展模式。预定义的 XMP 类型名称或自定义类型名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionproperty/getxml/)(XmlDocument) | 返回表示 XML 树中属性的 XML 元素列表。 |

### 另请参阅

* 类 [XmpPdfAExtensionField](../xmppdfaextensionfield/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)