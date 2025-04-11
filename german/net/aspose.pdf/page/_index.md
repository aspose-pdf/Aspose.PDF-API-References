---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Page-Klasse. Klasse, die eine Seite des PDF-Dokuments darstellt
type: docs
weight: 8050
url: /de/net/aspose.pdf/page/
---
## Seitenklasse

Klasse, die eine Seite des PDF-Dokuments darstellt.

```csharp
public sealed class Page : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Gibt die Sammlung von Seiten Eigenschaften zurück. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Gibt die Sammlung von Seitenanmerkungen zurück. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Gibt die Kunstbox der Seite zurück oder setzt sie. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Gibt die Sammlung von Artefakten auf der Seite zurück. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Gibt die Hintergrundfarbe der Seite zurück oder setzt sie. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Gibt das Hintergrundbild für die Seite zurück oder setzt es (nur für Generator, nicht ausgefüllt beim Lesen des Dokuments). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Gibt die Beschnittbox der Seite zurück oder setzt sie. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Setzt den Farbtyp der Seiten basierend auf Informationen von den Operatoren SetColor, Bildern und Formularen. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Gibt die Sammlung von Operatoren im Inhaltsstrom der Seite zurück. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Gibt die Zuschneidebox der Seite zurück oder setzt sie. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Gibt die Anzeige-Dauer der Seite zurück oder setzt sie. Dies ist die Zeit in Sekunden, die die Seite während der Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Gibt die Liste der Feldobjekte in Tab-Reihenfolge auf dieser Seite zurück. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Gibt die Fußzeile der Seite zurück oder setzt sie. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Gibt eine Gruppenattributklasse zurück oder setzt sie, die die Attribute der Seiten-Gruppe für die Verwendung im transparenten Bildmodell angibt. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Gibt die Kopfzeile der Seite zurück oder setzt sie. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Gibt die Hinzufügung von Absätzen nach dem letzten Absatz der Seite zurück oder setzt sie. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Gibt die Sammlung von Ebenen zurück oder setzt sie. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Gibt die Medienbox der Seite zurück oder setzt sie. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Gibt den Linienstil für Notizen zurück oder setzt ihn. (nur für Generator, nicht ausgefüllt beim Lesen des Dokuments) |
| [Number](../../aspose.pdf/page/number/) { get; } | Gibt die Nummer der Seite zurück. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Gibt die Seiteninformationen zurück oder setzt sie (nur für Generator, nicht ausgefüllt beim Lesen des Dokuments). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Gibt die Absätze zurück. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Gibt das Rechteck der Seite zurück oder setzt es. Für get: die Seiten-Zuschneidebox wird zurückgegeben, wenn angegeben, andernfalls wird die Seiten-Medienbox zurückgegeben. Für set: die Seiten-Medienbox wird immer gesetzt. Bitte beachten Sie, dass diese Eigenschaft die Seitenrotation nicht berücksichtigt. Um das Seitenrechteck unter Berücksichtigung der Rotation zu erhalten, verwenden Sie bitte ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Gibt die Seitenressourcen zurück. Das Ressourcenobjekt enthält Sammlungen von Bildern, Formularen und Schriftarten. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Gibt die Rotation der Seite zurück oder setzt sie. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Gibt die Transformationsmatrix für die Seite zurück. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Gibt die Tab-Reihenfolge der Seite zurück oder setzt sie. Mögliche Werte: Zeile, Spalte. Standard, Manuell |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Gibt die Informationen zum Inhaltsverzeichnis zurück oder setzt sie. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Gibt die Beschnittbox der Seite zurück oder setzt sie. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Gibt den Wert von UserUnit zurück oder setzt ihn. Eine positive Zahl, die die Größe der Standardbenutzereinheiten in Vielfachen von 1 / 72 Zoll angibt. Der Standardwert ist 1. Bitte setzen Sie einen Wert von null oder negativ, um diesen Eintrag auf der Seite zu löschen. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Gibt das Wasserzeichen der Seite zurück oder setzt es. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Akzeptiert [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) Besucherobjekt, das Funktionen zum Arbeiten mit Anmerkungen bereitstellt. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Akzeptiert [`ImagePlacementAbsorber`](../imageplacementabsorber/) Besucherobjekt, das Funktionen zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Akzeptiert [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) Besucherobjekt, das Funktionen zum Arbeiten mit Textobjekten bereitstellt. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Akzeptiert [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) Besucherobjekt, das Funktionen zum Arbeiten mit Textobjekten bereitstellt. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Fügt der Seite Grafiken hinzu. Funktioniert schneller als das Hinzufügen von Elementen einzeln mit der Methode [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Fügt ein Bild auf die Seite hinzu und platziert es in der Mitte des angegebenen Rechtecks, wobei das Verhältnis des Bildes beibehalten wird. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Fügt ein Bild auf die Seite hinzu und platziert es in der Mitte des angegebenen Rechtecks, wobei das Verhältnis des Bildes beibehalten wird. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Fügt ein durchsuchbares Bild auf die Seite hinzu und platziert es in der Mitte des angegebenen Rechtecks, wobei das Verhältnis des Bildes beibehalten wird. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Fügt ein Bild auf die Seite hinzu und platziert es abhängig von der Position des Bildrechtecks. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Fügt einen Stempel in die Seite ein. Der Stempel kann eine Seitenzahl, ein Bild oder einfacher Text, z.B. ein Logo, sein. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Konvertiert die aktuelle Seite in ein Bitmap und gibt dann ein Byte-Array zurück. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Konvertiert die aktuelle Seite in XML mit UTF-8-Codierung. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Berechnet den BBox-Wert - ein Rechteck, das den Inhalt ohne sichtbare Ränder enthält. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Konvertiert die Seite in PNG für DSR, OMR, OCR-Bildstrom. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Löscht Grafiken von der Seite. Funktioniert schneller als das Löschen von Elementen einzeln mit der Methode [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Gibt den Speicher frei |
| [Flatten](../../aspose.pdf/page/flatten/)() | Entfernt alle auf der Seite befindlichen Felder und ersetzt deren Werte. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Löscht zwischengespeicherte Daten |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Gibt Benachrichtigungen über interne Vorgänge mit dem Seiteninhalt zurück. (Derzeit werden nur Benachrichtigungen über Absatzereignisse in Text-Hinzufügungsszenarien unterstützt.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Gibt das Rechteck der Seite gemäß ihrer CropBox (oder MediaBox, wenn CropBox null) zurück. |
| [GetResources](../../aspose.pdf/page/getresources/)() | Ruft die mit der Seite verbundenen Ressourcen ab. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Erkennt das Vorhandensein von Vektorgrafiken, wenn sie auf der Seite vorhanden sind. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Gibt das Flag zurück, ob die Seite leer ist oder nicht. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Konvertiert die Seite in Graustufen. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Führt alle Ebenen auf der Seite in eine einzelne Ebene mit dem angegebenen neuen Ebenennamen zusammen. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Führt alle Ebenen auf der Seite in eine einzelne Ebene mit dem angegebenen neuen Ebenennamen und optionaler Inhaltsgruppen-ID zusammen. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Ändert die Größe der Seite. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Sendet die Seite zur Verarbeitung mit dem angegebenen Seiten-Gerät. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Sendet die Seite zur Verarbeitung mit dem angegebenen Seiten-Gerät. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Setzt die Seitengröße für die Seite. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Versucht, Vektorgrafiken zu speichern, wenn sie auf der Seite vorhanden sind. Das Speicherformat ist SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Übersetzt den ganzzahligen Wert in das entsprechende Rotationsenumerationsmitglied. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Übersetzt das Rotationsenumerationsmitglied in einen ganzzahligen Wert. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Ereignis zur Anpassung von Kopf- und Fußzeile. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Verfahren zur Anpassung von Kopf- und Fußzeile. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)