---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor-Klasse. Stellt eine Klasse zum Bearbeiten der PDF-Dateiseiten dar, einschließlich Drehen der Seite, Vergrößern der Seite, Verschieben der Position und Ändern der Seitengröße
type: docs
weight: 4590
url: /de/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor-Klasse

Stellt eine Klasse zum Bearbeiten der PDF-Dateiseiten dar, einschließlich Drehen der Seite, Vergrößern der Seite, Verschieben der Position und Ändern der Seitengröße.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Konstruktor für die PdfPageEditor-Klasse. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Konstruktor für die PdfPageEditor-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Ruft die Anzeigedauer für Seiten ab oder legt sie fest. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ruft die Dokumentenfacade ab, an der gearbeitet wird. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite ab oder legt sie fest, Standard ist AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Eine Hashtable, die die Seitennummer und den Rotationsgrad enthält, der Schlüssel stellt die Seitennummer dar, der Wert des Schlüssels stellt die Rotation in Grad dar. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Ruft die Seitengröße der Ausgabedatei ab oder legt sie fest. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Ruft die zu bearbeitenden Seitennummern ab oder legt sie fest. Standardmäßig wird jede Seite bearbeitet. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Ruft die Rotation der Seiten ab oder legt sie fest, die Rotation muss 0, 90, 180 oder 270 sein. Standardwert ist 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Ruft die Dauer des Übergangseffekts ab oder legt sie fest. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Ruft den Übergangsstil ab oder legt ihn fest, der verwendet werden soll, wenn zu dieser Seite von einer anderen während einer Präsentation gewechselt wird. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Ruft die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite ab oder legt sie fest, Standard ist VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Ruft den Zoomfaktor ab oder legt ihn fest. Wert 1.0 entspricht 100 %. Standardwert ist 1.0. Das folgende Beispiel zeigt, wie man den Zoom der Dokumentseiten ändert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Wendet die Änderungen an den Dokumentseiten an. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Gibt das mit einer Facade verbundene Aspose.Pdf.Document frei. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Facade frei. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Gibt die Größe des angegebenen Feldes im Dokument zurück. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Gibt die Rotation der angegebenen Seite zurück. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Gibt die Gesamtanzahl der Seiten zurück. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Gibt die Seitengröße der angegebenen Seite zurück. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Verschiebt den Ursprung von (0, 0) zu dem angegebenen Punkt. Der Ursprung ist links unten und die Einheit ist Punkt (1 Zoll = 72 Punkte). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Speichert das geänderte Dokument im Stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Speichert das geänderte Dokument in einer Datei. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Vertikale Jalousien |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Vertikale Jalousien |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Wischen von unten nach oben |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Diagonales Glitzern |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Die alte Seite löst sich auf |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Eingehende Box |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Links-Rechts-Glitzern |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Links-Rechts-Wischen |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Ausgehende Box |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Rechts-Links-Wischen |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | IN Horizontale Teilung |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Aus Horizontale Teilung |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | In Vertikale Teilung |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Aus Vertikale Teilung |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Oben-Unten-Glitzern |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Oben-Unten-Wischen |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)