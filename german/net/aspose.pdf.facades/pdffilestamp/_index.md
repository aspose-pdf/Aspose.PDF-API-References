---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileStamp-Klasse. Klasse zum Hinzufügen von Stempeln, Wasserzeichen oder Hintergründen zu PDF-Dateien
type: docs
weight: 4570
url: /de/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp-Klasse

Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Konstruktor der PdfFileStamp. Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Initialisiert ein neues `PdfFileStamp`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Legt das PDF-Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard-PDF-Format ohne Konvertierung gespeichert. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Beibehaltung der Sicherheit, wenn wahr. (Dieses Feature wird in den nächsten Versionen implementiert). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Gibt den Seitenzahlstil an oder setzt ihn. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Gibt das Optimierungsflag an oder setzt es. Gleiche Ressourcenströme in der resultierenden Datei werden in ein PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der Dateigröße, kann jedoch zu langsamerer Ausführung und höheren Speicheranforderungen führen. Standardwert: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Gibt die Höhe der ersten Seite in der Quelldatei zurück. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Gibt die Drehung der Seitenzahl an oder setzt sie. Die Drehung erfolgt in Grad. Standard ist 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Gibt die Breite der ersten Seite in der Eingabedatei zurück. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | Stempel-ID des nächsten hinzugefügten Stempels (einschließlich Seitenkopf-/fußzeilen/seitennummern). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Gibt die Startnummer für die erste Seite in der Eingabedatei an oder setzt sie. Die nächsten Seiten werden ab diesem Wert nummeriert. Wenn beispielsweise die StartingNumber auf 100 gesetzt ist, haben die Dokumentseiten die Nummern 100, 101, 102... |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Fügt den Seiten des Dokuments einen Fußzeilentext hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Fügt den Seiten des Dokuments einen Fußzeilentext hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Fügt ein Bild als Fußzeile der Seiten hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Fügt der Seite einen Kopfzeilentext hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Fügt ein Bild als Kopfzeile auf den Seiten hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Fügt ein Bild als Kopfzeile zu den Seiten der Datei hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Fügt den Seiten der Datei einen Kopfzeilentext hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Fügt ein Bild oben auf der Seite hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Fügt ein Bild als Kopfzeile auf den Seiten hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Fügt der Seite eine Seitenzahl hinzu. Die Seitenzahl kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Fügt die Seitenzahl zur Datei hinzu. Der Seitenzahltext kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Fügt den Seiten die Seitenzahl hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Fügt den Seiten die Seitenzahl hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Fügt die Seitenzahl an der angegebenen Position auf der Seite hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Fügt die Seitenzahl an der angegebenen Position auf der Seite hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Fügt den Seiten die Seitenzahl des Dokuments hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Fügt den Seiten die Seitenzahl des Dokuments hinzu. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Fügt dem Dokument einen Stempel hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Schließt geöffnete Dateien und speichert Änderungen. Warnung: Wenn Eingabe- oder Ausgabeströme angegeben sind, werden diese nicht durch die Close()-Methode geschlossen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Speichert das Dokument im angegebenen Stream. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Speichert das Ergebnis in der angegebenen Datei. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Untere linke Position. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Untere mittlere Position. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Untere rechte Position. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Linke Position. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Rechte Position. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Obere linke Position. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Obere mittlere Position. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Obere rechte Position. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)