---
title: Class MovieAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.MovieAnnotation-Klasse. Stellt eine Filmannotation dar, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher präsentiert werden. Wenn die Annotation aktiviert wird, wird der Film abgespielt.
type: docs
weight: 2110
url: /de/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation-Klasse

Stellt eine Filmannotation dar, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher präsentiert werden. Wenn die Annotation aktiviert wird, wird der Film abgespielt.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Konstruktor zur Verwendung mit Generator. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Erstellt eine neue Tonannotation auf der angegebenen Seite. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gibt die Liste der Annotatationsaktionen zurück. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Gibt die Breite und Höhe des Begrenzungsrahmens des Films in Pixeln zurück oder legt sie fest. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Annotationsrahmens zurück oder legt sie fest. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder legt ihn fest. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Gibt eine Dateispezifikation zurück oder legt sie fest, die eine selbstbeschreibende Filmdatei identifiziert. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink zurück oder legt ihn fest (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder legt fest, ob ein Absatz inline ist. Standard ist falsch. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder legt ihn fest (für PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder legt sie fest, wann die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder legt ihn fest. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gibt den Index der Seite zurück, die die Annotation enthält. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Gibt ein Flag oder einen Stream zurück oder legt ihn fest, der angibt, ob und wie ein Posterbild, das den Film darstellt, angezeigt werden soll. Wenn wahr, wird das Posterbild aus der Filmdatei abgerufen; wenn falsch, wird kein Poster angezeigt. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gibt das Rechteck der Annotation zurück oder legt es fest. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die der Film im Uhrzeigersinn relativ zur Seite gedreht werden soll. Der Wert muss ein Vielfaches von 90 sein. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungsbild-Wörterbuch der Annotation zurück. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder legt sie fest. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Gibt den Titel der Filmannotation zurück oder legt ihn fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Absatzes zurück oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Platziert den Inhalt der Annotation direkt auf der Seite, das Annotationsobjekt wird entfernt. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |

### Siehe auch

* Klasse [Annotation](../annotation/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)