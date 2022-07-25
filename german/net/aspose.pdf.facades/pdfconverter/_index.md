---
title: PdfConverter
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse zum Konvertieren jeder Seite einer PDF-Datei in Bilder und unterstützt jetzt BMP JPEG PNG und TIFF. Unterstützte Inhalte in PDFs Bilder Formulare Kommentare.
type: docs
weight: 2450
url: /de/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Repräsentiert eine Klasse zum Konvertieren jeder Seite einer PDF-Datei in Bilder und unterstützt jetzt BMP, JPEG, PNG und TIFF. Unterstützte Inhalte in PDFs: Bilder, Formulare, Kommentare.

```csharp
public sealed class PdfConverter : Facade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Initialisiert neu[`PdfConverter`](../pdfconverter) Objekt. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Initialisiert neu[`PdfConverter`](../pdfconverter) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Holt oder setzt den Seitenkoordinatentyp (Media/Crop-Boxen). CropBox-Wert wird standardmäßig verwendet. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Ermittelt oder setzt die Endposition, die Sie konvertieren möchten. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Ruft den Präsentationsmodus des Formulars ab oder legt ihn fest. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Ruft die Seitenanzahl ab. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | Ruft das OwnerPassword des Dokuments ab oder legt es fest. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Ruft Wiedergabeoptionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Liest oder setzt die Auflösung während der Konvertierung. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Ermittelt oder setzt die Startposition, die Sie konvertieren möchten. Der Mindestwert ist 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | Ruft das Benutzerpasswort für das Dokument ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | Bindet einen PDF-Stream für convert. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Bindet eine PDF-Datei zum Konvertieren. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | Schließen Sie die Instanz von PdfConverter und geben Sie die Ressourcen frei. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Führen Sie einige erste Arbeiten zum Konvertieren eines PDF-Dokuments in Bilder durch. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Speichert das Bild im Stream mit dem Standardbildformat - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Speichert das Bild in einer Datei mit dem Standardbildformat - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Speichert das Bild im Stream mit dem angegebenen Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Speichert das Bild im Stream mit der angegebenen Seitengröße. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Standardbildformat - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Speichert Bild im Stream mit gegebenem Bildformat und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Speichert das Bild im Stream mit der angegebenen Seitengröße. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Speichert Bild in Datei mit vorgegebenem Bildformat und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Speichert Bild in Datei mit gegebener Seitengröße und Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Speichert das Bild im Stream mit dem angegebenen Bildformat, der angegebenen Größe und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Speichert das Bild mit gegebener Seitengröße, Bildformat und Qualität im Stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat und den angegebenen Abmessungen. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Speichert Bild in Datei mit gegebener Seitengröße, Bildformat und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Speichert das Bild im Stream mit dem angegebenen Bildformat, der angegebenen Größe und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Speichert das Bild im Stream mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat, Bildgröße und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Speichert das Bild mit dem angegebenen Bildformat, den Abmessungen und der Qualität in einer Datei. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Gibt an, ob die PDF-Datei mehr Bilder enthält oder nicht. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF ClassF-Stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-ClassF-Datei. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF ClassF-Stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-ClassF-Datei. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF ClassF-Stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-ClassF-Datei. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Führt eine Liste von Bildströmen zu einem Bildstrom zusammen. Png/jpg/tiff-Ausgabeformate werden unterstützt, bei Verwendung eines nicht unterstützten Formats ist der Ausgabestrom standardmäßig als JPEG kodiert. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | Führt eine Liste von TIFF-Streams zu einem TIFF-Stream mit mehreren Frames zusammen. |

### Siehe auch

* class [Facade](../facade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
