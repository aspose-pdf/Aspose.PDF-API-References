---
title: Class PageInformationAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.PageInformationAnnotation-Klasse. Stellt eine Seiteninformationsannotation in einem PDF-Dokument dar. Diese Annotation enthält den Dateinamen, die Seitenzahl sowie das Datum und die Uhrzeit der Erstellung der Annotation.
type: docs
weight: 2260
url: /de/net/aspose.pdf.annotations/pageinformationannotation/
---
## Klasse PageInformationAnnotation

Stellt eine Seiteninformationsannotation in einem PDF-Dokument dar. Diese Annotation enthält den Dateinamen, die Seitenzahl sowie das Datum und die Uhrzeit der Erstellung der Annotation.

```csharp
public sealed class PageInformationAnnotation : PrinterMarkAnnotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PageInformationAnnotation](pageinformationannotation/)(Page, Rectangle) | Initialisiert eine neue Instanz der `PageInformationAnnotation`-Klasse auf der angegebenen Seite an der angegebenen Position. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Aktionsannotationen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/pageinformationannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Dictionary der Annotation zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Rahmens der Annotation zurück oder legt sie fest. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder legt ihn fest. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink zurück oder legt ihn fest (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false (für PDF-Generierung). |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder legt fest, ob ein Absatz inline ist. Standard ist false (für PDF-Generierung). |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist false (für PDF-Generierung). |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false (für PDF-Generierung). |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder legt ihn fest (für PDF-Generierung). |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder legt sie fest, wann die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder legt ihn fest. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Annotation enthält. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Annotation zurück oder legt es fest. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Dictionary der Annotation zurück. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder legt sie fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pageinformationannotation/accept/)(AnnotationSelector) | Akzeptiert einen Besucher zur Verarbeitung der Annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Annotation direkt auf der Seite, das Annotierungsobjekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |

## Anmerkungen

Diese Klasse wird hauptsächlich verwendet, um Metadaten zu einer bestimmten Seite im PDF-Dokument hinzuzufügen, was nützlich sein kann, um Verfolgungs- und Referenzierungszwecke zu erfüllen. Beispielsweise kann sie verwendet werden, um Seiten während des Druckvorgangs zu kennzeichnen oder um zusätzliche Informationen über die Seite beim Anzeigen des Dokuments bereitzustellen.

### Siehe auch

* Klasse [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)