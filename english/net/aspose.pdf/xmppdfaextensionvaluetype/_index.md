---
title: "XmpPdfAExtensionValueType Class"
linktitle: "XmpPdfAExtensionValueType"
articleTitle: "XmpPdfAExtensionValueType"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XmpPdfAExtensionValueType class. The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specifi..."
type: docs
weight: 3340
url: "/net/aspose.pdf/xmppdfaextensionvaluetype/"
keywords: "XmpPdfAExtensionValueType, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XmpPdfAExtensionValueType class

The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list:
 - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq
 - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath
 - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
 - Basic Job/Workflow value type: Job
 - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational
 Schema namespace URI: http://www.aiim.org/pdfa/ns/type#
 Required schema namespace prefix: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/#constructor)(*string, string, string, string*) | Initializes new object. |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Gets the description. *(Inherited from XmpPdfAExtensionObject)* |
| [Fields](./fields/) { get; } | Gets the list of fields. |
| [NamespaceUri](./namespaceuri/) { get; } | Gets the namespace URI. |
| [Prefix](./prefix/) { get; } | Gets the prefix. |
| [Type](./type/) { get; } | Gets the value type. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Gets or sets the value. *(Inherited from XmpPdfAExtensionObject)* |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*XmpPdfAExtensionField*) | Add new field. |
| [AddRange](./addrange/)(*XmpPdfAExtensionField[]*) | Adds the range of fields. |
| [Clear](./clear/) | Clears all fields. |
| [GetXml](./getxml/)(*XmlDocument*) | Returns the list of xml elements that represent value type in xml tree. |
| [Remove](./remove/)(*XmpPdfAExtensionField*) | Removes the field from the list of fields. |

### See Also

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

