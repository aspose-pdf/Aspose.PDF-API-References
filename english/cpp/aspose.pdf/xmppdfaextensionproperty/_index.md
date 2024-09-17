---
title: Aspose::Pdf::XmpPdfAExtensionProperty class
linktitle: XmpPdfAExtensionProperty
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmpPdfAExtensionProperty class. Describes a single property. Schema namespace URI:  Required schema namespace prefix: pdfaProperty in C++.'
type: docs
weight: 17200
url: /cpp/aspose.pdf/xmppdfaextensionproperty/
---
## XmpPdfAExtensionProperty class


Describes a single property. Schema namespace URI: [http://www.aiim.org/pdfa/ns/property#](http://www.aiim.org/pdfa/ns/property#) Required schema namespace prefix: pdfaProperty.

```cpp
class XmpPdfAExtensionProperty : public Aspose::Pdf::XmpPdfAExtensionField
```

## Methods

| Method | Description |
| --- | --- |
| [get_Category](./get_category/)() const | Gets the property category. |
| [get_Description](../xmppdfaextensionobject/get_description/)() const | Gets the description. |
| [get_Name](../xmppdfaextensionfield/get_name/)() const | Field name. Field names must be valid XML element names. |
| [get_Value](../xmppdfaextensionobject/get_value/)() const | Gets the value. |
| [get_ValueType](../xmppdfaextensionfield/get_valuetype/)() const | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. Predefined XMP type names or names of custom types. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Returns the list of xml elements that represent property in xml tree. |
| [set_Value](../xmppdfaextensionobject/set_value/)(System::String) | Sets the value. |
| [XmpPdfAExtensionField](../xmppdfaextensionfield/xmppdfaextensionfield/)(System::String, System::String, System::String, System::String) | Initializes object. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/)(System::String, System::String, System::String, XmpPdfAExtensionCategoryType, System::String) | Initializes new object. |
## See Also

* Class [XmpPdfAExtensionField](../xmppdfaextensionfield/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
