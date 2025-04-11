---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer-Klasse. Stellt eine Klasse zum Anzeigen oder Drucken eines PDFs dar
type: docs
weight: 4630
url: /de/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer-Klasse

Stellt eine Klasse zum Anzeigen oder Drucken eines PDFs dar.

```csharp
public sealed class PdfViewer : IFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Initialisiert ein neues `PdfViewer`-Objekt. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Initialisiert ein neues `PdfViewer`-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob die Datei mit optimierter Größe gedruckt werden soll. Wenn false, wird die Seite ohne Seitenvergrößerung gedruckt. Wenn true, wird die Seite mit einer Skalierung gedruckt, um in den druckbaren Bereich zu passen. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob die Datei mit automatischer Drehung gedruckt werden soll. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Ruft einen AutoRotateMode-Wert ab oder legt ihn fest, der die Drehrichtung angibt. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der die horizontale Ausrichtung angibt. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Ruft die Seitenanzahl der aktuellen PDF-Datei ab. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Ruft das Passwort des Eingabedokuments ab oder legt es fest. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Legt einen Modus für PdfViewer fest, um als Bild zu drucken. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Ruft den Namen des Dokuments in der Druckwarteschlange ab oder legt ihn fest, wenn das Dokument gedruckt wird. Der Standardwert ist der Dateiname. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob beim Drucken das Seitenzahlendialogfeld angezeigt werden soll. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Ruft das Ergebnis des Druckauftrags ab. Wenn erfolgreich, dann null; andernfalls ein Ausnahmeobjekt. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Ruft die Auflösung während der Anzeige und des Druckens ab oder legt sie fest. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Ruft einen Fließkommawert ab oder legt ihn fest, der den Skalierungsfaktor angibt. Der Standardwert ist 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Ruft die Verwendung der Konvertierung der PDF-Seite in eine Zwischen-PNG-Datei während des Druckens im Dateimodus ab oder legt sie fest. Verwenden Sie es, wenn die Größe der Ausgabedatei wichtig ist. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der die vertikale Ausrichtung angibt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Initialisiert die Fassade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Initialisiert die Fassade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Initialisiert die Fassade. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Schließt die Fassade. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Ruft die Seiten der aktuellen PDF-Datei ab. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Dekodiert eine Seite einer PDF-Datei. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Gibt die Ressourcen der Fassade frei. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Ruft die standardmäßigen Seiteneinstellungen ab. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Ruft die standardmäßigen Druckereinstellungen ab. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Druckt das PDF-Dokument mit dem Standarddrucker. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Druckt das PDF-Dokument mit Druckereinstellungen. Die Ausgabeseitengröße passt sich zuerst der Seitengröße des Dokuments an. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Druckt das PDF-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht der Seitengröße entspricht, wird sie erweitert, um in die Seitengröße zu passen. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Druckt das PDF-Dokument mit einem Einrichtungsdialog. Wählen Sie einen Drucker über den Dialog aus. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Öffnet und druckt einen großen PDF-Stream. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird empfohlen, diese Methode für eine bessere Leistung zu verwenden. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Öffnet und druckt eine große PDF-Datei. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird empfohlen, diese Methode für eine bessere Leistung zu verwenden. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Öffnet und druckt einen großen PDF-Stream mit angegebenen Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird empfohlen, diese Methode für eine bessere Leistung zu verwenden. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Öffnet und druckt eine große PDF-Datei mit angegebenen Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird empfohlen, diese Methode für eine bessere Leistung zu verwenden. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Öffnet und druckt einen großen PDF-Stream mit angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird empfohlen, diese Methode für eine bessere Leistung zu verwenden. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Öffnet und druckt eine große PDF-Datei mit angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird empfohlen, diese Methode für eine bessere Leistung zu verwenden. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Speichert das resultierende PDF-Dokument im Stream. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Speichert das resultierende PDF-Dokument in einer Datei. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Tritt auf, bevor das Drucken beginnt, und ermöglicht es, benutzerdefinierte Druckhandler anstelle des Standardhandlers bereitzustellen. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Tritt auf, wenn das Drucken einer Seite im PdfViewer endet. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Fügt Abonnements für das Ereignis des Druckens der letzten Seite hinzu/entfernt. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Fügt Abonnements für das Ereignis des Druckens der letzten Seite hinzu/entfernt. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Tritt auf, bevor eine Seite zu drucken beginnt. |

### Siehe auch

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)