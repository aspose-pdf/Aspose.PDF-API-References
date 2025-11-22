---
title: Aspose::Pdf::XmpPdfAExtensionField class
linktitle: XmpPdfAExtensionField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmpPdfAExtensionField class. This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI:  Required schema namespace prefix: pdfaField in C++.'
type: docs
weight: 20000
url: /cpp/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class


This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI: [http://www.aiim.org/pdfa/ns/field#](http://www.aiim.org/pdfa/ns/field#) Required schema namespace prefix: pdfaField.

```cpp
class XmpPdfAExtensionField : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Methods

| Method | Description |
| --- | --- |
| [get_Name](./get_name/)() const | Field name. Field names must be valid XML element names. |
| [get_ValueType](./get_valuetype/)() const | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. Predefined XMP type names or names of custom types. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Returns the list of xml elements that represent field in xml tree. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/)(System::String, System::String, System::String, System::String) | Initializes object. |
## See Also

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
