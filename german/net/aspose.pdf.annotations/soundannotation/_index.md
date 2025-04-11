---
title: Class SoundAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SoundAnnotation-Klasse. Stellt eine Audioanmerkung dar, die Audio enthält, das vom Mikrofon des Computers aufgenommen oder aus einer Datei importiert wurde.
type: docs
weight: 2530
url: /de/net/aspose.pdf.annotations/soundannotation/
---
## SoundAnnotation-Klasse

Stellt eine Audioanmerkung dar, die Audio enthält, das vom Mikrofon des Computers aufgenommen oder aus einer Datei importiert wurde.

```csharp
public sealed class SoundAnnotation : MarkupAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SoundAnnotation](soundannotation/#constructor)(Seite, Rechteck, string) | Erstellt eine neue Audioanmerkung auf der angegebenen Seite. |
| [SoundAnnotation](soundannotation/#constructor_1)(Seite, Rechteck, string, SoundSampleData) | Erstellt eine neue Audioanmerkung auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Anmerkungsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Anzeigestatus der Anmerkung zurück oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/soundannotation/annotationtype/) { get; } | Gibt den Typ der Anmerkung zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Anmerkung zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Anmerkungsrahmens zurück oder legt sie fest. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Anmerkung zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Anmerkung zurück oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Anmerkung zurück oder legt ihn fest. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Gibt das Datum und die Uhrzeit zurück, zu der die Anmerkung erstellt wurde. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Anmerkung. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Anmerkung zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Anmerkung zurück oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink zurück oder legt ihn fest (für PDF-Generator). |
| [Icon](../../aspose.pdf.annotations/soundannotation/icon/) { get; set; } | Gibt ein Symbol zurück oder legt es fest, das zur Anzeige der Anmerkung verwendet werden soll. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Eine Referenz auf die Anmerkung, auf die diese Anmerkung "antwortet". Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false (für PDF-Generierung). |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder legt fest, ob ein Absatz inline ist. Standard ist false (für PDF-Generierung). |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false (für PDF-Generierung). |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false (für PDF-Generierung). |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder legt ihn fest (für PDF-Generierung). |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder legt sie fest, zu der die Anmerkung zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Anmerkung auf der Seite zurück oder legt ihn fest. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gibt den konstanten Opazitätswert zurück oder legt ihn fest, der beim Zeichnen der Anmerkung verwendet werden soll. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Anmerkung enthält. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verbundenen Textes. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Anmerkung zurück oder legt es fest. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Eine Zeichenfolge, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer durch InReplyTo angegebenen Anmerkung angibt. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gibt eine Rich-Text-Zeichenfolge zurück oder legt sie fest, die im Popup-Fenster angezeigt werden soll, wenn die Anmerkung geöffnet wird. |
| [SoundData](../../aspose.pdf.annotations/soundannotation/sounddata/) { get; } | Gibt ein Audioobjekt zurück, das den Sound definiert, der abgespielt werden soll, wenn die Anmerkung aktiviert wird. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Anmerkung zurück. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gibt den Text zurück, der die Beschreibung des Objekts darstellt. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Anmerkung zurück oder legt sie fest. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gibt einen Text zurück oder legt ihn fest, der in der Titelleiste der Anmerkung angezeigt werden soll. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Anmerkung zurück oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/soundannotation/accept/)(AnnotationSelector) | Akzeptiert ein Besucherobjekt zur Verarbeitung der Anmerkung. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Löscht den Zustand und das Zustandsmodell für die Anmerkung. Zum Beispiel wird der Überprüfungsstatus für eine Anmerkung gelöscht. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Anmerkung direkt auf der Seite, das Anmerkungsobjekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Anmerkung unter Berücksichtigung der Seitenrotation zurück. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gibt den Zustand der Anmerkung zurück. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gibt das Zustandsmodell der Anmerkung zurück. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Legt den markierten und unmarkierten Zustand für die Anmerkung fest. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Legt den Überprüfungszustand für eine Anmerkung fest. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Der Zustand wird von dem Benutzer festgelegt, der die Zielanmerkung erstellt hat. Der Wert wird aus der Titel-Eigenschaft der Zielanmerkung entnommen. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Legt den Überprüfungszustand für eine Anmerkung fest. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Überprüfungszustandsmodell gehören. Beachten Sie, dass der Zustand in anderen Textanmerkungen gespeichert ist, die Schlüssel für Zustand und Zustandsmodell haben. |

### Siehe auch

* Klasse [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)