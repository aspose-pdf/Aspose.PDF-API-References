---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionField klass. Detta schema beskriver ett fält i en strukturerad typ. Det är mycket likt PDF/A Property Value Type-schemat men definierar ett fält i en struktur istället för en egenskap. Schema namnrymd URI http//www.aiim.org/pdfa/ns/field Obligatorisk schema namnrymd prefix pdfaField
type: docs
weight: 11440
url: /sv/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField klass

Detta schema beskriver ett fält i en strukturerad typ. Det är mycket likt PDF/A Property Value Type-schemat, men definierar ett fält i en struktur istället för en egenskap. Schema namnrymd URI: http://www.aiim.org/pdfa/ns/field# Obligatorisk schema namnrymd prefix: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | Initierar objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Hämtar beskrivningen. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Fältnamn. Fältnamn måste vara giltiga XML-elementnamn. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Hämtar eller ställer in värdet. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Fältvärdetyp, hämtad från XMP-specifikationen 2004, eller ett inbäddat PDF/A-värdetyputvidgningsschema. Fördefinierade XMP-typnamn eller namn på anpassade typer. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | Returnerar listan över xml-element som representerar fältet i xml-trädet. |

### Se Även

* klass [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)