---
title: Class PDF3DAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.PDF3DAnnotation-Klasse. Klasse PDF3DAnnotation. Diese Klasse kann nicht vererbt werden
type: docs
weight: 2150
url: /de/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation-Klasse

Klasse PDF3DAnnotation. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation/#constructor)(Seite, Rechteck, PDF3DArtwork) | Initialisiert eine neue Instanz der `PDF3DAnnotation`-Klasse. |
| [PDF3DAnnotation](pdf3dannotation/#constructor_1)(Seite, Rechteck, PDF3DArtwork, PDF3DActivation) | Initialisiert eine neue Instanz der `PDF3DAnnotation`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Annotationsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/pdf3dannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Annotationsrahmens zurück oder legt sie fest. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder legt sie fest. |
| [Content](../../aspose.pdf.annotations/pdf3dannotation/content/) { get; set; } | Gibt den Inhalt zurück oder legt ihn fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder legt ihn fest. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink zurück oder legt ihn fest (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch (für PDF-Generierung). |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder legt fest, ob ein Absatz inline ist. Standard ist falsch (für PDF-Generierung). |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch (für PDF-Generierung). |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch (für PDF-Generierung). |
| [LightingScheme](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme/) { get; } | Gibt das Beleuchtungsschema zurück. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder legt ihn fest (für PDF-Generierung). |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder legt sie fest, wann die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder legt ihn fest. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Annotation enthält. |
| [Pdf3DArtwork](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork/) { get; } | Gibt das 3D-Kunstwerk zurück. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Annotation zurück oder legt es fest. |
| [RenderMode](../../aspose.pdf.annotations/pdf3dannotation/rendermode/) { get; } | Gibt den Render-Modus zurück. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder legt sie fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder legt sie fest. |
| [ViewArray](../../aspose.pdf.annotations/pdf3dannotation/viewarray/) { get; } | Gibt das Ansichtsarray zurück. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pdf3dannotation/accept/)(AnnotationSelector) | Akzeptiert einen Besucher zur Verarbeitung der Annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| [ClearImagePreview](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview/)() | Löscht die Bildvorschau. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Annotation direkt auf der Seite, das Annotationsobjekt wird entfernt. |
| [GetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview/)() | Gibt die Bildvorschau zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [SetDefaultViewIndex](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex/)(int) | Legt den Index der Standardansicht fest. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview/#setimagepreview)(Stream) | Legt die Bildvorschau fest. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview/#setimagepreview_1)(string) | Legt die Bildvorschau fest. |

### Siehe auch

* Klasse [Annotation](../annotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)