---
title: PdfPageEditor
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse zum Bearbeiten der Seite der PDF-Datei einschließlich Drehen der Seite Zoomen der Seite Verschieben der Position und Ändern der Seitengröße.
type: docs
weight: 2600
url: /de/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Repräsentiert eine Klasse zum Bearbeiten der Seite der PDF-Datei, einschließlich Drehen der Seite, Zoomen der Seite, Verschieben der Position und Ändern der Seitengröße.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | Konstruktor für die PdfPageEditor-Klasse. |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | Konstruktor für die PdfPageEditor-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | Ruft die Anzeigedauer für Seiten ab oder legt sie fest. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | Ruft die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite ab oder legt sie fest, Standard ist AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | Eine Hashtabelle enthält die Seitenzahl und den Grad der Drehung, der Schlüssel stellt die Seitenzahl dar, der Wert des Schlüssels stellt die Drehung in Grad dar. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | Ruft die Seitengröße der Ausgabedatei ab oder legt sie fest. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | Ermittelt oder setzt die zu bearbeitenden Seitenzahlen. Standardmäßig wird jede Seite bearbeitet. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | Ermittelt oder setzt die Drehung der Seiten, die Drehung muss 0, 90, 180 oder 270 sein. Standardwert ist 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | Ruft die Dauer des Übergangseffekts ab oder legt sie fest. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | Ruft den zu verwendenden Übergangsstil ab oder legt ihn fest, wenn während einer Präsentation von einer anderen Seite zu dieser Seite gewechselt wird. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | Ruft die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite ab oder legt sie fest, Standard ist VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | Holt oder setzt den Zoomfaktor. Wert 1,0 entspricht 100 %. Standardwert ist 1,0.  Das folgende Beispiel zeigt, wie Sie den Zoom der Dokumentseiten ändern. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | An den Dokumentseiten vorgenommene Änderungen übernehmen. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf.Document gebunden mit einer Fassade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | Gibt die Größe des angegebenen Felds im Dokument zurück. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | Gibt die Drehung der angegebenen Seite zurück. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | Gibt die Gesamtzahl der Seiten zurück. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | Gibt die Seitengröße der angegebenen Seite zurück. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | Verschiebt den Ursprung von (0, 0) zu dem festgelegten Punkt. Der Ursprung ist links unten und die Einheit ist Punkt (1 Zoll = 72 Punkte). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | Speichert das geänderte Dokument im Stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | Speichert geändertes Dokument in Datei. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | Vertikale Jalousien |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | Vertikale Jalousien |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | Unten-Oben-Wischen |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | Diagonaler Glitzer |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | Die alte Seite löst sich auf |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | Box nach innen |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | Links-Rechts-Glitter |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | Links-rechts wischen |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | Äußere Box |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | Rechts-Links-Wischen |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | IN Horizontale Teilung |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | Aus horizontaler Teilung |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | Im vertikalen Split |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | Vertikale Teilung aus |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | Glitzer von oben nach unten |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | Wischen von oben nach unten |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
