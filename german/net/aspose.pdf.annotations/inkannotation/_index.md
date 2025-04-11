---
title: Class InkAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.InkAnnotation-Klasse. Stellt ein freihändiges Geschmiere dar, das aus einem oder mehreren disjunkten Pfaden besteht
type: docs
weight: 1920
url: /de/net/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation-Klasse

Stellt ein freihändiges "Geschmiere" dar, das aus einem oder mehreren disjunkten Pfaden besteht.

```csharp
public sealed class InkAnnotation : MarkupAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [InkAnnotation](inkannotation/#constructor)(Document, IList&lt;Point[]&gt;) | Konstruktor für die Ink-Annotation für den Generator. |
| [InkAnnotation](inkannotation/#constructor_1)(Page, Rectangle, IList&lt;Point[]&gt;) | Erstellt eine neue Ink-Annotation auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Annotatationsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ruft den aktuellen Erscheinungszustand der Annotation ab oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/inkannotation/annotationtype/) { get; } | Ruft den Typ der Annotation ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ruft die Eigenschaften des Rahmens der Annotation ab oder legt sie fest. [`Border`](../annotation/border/) |
| [CapStyle](../../aspose.pdf.annotations/inkannotation/capstyle/) { get; set; } | Stil der Linienenden der Ink-Annotation. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ruft die Eigenschaften der Annotation ab. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ruft die Farbe der Annotation ab oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ruft den Text der Annotation ab oder legt ihn fest. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Ruft das Datum und die Uhrzeit ab, zu der die Annotation erstellt wurde. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ruft den vollqualifizierten Namen der Annotation ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ruft die Höhe der Annotation ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für den PDF-Generator) ab oder legt ihn fest. |
| [InkList](../../aspose.pdf.annotations/inkannotation/inklist/) { get; set; } | Ruft die Liste der Gesten ab oder legt sie fest, die unabhängige Linien darstellen, die durch Point[]-Arrays repräsentiert werden. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Eine Referenz auf die Annotation, auf die diese Annotation "antwortet". Beide Annotationen müssen sich auf derselben Seite des Dokuments befinden. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für die PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ruft das Datum und die Uhrzeit ab oder legt sie fest, zu der die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ruft den Namen der Annotation auf der Seite ab oder legt ihn fest. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Ruft den konstanten Opazitätswert ab oder legt ihn fest, der beim Zeichnen der Annotation verwendet werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Ruft den Index der Seite ab, die die Annotation enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-Annotation zum Eingeben oder Bearbeiten des mit dieser Annotation verbundenen Textes. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Ruft das Rechteck der Annotation ab oder legt es fest. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Eine Zeichenfolge, die die Beziehung (den "Antworttyp") zwischen dieser Annotation und einer durch InReplyTo angegebenen beschreibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Ruft eine Rich-Text-Zeichenfolge ab oder legt sie fest, die im Pop-up-Fenster angezeigt wird, wenn die Annotation geöffnet wird. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Ruft den Text ab, der die Beschreibung des Objekts darstellt. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ruft die Textausrichtung für die Annotation ab oder legt sie fest. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Ruft einen Text ab oder legt ihn fest, der in der Titelleiste der Annotation angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ruft die Breite der Annotation ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/inkannotation/accept/)(AnnotationSelector) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/inkannotation/changeafterresize/)(Matrix) | Aktualisiert die Punkte in InkList gemäß der Matrixtransformation. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Löscht den Zustand und das Zustandsmodell für die Annotation. Zum Beispiel wird der Überprüfungsstatus für eine Annotation gelöscht. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Annotation direkt auf der Seite, das Annotation-Objekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Ruft den Zustand der Annotation ab. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Ruft das Zustandsmodell der Annotation ab. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Setzt den markierten und unmarkierten Zustand für die Annotation. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Der Zustand wird von dem Benutzer festgelegt, der die Zielannotation erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielannotation entnommen. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Setzt den Überprüfungszustand für eine Annotation. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Beachten Sie, dass der Zustand in anderen Textannotationen gespeichert ist, die Zustands- und Zustandsmodell-Schlüssel haben. |

### Siehe auch

* Klasse [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)