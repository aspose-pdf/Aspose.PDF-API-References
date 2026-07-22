---
title: "Aspose::Pdf::XmpPdfAExtensionField class"
linktitle: "XmpPdfAExtensionField"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XmpPdfAExtensionField class. Detta schema beskriver ett fält i en strukturerad typ. Det är mycket likt PDF/A Property Value Type-schema, men definierar ett fält i en struktur istället för en egenskap. Schema namespace URI:  Krävt schema namespace prefix: pdfaField i C++."
type: docs
weight: 20300
url: /sv/cpp/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class


Detta schema beskriver ett fält i en strukturerad typ. Det är mycket likt PDF/A Property Value Type-schemat, men definierar ett fält i en struktur istället för en egenskap. Schemanamnrymds-URI: [http://www.aiim.org/pdfa/ns/field#](http://www.aiim.org/pdfa/ns/field#) Obligatoriskt schemanamnrymdsprefix: pdfaField.

```cpp
class XmpPdfAExtensionField : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Name](./get_name/)() const | Fältnamn. Fältnamn måste vara giltiga XML-elementnamn. |
| [get_ValueType](./get_valuetype/)() const | Fältvärdestyp, hämtad från XMP Specification 2004, eller ett inbäddat PDF/A-värdetypsexpansionsschema. Fördefinierade XMP-typsnamn eller namn på anpassade typer. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Returnerar listan med xml-element som representerar fältet i xml-trädet. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&) | Initierar objektet. |
## Se även

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
