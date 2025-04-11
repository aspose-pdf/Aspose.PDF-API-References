---
title: Class LineAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.LineAnnotation-Klasse. Klasse, die eine Linienannotation darstellt
type: docs
weight: 1980
url: /de/net/aspose.pdf.annotations/lineannotation/
---
## Klasse LineAnnotation

Klasse, die eine Linienannotation darstellt.

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LineAnnotation](lineannotation/#constructor)(Document, Point, Point) | Konstruktor zur Verwendung mit Generator. |
| [LineAnnotation](lineannotation/#constructor_1)(Page, Rectangle, Point, Point) | Erstellt eine neue Linienannotation auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Annotatationsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder setzt ihn. |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Randes der Annotation zurück oder setzt sie. [`Border`](../annotation/border/) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset/) { get; set; } | Gibt den Versatz des Beschriftungstextes von seiner normalen Position zurück oder setzt ihn. |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition/) { get; set; } | Gibt die Position der Beschriftung der Annotation zurück oder setzt sie. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Merkmale der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder setzt sie. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder setzt ihn. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Gibt das Datum und die Uhrzeit zurück, zu der die Annotation erstellt wurde. |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending/) { get; set; } | Gibt den Endpunkt der Linie zurück oder setzt ihn. |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle/) { get; set; } | Gibt den Endstil für den Endpunkt der Linie zurück oder setzt ihn. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder setzt sie. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink (für PDF-Generator) zurück oder setzt ihn. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Eine Referenz auf die Annotation, auf die diese Annotation "antwortet". Beide Annotationen müssen sich auf derselben Seite des Dokuments befinden. |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent/) { get; set; } | Gibt die Absicht der Linienannotation zurück oder setzt sie. |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor/) { get; set; } | Gibt die Innenfarbe der Annotation zurück oder setzt sie. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder setzt, ob ein Absatz inline ist. Standard ist falsch. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für PDF-Generierung) |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline/) { get; set; } | Gibt die Länge der Führungslinie zurück oder setzt sie. |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension/) { get; set; } | Gibt die Länge der Erweiterung der Führungslinie zurück oder setzt sie. |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset/) { get; set; } | Gibt den Versatz der Führungslinie zurück oder setzt ihn. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder setzt ihn (für PDF-Generierung) |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure/) { get; set; } | Maßeinheiten, die für diese Annotation angegeben sind. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, zu der die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder setzt ihn. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gibt den konstanten Opazitätswert zurück oder setzt ihn, der beim Zeichnen der Annotation verwendet werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Annotation enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-Annotation zum Eingeben oder Bearbeiten des mit dieser Annotation verbundenen Textes. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Annotation zurück oder setzt es. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Eine Zeichenfolge, die die Beziehung (den "Antworttyp") zwischen dieser Annotation und einer durch InReplyTo angegebenen beschreibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gibt eine Rich-Text-Zeichenfolge zurück oder setzt sie, die im Pop-up-Fenster angezeigt werden soll, wenn die Annotation geöffnet wird. |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der bestimmt, ob der Inhalt als Beschriftung angezeigt werden muss. |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting/) { get; set; } | Gibt den Startpunkt der Linie zurück oder setzt ihn. |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle/) { get; set; } | Gibt den Stil des Linienanfangs für den Startpunkt der Linie zurück oder setzt ihn. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gibt den Text zurück, der die Beschreibung des Objekts darstellt. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder setzt sie. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gibt einen Text zurück oder setzt ihn, der in der Titelleiste der Annotation angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt eine vertikale Ausrichtung des Absatzes zurück oder setzt sie. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder setzt sie. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder setzt ihn, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept/)(AnnotationSelector) | Akzeptiert einen Besucher zur Annotationverarbeitung. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize/)(Matrix) | Aktualisiert die Start- und Endpunkte gemäß der Matrixtransformation. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Löscht den Zustand und das Zustandsmodell für die Annotation. Zum Beispiel wird der Überprüfungsstatus für eine Annotation gelöscht. Beachten Sie, dass der Zustand in einer anderen Textannotation gespeichert ist, die die Schlüssel state und statemodel hat. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Annotation direkt auf der Seite, das Annotation-Objekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gibt den Zustand der Annotation zurück. Beachten Sie, dass der Zustand in einer anderen Textannotation gespeichert ist, die die Schlüssel state und statemodel hat. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gibt das Zustandsmodell der Annotation zurück. Beachten Sie, dass der Zustand in einer anderen Textannotation gespeichert ist, die die Schlüssel state und statemodel hat. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Setzt den markierten und unmarkierten Zustand für die Annotation. Beachten Sie, dass der Zustand in einer anderen Textannotation gespeichert ist, die die Schlüssel state und statemodel hat. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Der Zustand wird von dem Benutzer gesetzt, der die Zielannotation erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielannotation entnommen. Beachten Sie, dass der Zustand in einer anderen Textannotation gespeichert ist, die die Schlüssel state und statemodel hat. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Beachten Sie, dass der Zustand in einer anderen Textannotation gespeichert ist, die die Schlüssel state und statemodel hat. |

### Siehe auch

* Klasse [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)