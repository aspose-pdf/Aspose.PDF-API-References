---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.GraphicElement-Klasse. Stellt die Basisklasse für Grafikobjekte auf der Seite dar
type: docs
weight: 11180
url: /de/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement-Klasse

Stellt die Basisklasse für Grafikobjekte auf der Seite dar.

```csharp
public abstract class GraphicElement : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ruft die Grafik-Element-Matrix ab. Die Matrix wird gesetzt, wenn das Element erstellt wird. Sie ändert sich, wenn SetPosition() aufgerufen wird. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ruft eine Sammlung von Operatoren ab, die das Element darstellen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Ruft das aktuelle [`XFormPlacement`](../xformplacement/) ab, in dem sich das Element befindet. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Ruft die Position im aktuellen Koordinatenraum ab oder setzt sie. Wenn [`Parent`](./parent/) nicht !:null ist, hat das Element einen xForm-Koordinatenraum. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Ruft das umschließende Rechteck des `GraphicElement` ab. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ruft die Seite ab, von der das Grafik-Element extrahiert wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Fügt das aktuelle Element auf der Seite hinzu. Wenn viele Elemente hinzugefügt werden müssen, verwenden Sie besser [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Gibt alle Ressourcen frei, die von der `GraphicElement`-Klasse verwendet werden. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Entfernt das aktuelle Element von der Seite. Wenn viele Elemente entfernt werden müssen, verwenden Sie besser [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Konvertiert das Element in ein einzelnes SVG-Bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Konvertiert das Element in eine einzelne SVG-Bilddatei. |

### Siehe auch

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)