---
title: TextMarkupAnnotation
second_title: Aspose.PDF für .NET-API-Referenz
description: Abstrakte Basisklasse für Textmarkup-Anmerkungen.
type: docs
weight: 1220
url: /de/net/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation class

Abstrakte Basisklasse für Textmarkup-Anmerkungen.

```csharp
public abstract class TextMarkupAnnotation : MarkupAnnotation
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ruft eine Liste mit Anmerkungsaktionen ab. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ruft den aktuellen Darstellungszustand der Anmerkung ab oder legt ihn fest. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype) { get; } | Ruft die Art der Anmerkung ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ruft das Darstellungswörterbuch der Anmerkung ab. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ruft Anmerkungsrandeigenschaften ab oder legt sie fest.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ruft Anmerkungsmerkmale ab. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ruft die Anmerkungsfarbe ab oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ruft den Anmerkungstext ab oder legt ihn fest. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Ruft Datum und Uhrzeit der Erstellung der Anmerkung ab. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flags der Anmerkung. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ruft den vollständig qualifizierten Namen der Anmerkung ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ruft die Höhe der Anmerkung ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Holt oder setzt den Fragment-Hyperlink (für PDF-Generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Ein Verweis auf die Anmerkung, auf die diese Anmerkung „antwortet“. Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist „false“.(für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ruft ab oder legt fest, dass ein Absatz inline ist. Standard ist „false“.(für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Der Standardwert ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite verbleibt. Der Standardwert ist „false“. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Liest oder setzt einen Außenrand für Absatz (für PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ruft Datum und Uhrzeit der letzten Änderung der Anmerkung ab oder legt sie fest. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ruft den Anmerkungsnamen auf der Seite ab oder legt ihn fest. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Ruft den konstanten Deckkraftwert ab oder legt ihn fest, der beim Zeichnen der Anmerkung verwendet werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ruft den Index der Seite ab, die Anmerkungen enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Popup-Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verknüpften Textes. |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints) { get; set; } | Ruft ein Array von Punkten ab oder legt es fest, das die Koordinaten von n Vierecken angibt. Jedes Viereck umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im Text, der der Anmerkung zugrunde liegt. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ruft das Anmerkungsrechteck ab oder legt es fest. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Eine Zeichenfolge, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer von InReplyTo. angegebenen angibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Ruft eine Rich-Text-Zeichenfolge ab oder legt sie fest, die im Popupfenster angezeigt wird, wenn die Anmerkung geöffnet wird. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ruft das Darstellungswörterbuch der Anmerkung ab. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Ruft Text ab, der die Beschreibung des Objekts darstellt. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ruft die Textausrichtung für Anmerkungen ab oder legt sie fest. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Liest oder setzt einen Text, der in der Titelleiste der Anmerkung angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Holt oder setzt eine vertikale Ausrichtung des Absatzes |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ruft die Breite der Anmerkung ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Diagramms angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Grafik mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept)(AnnotationSelector) | Akzeptiert Besucher zur Anmerkungsverarbeitung. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize)(Matrix) | Aktualisiert die QuadPoints gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klont diese Instanz. Virtuelle Methode. Immer null zurückgeben. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Platziert Anmerkungsinhalte direkt auf der Seite, Anmerkungsobjekt wird entfernt. |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext)() | Ruft Text unter Markup-Anmerkung als Zeichenfolge ab. |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments)() | Ruft Text unter Markup-Anmerkung als ab[`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection) . |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitendrehung berücksichtigt wird. |

### Siehe auch

* class [MarkupAnnotation](../markupannotation)
* namensraum [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
