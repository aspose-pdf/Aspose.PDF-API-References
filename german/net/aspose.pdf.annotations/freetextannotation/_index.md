---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FreeTextAnnotation-Klasse. Stellt eine Freitextannotation dar, die Text direkt auf der Seite anzeigt. Im Gegensatz zu einer gewöhnlichen Textannotation hat eine Freitextannotation keinen offenen oder geschlossenen Zustand; anstelle in einem Popup-Fenster angezeigt zu werden, ist der Text immer sichtbar.
type: docs
weight: 1810
url: /de/net/aspose.pdf.annotations/freetextannotation/
---
## Klasse FreeTextAnnotation

Stellt eine Freitextannotation dar, die Text direkt auf der Seite anzeigt. Im Gegensatz zu einer gewöhnlichen Textannotation hat eine Freitextannotation keinen offenen oder geschlossenen Zustand; anstelle in einem Popup-Fenster angezeigt zu werden, ist der Text immer sichtbar.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Konstruktor zur Verwendung mit Generator. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Erstellt eine neue Freitextannotation auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Annotierungsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Randes der Annotation zurück oder legt sie fest. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Array von Punkten, die die Callout-Linie angeben. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder legt ihn fest. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Gibt das Datum und die Uhrzeit zurück, zu der die Annotation erstellt wurde. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Gibt den Standarddarstellungsstring zurück oder legt ihn fest, der zur Formatierung des Textes verwendet werden soll. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Objekt, das das Standarderscheinungsbild der Freitextannotation darstellt. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Gibt einen Standardstil-String zurück oder legt ihn fest. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Gibt den Linienendstil für den Endpunkt der Linie zurück oder legt ihn fest. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink zurück oder legt ihn fest (für PDF-Generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Eine Referenz auf die Annotation, auf die diese Annotation "antwortet". Beide Annotationen müssen sich auf derselben Seite des Dokuments befinden. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Gibt die Absicht der Freitextannotation zurück oder legt sie fest. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false (für PDF-Generierung). |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder legt fest, ob ein Absatz inline ist. Standard ist false (für PDF-Generierung). |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist false (für PDF-Generierung). |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false (für PDF-Generierung). |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Gibt einen Code zurück oder legt ihn fest, der die Form der Ausrichtung (Justifizierung) angibt, die zur Anzeige des Textes der Annotation verwendet werden soll. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder legt ihn fest (für PDF-Generierung). |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder legt sie fest, zu der die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder legt ihn fest. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gibt den konstanten Opazitätswert zurück oder legt ihn fest, der beim Zeichnen der Annotation verwendet werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Annotation enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Popup-Annotation zum Eingeben oder Bearbeiten des mit dieser Annotation verbundenen Textes. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Annotation zurück oder legt es fest. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Ein String, der die Beziehung (den "Antworttyp") zwischen dieser Annotation und einer durch InReplyTo angegebenen angibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gibt einen Rich-Text-String zurück oder legt ihn fest, der im Popup-Fenster angezeigt werden soll, wenn die Annotation geöffnet wird. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Winkel der Annotationrotation. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Gibt den Linienendstil für den Endpunkt der Linie zurück oder legt ihn fest. Diese Eigenschaft ist veraltet, bitte verwenden Sie EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gibt den Text zurück, der die Beschreibung des Objekts darstellt. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder legt sie fest. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Rechteck, das die numerischen Unterschiede zwischen zwei Rechtecken beschreibt: dem Rect-Eintrag der Annotation und einem Rechteck, das innerhalb dieses Rechtecks enthalten ist. Das innere Rechteck ist der Ort, an dem der Text der Annotation angezeigt werden soll. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Gibt den Stil des Textes im Erscheinungsbild zurück oder legt ihn fest. Wenn der Textstil geändert wird, wird das Erscheinungsbild des Textes aktualisiert. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gibt einen Text zurück oder legt ihn fest, der in der Titelleiste der Annotation angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Akzeptiert ein Besucherobjekt zur Verarbeitung der Annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Löscht den Zustand und das Zustandsmodell für die Annotation. Zum Beispiel wird der Überprüfungsstatus für eine Annotation gelöscht. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Annotation direkt auf der Seite, das Annotierungsobjekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gibt den Zustand der Annotation zurück. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gibt das Zustandsmodell der Annotation zurück. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Setzt den markierten und unmarkierten Zustand für die Annotation. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Der Zustand wird von dem Benutzer festgelegt, der die Zielannotation erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielannotation entnommen. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |

### Siehe auch

* Klasse [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)