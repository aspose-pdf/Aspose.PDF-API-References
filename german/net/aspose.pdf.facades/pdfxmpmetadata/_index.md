---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata-Klasse. Klasse zur Manipulation von XMP-Metadaten
type: docs
weight: 4640
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata-Klasse

Klasse zur Manipulation von XMP-Metadaten.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Konstruktor für PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Initialisiert ein neues `PdfXmpMetadata`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Gibt das Wörterbuch der Erweiterungsfelder zurück. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Gibt true zurück, wenn die Sammlung eine feste Größe hat. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Gibt true zurück, wenn die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Gibt true zurück, wenn die Sammlung synchronisiert ist. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Gibt den Wert nach Schlüssel zurück oder setzt ihn. (2 Indizes) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Gibt die Schlüssel aus dem Wörterbuch zurück. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Gibt das Synchronisationsobjekt der Sammlung zurück. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Gibt die Sammlung der Werte im Wörterbuch zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Fügt ein Paar mit Schlüssel und Wert in das Wörterbuch ein. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Fügt einen Wert zu den XMP-Metadaten hinzu. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Fügt ein neues Element zum Wörterbuchobjekt hinzu. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Fügt ein neues Element zum Wörterbuchobjekt hinzu. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Fügt ein Erweiterungsfeld zu den Metadaten hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Entfernt alle Elemente aus dem Objekt. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Gibt das mit einer Fassade verbundene Aspose.Pdf.Document frei. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Überprüft, ob das Wörterbuch die angegebene Eigenschaft enthält. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Überprüft, ob das Wörterbuch den angegebenen Schlüssel enthält. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Bestimmt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Gibt das Enumerator-Objekt des Wörterbuchs zurück. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Gibt die Namespace-URI nach Präfix zurück. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Gibt das Präfix nach Namespace-URI zurück. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Holt die XmpMetadata des Eingabe-PDF im XML-Format. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Holt einen Teil der XmpMetadata des Eingabe-PDF gemäß einem Metanamen. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registriert die Namespace-URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Entfernt das Element mit dem angegebenen Schlüssel. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Entfernt das Schlüssel/Wert-Paar aus der Sammlung. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Entfernt den Schlüssel aus dem Wörterbuch. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Versucht, den Schlüssel im Wörterbuch zu finden und den Wert zurückzugeben, wenn er gefunden wurde. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Klasse [XmpValue](../../aspose.pdf/xmpvalue/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)