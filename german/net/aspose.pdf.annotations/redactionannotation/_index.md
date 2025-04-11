---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RedactionAnnotation-Klasse. Stellt die Redact-Annotation dar
type: docs
weight: 2400
url: /de/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation-Klasse

Stellt die Redact-Annotation dar.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | Konstruktor für RedactionAnnotation. Zur Verwendung im Generator. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | Konstruktor für RedactAnnotation. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Aktionsannotationen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder setzt ihn. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungswörterbuch der Annotation zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Randes der Annotation zurück oder setzt sie. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Gibt die Farbe des Randes zurück oder setzt sie, die gezeichnet wird, wenn die Reduktion nicht aktiv ist. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder setzt sie. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder setzt ihn. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Gibt das Datum und die Uhrzeit zurück, zu der die Annotation erstellt wurde. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Gibt den Standarddarstellungsstring zurück oder setzt ihn, der zur Formatierung des Textes verwendet werden soll. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Gibt die Farbe zurück oder setzt sie, um die Annotation auszufüllen. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Gibt die Schriftgröße für OverlayText zurück oder setzt sie. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder setzt sie. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragmenthyperlink zurück oder setzt ihn (für den PDF-Generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Eine Referenz auf die Annotation, auf die diese Annotation "antwortet". Beide Annotationen müssen sich auf derselben Seite des Dokuments befinden. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder setzt, ob ein Absatz inline ist. Standard ist falsch. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder setzt ihn (für die PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, zu der die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder setzt ihn. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gibt den konstanten Opazitätswert zurück oder setzt ihn, der beim Zeichnen der Annotation verwendet werden soll. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Gibt den Text zurück oder setzt ihn, der auf der Redact-Annotation gedruckt werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Annotation enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-Annotation zum Eingeben oder Bearbeiten des mit dieser Annotation verbundenen Textes. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Ein Array von 8xN-Zahlen, das die Koordinaten des Inhaltsbereichs angibt, der entfernt werden soll. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Annotation zurück oder setzt es. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Wenn wahr, wird der Overlay-Text auf der Annotation wiederholt. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Ein String, der die Beziehung (den "Antworttyp") zwischen dieser Annotation und einer durch InReplyTo angegebenen beschreibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gibt einen Rich-Text-String zurück oder setzt ihn, der im Popup-Fenster angezeigt wird, wenn die Annotation geöffnet wird. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungswörterbuch der Annotation zurück. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gibt den Text zurück, der die Beschreibung des Objekts darstellt. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Gibt zurück oder setzt die Ausrichtung des Overlay-Texts. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder setzt sie. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gibt einen Text zurück oder setzt ihn, der in der Titelleiste der Annotation angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder setzt sie. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder setzt sie. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder setzt ihn, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinung gemäß der Matrixtransformation. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Löscht den Zustand und das Zustandsmodell für die Annotation. Zum Beispiel wird der Überprüfungsstatus für eine Annotation gelöscht. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Flacht die Annotation ab, d.h. entfernt die Annotation und fügt sie hinzu |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gibt den Zustand der Annotation zurück. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gibt das Zustandsmodell der Annotation zurück. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Flacht die Annotation ab und redigiert den Seiteninhalt (d.h. entfernt Text und Bild unter der redigierten Annotation) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Setzt den markierten und unmarkierten Zustand für die Annotation. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Der Zustand wird von dem Benutzer festgelegt, der die Zielannotation erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielannotation entnommen. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |

### Siehe auch

* Klasse [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)