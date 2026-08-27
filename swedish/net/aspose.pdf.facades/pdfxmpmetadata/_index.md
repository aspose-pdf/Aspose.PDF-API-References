---
title: "Klass PdfXmpMetadata"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfXmpMetadata-klass. Klass för manipulation av XMP-metadata"
type: docs
weight: 4760
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

Klass för manipulation med XMP-metadata.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Konstruktor för PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Initierar ett nytt `PdfXmpMetadata`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Hämtar antalet objekt i samlingen. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Hämtar ordboken med tilläggsfält. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Returnerar true om samlingen har fast storlek. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Returnerar true om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Returnerar true om samlingen är synkroniserad. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Hämtar eller sätter värde efter nyckel. (2 indexerare) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Hämtar nycklar från ordboken. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Hämtar synkroniseringsobjektet för samlingen. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Hämtar samlingen av värden i ordboken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Lägger till ett par med nyckel och värde i ordboken. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Lägger till värde i XMP-metadata. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Lägger till ett nytt element i dictionary-objektet. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Lägger till ett nytt element i dictionary-objektet. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Lägger till ett extensionsfält i metadata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Tar bort alla element från objektet. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rensar Aspose.Pdf.Document som är bunden till en fasad. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Kontrollerar om dictionary innehåller den angivna egenskapen. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Kontrollerar om det angivna nyckel‑värde‑paret finns i dictionary. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Kontrollerar om dictionary innehåller den angivna nyckeln. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Fastställer om detta dictionary innehåller den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Hämtar enumerator‑objektet för dictionary. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Hämtar namespace‑URI med prefix. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Hämtar prefixet med namespace‑URI. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Hämta XmpMetadata för den angivna pdf-filen i XML-format. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Hämta en del av XmpMetadata för den angivna pdf-filen enligt ett metanamn. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registrerar namespace‑URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Tar bort element med angiven nyckel. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Tar bort nyckel/värde‑par från samlingen. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Tar bort nyckeln från dictionary. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Försöker hitta nyckeln i dictionary och hämtar värdet om den hittas. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* class [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


