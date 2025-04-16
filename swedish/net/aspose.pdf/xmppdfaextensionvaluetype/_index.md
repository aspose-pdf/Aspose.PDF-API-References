---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType klass. PDF/A ValueType-schema krävs för alla egenskapsvärdetyper som inte definieras i XMP 2004-specifikationen, dvs. för värdetyper utanför följande lista: - Arraytyper: Alt, Bag, Seq - Grundläggande värdetyper: Boolean, öppen och stängd Choice, Datum, Dimensioner, Heltal, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Mediehanteringsvärdetyper: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundläggande Jobb/Arbetsflöde värdetyper: Jobb - EXIF-schema värdetyper: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Krävs schema namespace prefix: pdfaType
type: docs
weight: 11490
url: /sv/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType klass

PDF/A ValueType-schema krävs för alla egenskapsvärdetyper som inte definieras i XMP 2004-specifikationen, dvs. för värdetyper utanför följande lista: - Arraytyper (dessa är behållartyper som kan innehålla ett eller flera fält): Alt, Bag, Seq - Grundläggande värdetyper: Boolean, (öppen och stängd) Choice, Datum, Dimensioner, Heltal, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Mediehanteringsvärdetyper: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundläggande Jobb/Arbetsflöde värdetyper: Jobb - EXIF-schema värdetyper: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Krävs schema namespace prefix: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Initierar nytt objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Hämtar beskrivningen. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Hämtar listan över fält. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Hämtar namespace URI. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Hämtar prefixet. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Hämtar värdetypen. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Hämtar eller sätter värdet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Lägger till nytt fält. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Lägger till intervallet av fält. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Rensar alla fält. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Returnerar listan över xml-element som representerar värdetyp i xml-trädet. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Tar bort fältet från listan över fält. |

### Se Även

* klass [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)