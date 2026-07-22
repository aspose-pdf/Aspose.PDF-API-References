---
title: "Aspose::Pdf::XmpPdfAExtensionSchema klass"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XmpPdfAExtensionSchema-klass. Beskriver XMP-utökningens schema som tillhandahålls av PDF/A-1 i C++."
type: docs
weight: 20600
url: /sv/cpp/aspose.pdf/xmppdfaextensionschema/
---
## XmpPdfAExtensionSchema class


Beskriver XMP-utökningens schema som tillhandahålls av PDF/A-1.

```cpp
class XmpPdfAExtensionSchema : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Lägger till ett nytt objekt i schemat. |
| [Contains](./contains/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Bestämmer om obj finns i schemat. |
| [get_Description](./get_description/)() const | Hämtar schemabeskrivningen. |
| [get_Objects](./get_objects/)() const | Hämtar listan över objekt (egenskaper, värdetyper). |
| [GetProperty](./getproperty/)(const System::String\&) | Returnerar PDF/A-egenskapen efter dess namn. |
| [GetSchemaXml](./getschemaxml/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&) | Returnerar xml-elementet (tagg - li) som representerar schemat i xml-trädet. |
| [GetValuesXml](./getvaluesxml/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&, const System::SharedPtr\<System::Xml::XmlElement\>\&) | Hämtar värdena för egenskaper som xml-trädsrepresentation. |
| [Remove](./remove/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Tar bort objektet från schemat. |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/)(const System::SharedPtr\<XmpPdfAExtensionSchemaDescription\>\&) | Initierar nytt objekt. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultExtensionNamespacePrefix](./defaultextensionnamespaceprefix/) | Standardprefix för utökningens namnrymd. |
| static [DefaultExtensionNamespaceUri](./defaultextensionnamespaceuri/) | Standard-URI för utökningens namnrymd. |
| static [DefaultFieldNamespacePrefix](./defaultfieldnamespaceprefix/) | Standardprefix för fältets namnrymd. |
| static [DefaultFieldNamespaceUri](./defaultfieldnamespaceuri/) | Standard-URI för utökningens namnrymd. |
| static [DefaultPropertyNamespacePrefix](./defaultpropertynamespaceprefix/) | Standardprefix för egenskapsnamnrymd. |
| static [DefaultPropertyNamespaceUri](./defaultpropertynamespaceuri/) | Standard-URI för egenskapsnamnrymd. |
| static [DefaultSchemaNamespacePrefix](./defaultschemanamespaceprefix/) | Standardprefix för schemats namnrymd. |
| static [DefaultSchemaNamespaceUri](./defaultschemanamespaceuri/) | Standard-URI för schemats namnrymd. |
| static [DefaultValueNamespaceUri](./defaultvaluenamespaceuri/) | Standard-URI för värdenas namnrymd. |
| static [DefaultValueTypeNamespacePrefix](./defaultvaluetypenamespaceprefix/) | Standardprefix för värdetypens namnrymd. |
| static [RdfNamespaceURI](./rdfnamespaceuri/) | Standard-URI för rdf-namnrymd. |
| static [RdfPrefix](./rdfprefix/) | Standardprefix för rdf-namnrymd. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
