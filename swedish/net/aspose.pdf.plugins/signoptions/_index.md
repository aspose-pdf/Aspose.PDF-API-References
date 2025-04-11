---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.SignOptions klass. Representerar signeringsalternativ för signaturplugin
type: docs
weight: 9250
url: /sv/net/aspose.pdf.plugins/signoptions/
---
## SignOptions klass

Representerar signeringsalternativ för [`Signature`](../signature/) plugin.

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Initierar en ny instans av `SignOptions` objektet med standardalternativ. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Initierar en ny instans av `SignOptions` objektet med standardalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Stänger indataflöden efter att operationen är slutförd. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Stänger utdataflöden efter att operationen är slutförd. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | Kontakten för signaturen. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Returnerar datainsamlingen för OrganizerOptions plugin. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | Platsen för signaturen. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | Namnet på det befintliga signaturfältet. Null för att skapa ett nytt fält. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Hämtar samlingen av tillagda mål för att spara operationens resultat. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | Sidnumret där signaturen görs. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | Anledningen till signaturen. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | Rektangeln för signaturen. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | Synligheten för signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Lägger till en ny datakälla till PdfOrganizer plugin datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Lägger till en ny datakälla till PdfOrganizer plugin datainsamling. |

### Se Även

* klass [OrganizerBaseOptions](../organizerbaseoptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)