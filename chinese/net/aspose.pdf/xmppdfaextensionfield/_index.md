---
title: "类 XmpPdfAExtensionField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.XmpPdfAExtensionField 类。此模式描述结构化类型中的字段。它非常类似于 PDF/A 属性值类型模式，但在结构中定义字段而不是属性。模式命名空间 URI http//www.aiim.org/pdfa/ns/field 必需的模式命名空间前缀 pdfaField。"
type: docs
weight: 11630
url: /zh/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class

此模式描述结构化类型中的字段。它与 PDF/A 属性值类型模式非常相似，但在结构中定义字段而不是属性。模式命名空间 URI: http://www.aiim.org/pdfa/ns/field# 必需的模式命名空间前缀: pdfaField。

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | 初始化对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 获取描述。 |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | 字段名称。字段名称必须是有效的 XML 元素名称。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 获取或设置值。 |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | 字段值类型，取自 XMP Specification 2004，或嵌入的 PDF/A 值类型扩展模式。预定义的 XMP 类型名称或自定义类型名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | 返回表示 xml 树中字段的 xml 元素列表。 |

### 另请参见

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


