---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata klass. Klass för manipulation med XMP metadata
type: docs
weight: 4640
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata klass

Klass för manipulation med XMP metadata.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Konstruktör för PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Initierar ett nytt `PdfXmpMetadata` objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Hämtar antalet objekt i samlingen. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetas med. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Hämtar ordboken med tilläggsfält. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Returnerar sant om samlingen har fast storlek. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Returnerar sant om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Returnerar sant om samlingen är synkroniserad. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Hämtar eller sätter värde efter nyckel. (2 indexerare) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Hämtar nycklar från ordboken. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Hämtar synkroniseringsobjektet för samlingen. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Hämtar samlingen av värden i ordboken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Lägger till par med nyckel och värde i ordboken. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Lägger till värde till XMP metadata. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Lägger till nytt element i ordboksobjektet. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Lägger till nytt element i ordboksobjektet. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Lägger till tilläggsfält i metadata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar facaden. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Tar bort alla element från objektet. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Avsätter Aspose.Pdf.Document kopplad till en fasad. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Kontrollerar om ordboken innehåller den angivna egenskapen. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Kontrollerar om den angivna nyckel-värde-paret finns i ordboken. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Kontrollerar om ordboken innehåller den angivna nyckeln. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Avgör om denna ordbok innehåller den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter facaden. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Hämtar enumeratorobjektet för ordboken. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Hämtar namnrymdens URI efter prefix. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Hämtar prefixet efter namnrymdens URI. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Hämtar XmpMetadata för den angivna pdf:en i xml-format. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Hämtar en del av XmpMetadata för den angivna pdf:en enligt ett meta-namn. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registrerar namnrymdens URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Tar bort element med angiven nyckel. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Tar bort nyckel/värde-par från samlingen. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Tar bort nyckeln från ordboken. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Försöker hitta nyckeln i ordboken och hämtar värdet om det hittas. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* klass [XmpValue](../../aspose.pdf/xmpvalue/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)