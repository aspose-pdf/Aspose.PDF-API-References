---
title: PdfViewer
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt eine Klasse zum Anzeigen oder Drucken einer PDF-Datei dar.
type: docs
weight: 2640
url: /de/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Stellt eine Klasse zum Anzeigen oder Drucken einer PDF-Datei dar.

```csharp
public sealed class PdfViewer : IFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | Initialisiert neu[`PdfViewer`](../pdfviewer) Objekt. |
| [PdfViewer](pdfviewer#constructor_1)(Document) | Initialisiert neu[`PdfViewer`](../pdfviewer) Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob die Datei mit optimierter Größe gedruckt wird.  Wenn falsch Seite ohne Seitenskalierung drucken. Wenn wahr Seite mit Skalierung auf bedruckbaren Bereich drucken. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob die Datei mit automatischer Drehung gedruckt wird |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | Ruft einen AutoRotateMode-Wert ab oder legt ihn fest, der die Drehrichtung angibt |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | Holt oder setzt den Seitenkoordinatentyp (Media/Crop-Boxen). CropBox-Wert wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | Ruft den Präsentationsmodus des Formulars ab oder legt ihn fest. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die horizontale Ausrichtung angibt |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | Ruft die Seitenanzahl der aktuellen PDF-Datei ab. |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | Ruft das Passwort für das Eingabedokument ab oder legt es fest. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | Setzt oder erhält einen Modus für PdfViewer zum Drucken als Bild. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | Ruft den Namen des Dokuments in der Druckerwarteschlange ab oder legt ihn fest, wenn das Dokument gedruckt wird. Standardwert ist Dateiname. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob beim Drucken der Seitenzahldialog erzeugt wird. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | Ruft das Ergebnis des Druckauftrags ab. Bei Erfolg als null; andernfalls Ausnahmeobjekt. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | Ruft Wiedergabeoptionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | Ruft die Auflösung während des Betrachtens und Druckens ab oder legt sie fest. Je höher die Auflösung, desto langsamer. Der Standardwert ist 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | Ruft einen Gleitkommawert ab oder legt diesen fest, der den Skalierungsfaktor angibt. Der Standardwert ist 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | Ermittelt/setzt die Verwendung der Konvertierung einer PDF-Seite in eine PNG-Zwischendatei während des Druckens im Dateimodus. Verwenden Sie es, wenn die Größe der Ausgabedatei wichtig ist. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die vertikale Ausrichtung angibt |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | Initialisiert die Fassade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | Initialisiert die Fassade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | Initialisiert die Fassade. |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | Schließt die Fassade. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | Seiten der aktuellen PDF-Datei abrufen. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | Decodiert eine Seite einer PDF-Datei. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | Gibt die Fassadenressourcen frei. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | Ruft die Standardseiteneinstellungen ab. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | Ruft die Standarddruckereinstellungen ab. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | Druckt das PDF-Dokument mit dem Standarddrucker. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | Druckt das PDF-Dokument mit den Druckereinstellungen. Die Größe der Ausgabeseite entspricht der Größe der ersten Seite des Dokuments. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | Druckt das PDF-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht mit der Seitengröße kompatibel ist, erweitert pdf.kit sie, um sie an die Seitengröße anzupassen. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | Druckt das PDF-Dokument mit einem Einrichtungsdialog. Wählen Sie im Dialogfeld einen Drucker aus. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | Öffnet und druckt einen großen PDF-Stream. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | Öffnet und druckt eine große PDF-Datei. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | Öffnet und druckt einen großen PDF-Stream mit festgelegten Druckereinstellungen. Wenn Ihre PDF-Datei hunderte Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | Öffnet und druckt eine große PDF-Datei mit festgelegten Druckereinstellungen. Wenn Ihre PDF-Datei hunderte Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Öffnet und druckt einen großen PDF-Stream mit festgelegten Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF- -Datei Hunderte von Seiten oder mehr umfasst oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | Öffnet und druckt eine große PDF-Datei mit festgelegten Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF- -Datei Hunderte von Seiten oder mehr umfasst oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | Speichert das Ergebnis-PDF-Dokument im Stream. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | Speichert das Ergebnis-PDF-Dokument in einer Datei. |

### Siehe auch

* interface [IFacade](../ifacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
