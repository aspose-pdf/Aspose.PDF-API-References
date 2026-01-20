---
title: Aspose::Pdf::XmpPdfAExtensionSchema class
linktitle: XmpPdfAExtensionSchema
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmpPdfAExtensionSchema class. Describes the XMP extension schema which is provided by PDF/A-1 in C++.'
type: docs
weight: 20600
url: /cpp/aspose.pdf/xmppdfaextensionschema/
---
## XmpPdfAExtensionSchema class


Describes the XMP extension schema which is provided by PDF/A-1.

```cpp
class XmpPdfAExtensionSchema : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<XmpPdfAExtensionObject\>) | Adds new object into schema. |
| [Contains](./contains/)(System::SharedPtr\<XmpPdfAExtensionObject\>) | Determines whether obj exists in schema. |
| [get_Description](./get_description/)() const | Gets the schema description. |
| [get_Objects](./get_objects/)() const | Gets the list of objects (properties, value types). |
| [GetProperty](./getproperty/)(System::String) | Returns PDF/A property by its name. |
| [GetSchemaXml](./getschemaxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) | Returns the xml element (tag - li) that represents schema in xml tree. |
| [GetValuesXml](./getvaluesxml/)(System::SharedPtr\<System::Xml::XmlDocument\>, System::SharedPtr\<System::Xml::XmlElement\>) | Gets the values of properties as xml tree representation. |
| [Remove](./remove/)(System::SharedPtr\<XmpPdfAExtensionObject\>) | Removes the object from schema. |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/)(System::SharedPtr\<XmpPdfAExtensionSchemaDescription\>) | Initializes new object. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultExtensionNamespacePrefix](./defaultextensionnamespaceprefix/) | Default extension namespace prefix. |
| static [DefaultExtensionNamespaceUri](./defaultextensionnamespaceuri/) | Default extension namespace uri. |
| static [DefaultFieldNamespacePrefix](./defaultfieldnamespaceprefix/) | Default field namespace prefix. |
| static [DefaultFieldNamespaceUri](./defaultfieldnamespaceuri/) | Default extension namespace uri. |
| static [DefaultPropertyNamespacePrefix](./defaultpropertynamespaceprefix/) | Default property namespace prefix. |
| static [DefaultPropertyNamespaceUri](./defaultpropertynamespaceuri/) | Default property namespace uri. |
| static [DefaultSchemaNamespacePrefix](./defaultschemanamespaceprefix/) | Default schema namespace prefix. |
| static [DefaultSchemaNamespaceUri](./defaultschemanamespaceuri/) | Default schema namespace uri. |
| static [DefaultValueNamespaceUri](./defaultvaluenamespaceuri/) | Default value namespace uri. |
| static [DefaultValueTypeNamespacePrefix](./defaultvaluetypenamespaceprefix/) | Default valie type namespace prefix. |
| static [RdfNamespaceURI](./rdfnamespaceuri/) | Default rdf namespace uri. |
| static [RdfPrefix](./rdfprefix/) | Default rdf namespace prefix. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
