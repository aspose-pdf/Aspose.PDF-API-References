---
title: PdfXmpMetadata
second_title: Aspose.PDF för .NET API Referens
description: Klass för manipulation med XMP-metadata.
type: docs
weight: 2650
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

Klass för manipulation med XMP-metadata.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata#constructor)() | Konstruktör för PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata#constructor_1)(Document) | Initierar ny[`PdfXmpMetadata`](../pdfxmpmetadata) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count) { get; } | Får räkning om föremål i samlingen. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields) { get; } | Hämtar ordlistan över tilläggsfält. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize) { get; } | Returnerar sant om samlingen har fast storlek. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly) { get; } | Returnerar sant om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized) { get; } | Returnerar sant om insamlingen är synkroniserad. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item) { get; set; } | Hämtar eller ställer in värde med nyckel. (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys) { get; } | Får nycklar från ordboken. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot) { get; } | Hämtar synkroniseringsobjekt för samlingen. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values) { get; } | Hämtar samlingen av värden i ordboken. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Lägger till par med nyckel och värde i ordboken. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add)(DefaultMetadataProperties, XmpValue) | Lägger till värde till XMP-metadata. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_4)(string, object) | Lägger till nytt element i ordboksobjektet. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_3)(string, XmpValue) | Lägger till nytt element i ordboksobjektet. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_1)(XmpPdfAExtensionObject, string, string, string) | Lägger till tilläggsfält i metadata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear)() | Tar bort alla element från objektet. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Kastar Aspose.Pdf.Dokument bunden med en fasad. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains)(DefaultMetadataProperties) | Kontrollerar om ordboken innehåller den angivna egenskapen. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Kontrollerar om det specificerade nyckel-värdeparet finns i ordboken. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_2)(string) | Kontrollerar om ordboken innehåller den angivna nyckeln. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey)(string) | Bestämmer om denna ordbok innehåller specificerad nyckel. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator)() | Hämtar uppräkningsobjekt i ordboken. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix)(string) | Får namnutrymmes-URI med prefix. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri)(string) | Hämtar prefixet efter namnutrymmes-URI. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata)() | Hämta XmpMetadata för den ingående pdf-filen i ett xml-format. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata_1)(string) | Hämta en del av XmpMetadata för den ingående pdf-filen enligt ett metanamn. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri)(string, string) | Registrerar namnutrymmets URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_2)(DefaultMetadataProperties) | Tar bort element med angiven nyckel. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Tar bort nyckel/värdepar från samlingen. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_1)(string) | Tar bort nyckel från ordboken. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue)(string, out XmpValue) | Försöker hitta nyckeln i ordboken och hämtar värde om det hittas. |

### Se även

* class [SaveableFacade](../saveablefacade)
* class [XmpValue](../../aspose.pdf/xmpvalue)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
