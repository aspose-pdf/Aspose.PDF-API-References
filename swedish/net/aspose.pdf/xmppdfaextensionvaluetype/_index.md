---
title: "Klass XmpPdfAExtensionValueType"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XmpPdfAExtensionValueType‑klass. PDF/A ValueType‑schemat krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004‑specifikationen, d.v.s. för värdetyper utanför följande lista  Array‑typer – dessa är behållartyper som kan innehålla ett eller flera fält Alt Bag Seq  Grundläggande värdetyper Boolean öppna och stängda Choice Date Dimensions Integer Lang Alt Locale MIMEType ProperName Real Text Thumbnail URI URL XPath  Media Management‑värdetyper AgentName RenditionClass ResourceEvent ResourceRef Version  Grundläggande Job/Workflow‑värdetyp Job  EXIF‑schemavärdetyper Flash CFAPattern DeviceSettings GPSCoordinate OECF/SFR Rational Schema namnrymd URI http//www.aiim.org/pdfa/ns/type Obligatoriskt schemats namnrymdsprefix pdfaType"
type: docs
weight: 11680
url: /sv/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

PDF/A ValueType‑schemat krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004‑specifikationen, d.v.s. för värdetyper utanför följande lista: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schemanamnrymd URI: http://www.aiim.org/pdfa/ns/type# Krävd schemanamnsprefix: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Initierar ett nytt objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Hämtar beskrivningen. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Hämtar listan över fält. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Hämtar namnrymdens URI. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Hämtar prefixet. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Hämtar värdetypen. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Hämtar eller anger värdet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Lägg till nytt fält. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Lägger till intervallet av fält. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Rensar alla fält. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Returnerar listan över xml‑element som representerar värdetypen i xml‑trädet. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Tar bort fältet från listan över fält. |

### Se även

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


