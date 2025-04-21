---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfConverter-Klasse. Stellt eine Klasse dar, um jede Seite einer PDF-Datei in Bilder zu konvertieren, die BMP, JPEG, PNG und TIFF unterstützen. Unterstützter Inhalt in PDFs Bilder, Formulare, Kommentare.
type: docs
weight: 4440
url: /de/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter-Klasse

Stellt eine Klasse dar, um jede Seite einer PDF-Datei in Bilder zu konvertieren, die BMP, JPEG, PNG und TIFF unterstützen. Unterstützter Inhalt in PDFs: Bilder, Formulare, Kommentare.

```csharp
public sealed class PdfConverter : Facade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Initialisiert ein neues `PdfConverter`-Objekt. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Initialisiert ein neues `PdfConverter`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ruft die Dokumentenfacade ab, an der gearbeitet wird. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Ruft die Endposition ab oder legt sie fest, die Sie konvertieren möchten. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Ruft die Seitenanzahl ab. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Ruft das Dokumenten-OwnerPassword ab oder legt es fest. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Ruft die Auflösung während der Konvertierung ab oder legt sie fest. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Ruft die Startposition ab oder legt sie fest, die Sie konvertieren möchten. Der minimale Wert ist 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Ruft das Dokumenten-UserPassword ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Bindet einen PDF-Stream zur Konvertierung. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Bindet eine PDF-Datei zur Konvertierung. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Schließt die Instanz von PdfConverter und gibt die Ressourcen frei. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Facade frei. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Führt einige Vorarbeiten zur Konvertierung eines PDF-Dokuments in Bilder durch. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Speichert das Bild im Stream im Standardbildformat - JPEG. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Speichert das Bild in einer Datei im Standardbildformat - JPEG. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Speichert das Bild im Stream im angegebenen Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Speichert das Bild im Stream mit der angegebenen Seitengröße. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Speichert das Bild in einer Datei im angegebenen Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Standardbildformat - JPEG. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Speichert das Bild im Stream im angegebenen Bildformat und in der angegebenen Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Speichert das Bild im Stream mit der angegebenen Seitengröße. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Speichert das Bild in einer Datei im angegebenen Bildformat und in der angegebenen Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Speichert das Bild im Stream im angegebenen Bildformat, in der angegebenen Größe und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Speichert das Bild im Stream mit der angegebenen Seitengröße, dem Bildformat und der Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Speichert das Bild in einer Datei im angegebenen Bildformat und den Abmessungen. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße, dem Bildformat und der Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Speichert das Bild im Stream im angegebenen Bildformat, in der angegebenen Größe und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Speichert das Bild im Stream im angegebenen Bildformat, in den Abmessungen und der Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Speichert das Bild in einer Datei im angegebenen Bildformat, der Bildgröße und Qualität. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Speichert das Bild in einer Datei im angegebenen Bildformat, den Abmessungen und der Qualität. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Gibt an, ob die PDF-Datei weitere Bilder enthält oder nicht. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Fügt eine Liste von Bildstreams zu einem Bildstream zusammen. PNG/JPG/TIFF-Ausgabeformate werden unterstützt; im Falle der Verwendung eines nicht unterstützten Ausgabeformats wird der Ausgabestream standardmäßig als JPEG kodiert. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Fügt eine Liste von TIFF-Streams zu einem einzelnen Mehrfachrahmen-TIFF-Stream zusammen. |

### Siehe auch

* Klasse [Facade](../facade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)