---
title: Page
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse die die Seite des PDF-Dokuments darstellt.
type: docs
weight: 5790
url: /de/net/aspose.pdf/page/
---
## Page class

Klasse, die die Seite des PDF-Dokuments darstellt.

```csharp
public sealed class Page : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Ruft eine Sammlung von Seiteneigenschaften ab. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Ruft eine Sammlung von Seitenanmerkungen ab. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Holt oder setzt die Grafikbox der Seite. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Ruft eine Sammlung von Artefakten auf der Seite ab. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Ruft die Hintergrundfarbe der Seite ab oder legt sie fest. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Ruft das Hintergrundbild für die Seite ab oder legt es fest (nur für Generator). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Ermittelt oder setzt die Anschnittbox der Seite. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Legt den Farbtyp der Seiten basierend auf Informationen fest, die von den Operatoren SetColor, Bilder und Formulare erhalten werden. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Ruft eine Sammlung von Operatoren im Inhaltsstrom der Seite ab. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Holt oder setzt Crop-Box der Seite. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Ruft die eingestellte Seitenanzeigedauer ab. Dies ist die Zeit in Sekunden, die die Seite während der Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Ruft eine Liste von Feldobjekten in Tab-Reihenfolge auf dieser Seite ab. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Ruft den Seitenfuß ab oder legt ihn fest. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Ruft eine Gruppenattributklasse ab oder legt sie fest, die die Attribute der Seitengruppe der Seite zur Verwendung im transparenten Bildgebungsmodell angibt. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Ruft Seitenheader ab oder legt sie fest. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Holt oder setzt das Hinzufügen von Absätzen nach dem letzten Absatz der Seite |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Ruft die Ebenensammlung ab oder legt sie fest. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Holt oder setzt Medienbox der Seite. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Ruft den Linienstil für Notizen ab oder legt ihn fest. (nur für Generator) |
| [Number](../../aspose.pdf/page/number) { get; } | Nummer der Seite abrufen. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Holt oder setzt die Seiteninformationen (nur für Generator, wird beim Lesen der Datei nicht ausgefüllt). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Ruft die Absätze ab. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Holt oder setzt das Rechteck der Seite. Falls angegeben, wird Seitenzuschneidebox zurückgegeben, andernfalls wird Seitenmedienbox zurückgegeben. Bitte beachten Sie, dass diese Eigenschaft die Seitendrehung nicht berücksichtigt. Um ein Seitenrechteck unter Berücksichtigung der Drehung zu erhalten, verwenden Sie bitte ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Ruft Seitenressourcen ab. Das Ressourcenobjekt enthält Sammlungen von Bildern, Formularen und Schriftarten. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Ruft die Drehung der Seite ab oder legt sie fest. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Ruft die Transformationsmatrix für die Seite ab. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Ruft die Tab-Reihenfolge der Seite ab oder legt sie fest. Mögliche Werte: Zeile, Spalte. Standard, Manuell |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Ruft Inhaltsverzeichnisinformationen ab oder legt sie fest. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Ermittelt oder setzt den Beschnittrahmen der Seite. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Ruft den UserUnit-Wert ab oder legt ihn fest. Eine positive Zahl, die die Größe der standardmäßigen Benutzerraumeinheiten angibt, in Vielfachen von 1 ⁄ 72 Zoll. Der Standardwert ist 1. Bitte setzen Sie null oder einen negativen Wert, um diesen Eintrag auf Seite. zu löschen. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Ruft das Wasserzeichen der Seite ab oder setzt es. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Akzeptiert[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) Besucherobjekt, das Funktionen zum Arbeiten mit Anmerkungen bereitstellt. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Akzeptiert[`ImagePlacementAbsorber`](../imageplacementabsorber) Besucherobjekt, das Funktionen zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Akzeptiert[`TextAbsorber`](../../aspose.pdf.text/textabsorber) Besucherobjekt, das Funktionen zum Arbeiten mit Textobjekten bereitstellt. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Akzeptiert[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) Besucherobjekt, das Funktionen zum Arbeiten mit Textobjekten bereitstellt. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Fügt ein Bild auf der Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bilds gespeichert werden. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Fügt ein Bild auf der Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bilds gespeichert werden. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Fügt ein durchsuchbares Bild auf der Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bilds gespeichert werden. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Fügt ein Bild auf der Seite hinzu und platziert es abhängig von der Position des Bildrechtecks. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Stempel in Seite setzen. Der Stempel kann eine Seitennummer, ein Bild oder einfacher Text sein, z. B. ein Logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Konvertiert die aktuelle Seite als Bitmap und gibt dann ein Array von Bytes zurück. |
| [AsXml](../../aspose.pdf/page/asxml)() | Konvertiert die aktuelle Seite als xml in utf8-Kodierung. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Berechnet den Bbox-Wert - Rechteck mit Inhalt ohne sichtbare Ränder. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Seite für DSR-, OMR- und OCR-Bildstream in PNG konvertieren. |
| [Dispose](../../aspose.pdf/page/dispose)() | Gibt Speicher frei |
| [Flatten](../../aspose.pdf/page/flatten)() | Entfernt alle Felder auf der Seite und setzt stattdessen ihre Werte. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Löscht zwischengespeicherte Daten |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Gibt Benachrichtigungen über interne Vorgänge mit Seiteninhalt zurück. (Es werden jetzt nur Benachrichtigungen über Absatzereignisse in Szenarios zum Hinzufügen von Text unterstützt.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Gibt das Rechteck der Seite zurück. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Ruft das Flag ab, ob die Seite leer ist oder nicht. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Wandelt die Seite in Graustufen um. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Sendet die Seite zur Verarbeitung mit dem angegebenen Seitengerät. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Sendet die Seite zur Verarbeitung mit dem angegebenen Seitengerät. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Legt die Seitengröße für die Seite fest. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Übersetzt den ganzzahligen Wert in das entsprechende Element der Rotationsaufzählung. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Übersetzt das Element der Rotationsaufzählung in einen ganzzahligen Wert. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Verfahren zum Anpassen von Kopf- und Fußzeile. |

### Siehe auch

* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
