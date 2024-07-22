---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType class. The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification i.e. for value types outside of the following list  Array types these are container types which may contain one or more fields Alt Bag Seq  Basic value types Boolean open and closed Choice Date Dimensions Integer Lang Alt Locale MIMEType ProperName Real Text Thumbnail URI URL XPath  Media Management value types AgentName RenditionClass ResourceEvent ResourceRef Version  Basic Job/Workflow value type Job  EXIF schema value types Flash CFAPattern DeviceSettings GPSCoordinate OECF/SFR Rational Schema namespace URI http//www.aiim.org/pdfa/ns/type Required schema namespace prefix pdfaType
type: docs
weight: 8590
url: /net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Initializes new object. |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Gets the description. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Gets the list of fields. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Gets the namespace URI. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Gets the prefix. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Gets the value type. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Gets or sets the value. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Add new field. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Adds the range of fields. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Clears all fields. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Returns the list of xml elements that represent value type in xml tree. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Removes the field from the list of fields. |

### See Also

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


