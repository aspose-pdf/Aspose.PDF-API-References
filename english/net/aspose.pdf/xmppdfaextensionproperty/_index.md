---
title: "XmpPdfAExtensionProperty Class"
linktitle: "XmpPdfAExtensionProperty"
articleTitle: "XmpPdfAExtensionProperty"
second_title: "Aspose.PDF for .NET"
description: "Describes a single property. Schema namespace URI: http://www.aiim.org/pdfa/ns/property# Required schema namespace prefix: pdfaProperty"
type: docs
weight: 3310
url: "/net/aspose.pdf/xmppdfaextensionproperty/"
keywords: "XmpPdfAExtensionProperty, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XmpPdfAExtensionProperty class

Describes a single property. Schema namespace URI: http://www.aiim.org/pdfa/ns/property#
 Required schema namespace prefix: pdfaProperty

```csharp
public sealed class XmpPdfAExtensionProperty : XmpPdfAExtensionField
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/#constructor)(*string, string, string, [XmpPdfAExtensionCategoryType](../../aspose.pdf/xmppdfaextensioncategorytype/), string*) | Initializes new object. |

## Properties

| Name | Description |
| --- | --- |
| [Category](./category/) { get; } | Gets the property category. |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Gets the description. *(Inherited from XmpPdfAExtensionObject)* |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Field name. Field names must be valid XML element names. *(Inherited from XmpPdfAExtensionField)* |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Gets or sets the value. *(Inherited from XmpPdfAExtensionObject)* |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension. *(Inherited from XmpPdfAExtensionField)* |

## Methods

| Name | Description |
| --- | --- |
| [GetXml](./getxml/)(*XmlDocument*) | Returns the list of xml elements that represent property in xml tree. |

### See Also

* class [XmpPdfAExtensionField](../xmppdfaextensionfield/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

