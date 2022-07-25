---
title: PdfXmpMetadata
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse zur Manipulation mit XMP-Metadaten.
type: docs
weight: 2650
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

Klasse zur Manipulation mit XMP-Metadaten.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata#constructor)() | Konstruktor für PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata#constructor_1)(Document) | Initialisiert neu[`PdfXmpMetadata`](../pdfxmpmetadata) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count) { get; } | Ruft die Anzahl der Elemente in der Sammlung ab. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields) { get; } | Ruft das Wörterbuch der Erweiterungsfelder ab. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize) { get; } | Gibt true zurück, wenn die Sammlung eine feste Größe hat. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly) { get; } | Gibt „true“ zurück, wenn die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized) { get; } | Gibt „true“ zurück, wenn die Sammlung synchronisiert ist. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item) { get; set; } | Ruft den Wert nach Schlüssel ab oder legt ihn fest. (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys) { get; } | Ruft Schlüssel aus dem Wörterbuch ab. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot) { get; } | Ruft das Synchronisationsobjekt der Sammlung ab. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values) { get; } | Ruft die Sammlung von Werten im Wörterbuch ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Fügt ein Paar mit Schlüssel und Wert in das Wörterbuch ein. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add)(DefaultMetadataProperties, XmpValue) | Fügt Wert zu XMP-Metadaten hinzu. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_4)(string, object) | Fügt dem Dictionary-Objekt ein neues Element hinzu. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_3)(string, XmpValue) | Fügt dem Dictionary-Objekt ein neues Element hinzu. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_1)(XmpPdfAExtensionObject, string, string, string) | Fügt Erweiterungsfeld zu Metadaten hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear)() | Entfernt alle Elemente aus dem Objekt. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf.Document gebunden mit einer Fassade. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains)(DefaultMetadataProperties) | Überprüft, ob das Wörterbuch die angegebene Eigenschaft enthält. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Prüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_2)(string) | Überprüft, ob das Wörterbuch den angegebenen Schlüssel enthält. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey)(string) | Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator)() | Ruft das Aufzählungsobjekt des Wörterbuchs ab. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix)(string) | Ruft Namespace-URI nach Präfix ab. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri)(string) | Ruft das Präfix nach Namespace-URI ab. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata)() | Holen Sie sich die XmpMetadata der Eingabe-PDF im XML-Format. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata_1)(string) | Holen Sie sich einen Teil der XmpMetadata des Eingabe-PDF gemäß einem Metanamen. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri)(string, string) | Registriert den Namespace-URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_2)(DefaultMetadataProperties) | Entfernt Element mit angegebenem Schlüssel. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Entfernt Schlüssel/Wert-Paare aus der Sammlung. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_1)(string) | Entfernt Schlüssel aus dem Wörterbuch. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue)(string, out XmpValue) | Versucht, den Schlüssel im Wörterbuch zu finden, und ruft den Wert ab, falls gefunden. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* class [XmpValue](../../aspose.pdf/xmpvalue)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
