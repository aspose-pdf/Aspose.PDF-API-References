---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph-Klasse. Stellt einen Grafikgenerator-Absatz dar
type: docs
weight: 3940
url: /de/net/aspose.pdf.drawing/graph/
---
## Graph-Klasse

Stellt einen Grafikgenerator-Absatz dar.

```csharp
public sealed class Graph : BaseParagraph
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Initialisiert eine neue Instanz der `Graph`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Ruft den Rand ab oder legt ihn fest. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Ruft ein [`GraphInfo`](./graphinfo/) Objekt ab oder legt es fest, das die Graph-Informationen wie Farbe, Linienstärke usw. angibt. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Ruft einen Float-Wert ab oder legt ihn fest, der die Höhe des Graphen angibt. Die Einheit ist Punkt. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft eine horizontale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für den PDF-Generator) ab oder legt ihn fest. |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Ruft ab oder legt fest, ob die aktuelle Position nach dem Verarbeiten des Absatzes geändert wird. (Standard ist true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob der Absatz inline ist. Standard ist false. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für die PDF-Generierung) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Ruft die linke Koordinate der Tabelle ab oder legt sie fest. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für die PDF-Generierung) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Ruft eine [`Shapes`](./shapes/) Sammlung ab oder legt sie fest, die alle Formen im Graphen angibt. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Ruft einen String-Wert ab oder legt ihn fest, der den Titel des Graphen angibt. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Ruft die obere Koordinate der Tabelle ab oder legt sie fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Ruft einen Float-Wert ab oder legt ihn fest, der die Breite des Graphen angibt. Die Einheit ist Punkt. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Klont den Graphen. |

### Siehe auch

* Klasse [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* Assembly [Aspose.PDF](../../)