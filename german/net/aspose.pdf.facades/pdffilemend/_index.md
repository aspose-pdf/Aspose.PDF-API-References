---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend-Klasse. Stellt eine Klasse zum Hinzufügen von Texten und Bildern auf den Seiten eines vorhandenen PDF-Dokuments dar
type: docs
weight: 4530
url: /de/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend-Klasse

Stellt eine Klasse zum Hinzufügen von Texten und Bildern auf den Seiten eines vorhandenen PDF-Dokuments dar.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Konstruktor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Initialisiert ein neues `PdfFileMend`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Setzt einen booleschen Wert, der den Zeilenumbruch in den AddText-Methoden angibt. Wenn der Wert true ist, wird der Text in FormatiertemText umgebrochen. Standardmäßig ist der Wert false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Setzt oder erhält die Textpositionierungsstrategie. [`PositioningMode`](../positioningmode/) Der Standardmodus ist Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Setzt oder erhält den Algorithmus für den Zeilenumbruch. Siehe WordWrapMode und IsWordWrap. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Nicht implementiert. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Nicht implementiert. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Nicht implementiert. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Schließt das PdfFileMend-Objekt. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)