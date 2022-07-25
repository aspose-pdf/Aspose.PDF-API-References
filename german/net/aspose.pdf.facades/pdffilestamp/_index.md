---
title: PdfFileStamp
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse zum Hinzufügen von Stempeln Wasserzeichen oder Hintergrund zu PDF-Dateien.
type: docs
weight: 2580
url: /de/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | Konstruktor des PdfFileStamp. Eingabedatei und Ausgabedatei können über entsprechende Eigenschaften spezifiziert werden. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Initialisiert neu[`PdfFileStamp`](../pdffilestamp) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | Ruft den Namen des Anhangs ab oder legt ihn fest, wenn das Ergebnis der Operation als Anhang in HttpResponse-Objekten gespeichert wird. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | Ruft ab oder legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation im HttpResponse-Objekt gespeichert wird. Möglicher Wert: inline / attachment. Standard: inline. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | Legt das PDF-Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei ohne Konvertierung im Standard-PDF-Format gespeichert. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Behält die Sicherheit bei, wenn wahr. (Diese Funktion wird in den nächsten Versionen implementiert). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Holt oder setzt Seitennummerierungsstil. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Holt oder setzt Optimierungs-Flag. Gleiche Ressourcenströme in der resultierenden Datei werden zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der resultierenden Dateigröße, kann jedoch zu einer langsameren Ausführung und größeren Speicheranforderungen führen. Standardwert: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Ruft die Höhe der ersten Seite in der Quelldatei ab. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Ruft die Drehung der Seitennummer ab oder legt sie fest. Die Drehung erfolgt in Grad. Standard ist 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Ruft die Breite der ersten Seite in der Eingabedatei ab. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | Ruft das Antwortobjekt ab oder legt es fest, in dem das Ergebnis der Operation gespeichert wird. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Ruft Speicheroptionen ab oder legt sie fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | Stempel-ID des nächsten hinzugefügten Stempels (einschließlich Seitenüberschriften/Hupen/Seitenzahlen). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Ermittelt oder setzt die Startnummer für die erste Seite in der Eingabedatei. Die nächsten Seiten werden ab diesem Wert nummeriert. Wenn zum Beispiel StartingNumber auf 100 eingestellt ist, haben Dokumentseiten die Nummern 100, 101, 102... |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Fügt den Seiten des Dokuments eine Fußzeile hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Fügt den Seiten des Dokuments ein Bild als Fußzeile hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Fügt den Seiten des Dokuments eine Fußzeile hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Fügt ein Bild als Fußzeile der Seiten hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Fügt der Seite eine Kopfzeile hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Fügt ein Bild als Kopfzeile auf den Seiten hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Fügt den Seiten der Datei ein Bild als Kopfzeile hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Fügt Kopfzeilen zu den Seiten der Datei hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Fügt ein Bild oben auf der Seite hinzu. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Fügt ein Bild als Kopfzeile auf den Seiten hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Fügt der Seite eine Seitenzahl hinzu. Die Seitenzahl kann ein #-Zeichen enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird unten auf der Seite horizontal zentriert platziert. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Seitenzahl zur Datei hinzufügen. Seitenzahlentext kann ein #-Zeichen enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird unten auf der Seite horizontal zentriert platziert. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Fügt Seitenzahlen zu den Seiten hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Fügt Seitenzahlen zu den Seiten hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Fügt eine Seitenzahl an der angegebenen Position auf der Seite hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Fügt eine Seitenzahl an der angegebenen Position auf der Seite hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Fügt Seitenzahlen zu den Seiten des Dokuments hinzu. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Fügt Seitenzahlen zu den Seiten des Dokuments hinzu. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Fügt der Datei einen Stempel hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Schließt geöffnete Dateien und speichert Änderungen. Warnung. Wenn Eingabe- oder Ausgabestreams angegeben sind, werden sie nicht durch die Close()-Methode geschlossen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Speichert das Dokument im angegebenen Stream. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Speichert das Ergebnis in der angegebenen Datei. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Position unten links. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Untere mittlere Position. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Position unten rechts. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Linke Position. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Rechte Position. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Obere linke Position. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Obere mittlere Position. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Rechte obere Position. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
