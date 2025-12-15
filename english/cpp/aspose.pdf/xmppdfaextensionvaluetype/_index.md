---
title: Aspose::Pdf::XmpPdfAExtensionValueType class
linktitle: XmpPdfAExtensionValueType
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmpPdfAExtensionValueType class. The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: in C++.'
type: docs
weight: 20700
url: /cpp/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class


The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list:

```cpp
class XmpPdfAExtensionValueType : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<XmpPdfAExtensionField\>) | Add new field. |
| [AddRange](./addrange/)(System::ArrayPtr\<System::SharedPtr\<XmpPdfAExtensionField\>\>) | Adds the range of fields. |
| [Clear](./clear/)() | Clears all fields. |
| [get_Fields](./get_fields/)() const | Gets the list of fields. |
| [get_NamespaceUri](./get_namespaceuri/)() const | Gets the namespace URI. |
| [get_Prefix](./get_prefix/)() const | Gets the prefix. |
| [get_Type](./get_type/)() const | Gets the value type. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Returns the list of xml elements that represent value type in xml tree. |
| [Remove](./remove/)(System::SharedPtr\<XmpPdfAExtensionField\>) | Removes the field from the list of fields. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/)(System::String, System::String, System::String, System::String) | Initializes new object. |
## Remarks


* Array types (these are container types which may contain one or more fields): Alt, Bag, Seq
* Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, [Text](../../aspose.pdf.text/), Thumbnail, URI, URL, XPath
* Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
* Basic Job/Workflow value type: Job
* EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: [http://www.aiim.org/pdfa/ns/type#](http://www.aiim.org/pdfa/ns/type#) Required schema namespace prefix: pdfaType


## See Also

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
