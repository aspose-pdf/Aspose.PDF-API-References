---
title: Class TextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.TextAnnotation-Klasse. Stellt eine Textanmerkung dar, die eine Haftnotiz ist, die an einem Punkt im PDF-Dokument angeheftet ist.
type: docs
weight: 2650
url: /de/net/aspose.pdf.annotations/textannotation/
---
## TextAnnotation-Klasse

Stellt eine Textanmerkung dar, die eine 'Haftnotiz' ist, die an einem Punkt im PDF-Dokument angeheftet ist.

```csharp
public sealed class TextAnnotation : MarkupAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextAnnotation](textannotation/#constructor)(Document) | Konstruktor für Anmerkungen, wenn sie im Generator verwendet werden. |
| [TextAnnotation](textannotation/#constructor_1)(Page, Rectangle) | Erstellt eine neue Textanmerkung auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Anmerkungsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Anmerkung zurück oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/textannotation/annotationtype/) { get; } | Gibt den Typ der Anmerkung zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Dictionary der Anmerkung zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Anmerkungsrahmens zurück oder legt sie fest. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Anmerkung zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Anmerkung zurück oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Anmerkung zurück oder legt ihn fest. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Gibt das Datum und die Uhrzeit zurück, zu der die Anmerkung erstellt wurde. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Anmerkung. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Anmerkung zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Anmerkung zurück oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink (für den PDF-Generator) zurück oder legt ihn fest. |
| [Icon](../../aspose.pdf.annotations/textannotation/icon/) { get; set; } | Gibt ein Symbol zurück oder legt es fest, das zur Anzeige der Anmerkung verwendet werden soll. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Eine Referenz auf die Anmerkung, auf die diese Anmerkung "antwortet". Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder legt fest, ob ein Absatz inline ist. Standard ist false. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder legt ihn fest (für die PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder legt sie fest, zu der die Anmerkung zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Anmerkung auf der Seite zurück oder legt ihn fest. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gibt den konstanten Opazitätswert zurück oder legt ihn fest, der beim Zeichnen der Anmerkung verwendet werden soll. |
| [Open](../../aspose.pdf.annotations/textannotation/open/) { get; set; } | Gibt ein Flag zurück oder legt es fest, das angibt, ob die Anmerkung anfänglich geöffnet angezeigt werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Anmerkung enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verbundenen Textes. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Anmerkung zurück oder legt es fest. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Eine Zeichenfolge, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer durch InReplyTo angegebenen Anmerkung angibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gibt eine Rich-Text-Zeichenfolge zurück oder legt sie fest, die im Pop-up-Fenster angezeigt werden soll, wenn die Anmerkung geöffnet wird. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Dictionary der Anmerkung zurück. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gibt den Text zurück, der die Beschreibung des Objekts darstellt. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Anmerkung zurück oder legt sie fest. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gibt einen Text zurück oder legt ihn fest, der in der Titelleiste der Anmerkung angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Anmerkung zurück oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/textannotation/accept/)(AnnotationSelector) | Akzeptiert ein Besucherobjekt, um die Anmerkung zu verarbeiten. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textannotation/changeafterresize/)(Matrix) | Überschreibt die Definition in der Basisklasse mit einem leeren Körper. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Löscht den Zustand und das Zustandsmodell für die Anmerkung. Zum Beispiel wird der Überprüfungsstatus für eine Anmerkung gelöscht. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Anmerkung direkt auf der Seite, das Anmerkungsobjekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Anmerkung unter Berücksichtigung der Seitenrotation zurück. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gibt den Zustand der Anmerkung zurück. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gibt das Zustandsmodell der Anmerkung zurück. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Setzt den markierten und unmarkierten Zustand für die Anmerkung. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Setzt den Überprüfungszustand für eine Anmerkung. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Der Zustand wird von dem Benutzer festgelegt, der die Zielanmerkung erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielanmerkung entnommen. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Setzt den Überprüfungszustand für eine Anmerkung. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |

### Siehe auch

* Klasse [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)