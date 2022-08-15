---
title: MovieAnnotation
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt eine Filmanmerkung dar die animierte Grafiken und Ton enthält die auf dem Computerbildschirm und über die Lautsprecher angezeigt werden. Wenn die Anmerkung aktiviert ist wird der Film abgespielt.
type: docs
weight: 730
url: /de/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Stellt eine Filmanmerkung dar, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher angezeigt werden. Wenn die Anmerkung aktiviert ist, wird der Film abgespielt.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MovieAnnotation](movieannotation#constructor)(Document, string) | Konstruktor zur Verwendung mit Generator. |
| [MovieAnnotation](movieannotation#constructor_1)(Page, Rectangle, string) | Erstellt eine neue Tonanmerkung auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ruft eine Liste mit Anmerkungsaktionen ab. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ruft den aktuellen Darstellungszustand der Anmerkung ab oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype) { get; } | Ruft die Art der Anmerkung ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ruft das Darstellungswörterbuch der Anmerkung ab. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect) { get; set; } | Ruft die Breite und Höhe des Begrenzungsrahmens des Films in Pixel ab oder legt diese fest. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ruft Anmerkungsrandeigenschaften ab oder legt sie fest.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ruft Anmerkungsmerkmale ab. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ruft die Anmerkungsfarbe ab oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ruft den Anmerkungstext ab oder legt ihn fest. |
| [File](../../aspose.pdf.annotations/movieannotation/file) { get; set; } | Ruft eine Dateispezifikation ab oder legt diese fest, die eine selbstbeschreibende Filmdatei identifiziert. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flags der Anmerkung. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ruft den vollständig qualifizierten Namen der Anmerkung ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ruft die Höhe der Anmerkung ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Holt oder setzt den Fragment-Hyperlink (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist „false“.(für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ruft ab oder legt fest, dass ein Absatz inline ist. Standard ist „false“.(für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Der Standardwert ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite verbleibt. Der Standardwert ist „false“. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Liest oder setzt einen Außenrand für Absatz (für PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ruft Datum und Uhrzeit der letzten Änderung der Anmerkung ab oder legt sie fest. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ruft den Anmerkungsnamen auf der Seite ab oder legt ihn fest. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ruft den Index der Seite ab, die Anmerkungen enthält. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster) { get; set; } | Ruft oder setzt ein Flag oder einen Stream, der angibt, ob und wie ein Posterbild, das den Film darstellt, angezeigt werden soll. Wenn wahr, soll das Posterbild aus der Filmdatei abgerufen werden; wenn es falsch ist, wird kein Poster angezeigt. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ruft das Anmerkungsrechteck ab oder legt es fest. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate) { get; set; } | Ermittelt oder setzt die Gradzahl, um die der Film relativ zur Seite im Uhrzeigersinn gedreht werden soll. Der Wert muss ein Vielfaches von 90. sein |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ruft das Darstellungswörterbuch der Anmerkung ab. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ruft die Textausrichtung für Anmerkungen ab oder legt sie fest. |
| [Title](../../aspose.pdf.annotations/movieannotation/title) { get; set; } | Ruft den Titel der Filmanmerkung ab oder legt ihn fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Holt oder setzt eine vertikale Ausrichtung des Absatzes |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ruft die Breite der Anmerkung ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Diagramms angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Grafik mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept)(AnnotationSelector) | Akzeptiert das Besucherobjekt, um die Anmerkung zu verarbeiten. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aktualisieren Sie Parameter und Aussehen gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klont diese Instanz. Virtuelle Methode. Immer null zurückgeben. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Platziert Anmerkungsinhalte direkt auf der Seite, Anmerkungsobjekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitendrehung berücksichtigt wird. |

### Siehe auch

* class [Annotation](../annotation)
* namensraum [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
