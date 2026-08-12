---
title: "Aspose::Pdf::XmpPdfAExtensionValueType class"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XmpPdfAExtensionValueType class. PDF/A ValueType-schemat krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004-specifikationen, d.v.s. för värdetyper utanför följande lista: i C++."
type: docs
weight: 20800
url: /sv/cpp/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class


PDF/A ValueType-schemat krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004-specifikationen, dvs. för värdetyper utanför följande lista:

```cpp
class XmpPdfAExtensionValueType : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionField\>\&) | Lägg till nytt fält. |
| [AddRange](./addrange/)(const System::ArrayPtr\<System::SharedPtr\<XmpPdfAExtensionField\>\>\&) | Lägger till intervallet av fält. |
| [Clear](./clear/)() | Rensar alla fält. |
| [get_Fields](./get_fields/)() const | Hämtar listan över fält. |
| [get_NamespaceUri](./get_namespaceuri/)() const | Hämtar namnrymdens URI. |
| [get_Prefix](./get_prefix/)() const | Hämtar prefixet. |
| [get_Type](./get_type/)() const | Hämtar värdetypen. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Returnerar listan över xml-element som representerar värdetypen i xml-trädet. |
| [Remove](./remove/)(const System::SharedPtr\<XmpPdfAExtensionField\>\&) | Tar bort fältet från listan över fält. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&) | Initierar nytt objekt. |
## Anmärkningar


* Array types (these are container types which may contain one or more fields): Alt, Bag, Seq
* Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, [Text](../../aspose.pdf.text/), Thumbnail, URI, URL, XPath
* Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
* Basic Job/Workflow value type: Job
* EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: [http://www.aiim.org/pdfa/ns/type#](http://www.aiim.org/pdfa/ns/type#) Required schema namespace prefix: pdfaType


## Se även

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
