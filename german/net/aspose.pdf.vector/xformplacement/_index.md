---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement-Klasse. Stellt die Platzierung von XForm dar. Wenn die XForm mehr als einmal auf der Seite angezeigt wird, haben alle XFormPlacements, die mit dieser XForm verbunden sind, gemeinsame grafische Elemente, aber unterschiedliche grafische Zustände.
type: docs
weight: 11260
url: /de/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement-Klasse

Stellt die Platzierung von XForm dar. Wenn die XForm mehr als einmal auf der Seite angezeigt wird, haben alle XFormPlacements, die mit dieser XForm verbunden sind, gemeinsame grafische Elemente, aber unterschiedliche grafische Zustände.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Gibt die grafischen Elemente innerhalb dieser XForm zurück. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Gibt die Matrix des grafischen Elements zurück. Die Matrix wird festgelegt, wenn das Element erstellt wird. Sie ändert sich, wenn SetPosition() aufgerufen wird. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Gibt den Namen der XForm zurück. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Gibt eine Sammlung von Operatoren zurück, die das Element darstellen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Gibt das aktuelle `XFormPlacement` zurück, in dem sich das Element befindet. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Gibt die Seite zurück, von der das grafische Element extrahiert wurde. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Gibt die XForm zurück, die mit diesem XFormPlacement verbunden ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Fügt das aktuelle Element auf der Seite hinzu. Wenn es viele Elemente hinzuzufügen gibt, verwenden Sie besser [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Gibt alle Ressourcen frei, die von der [`GraphicElement`](../graphicelement/) Klasse verwendet werden. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Entfernt das aktuelle Element von der Seite. Wenn es viele Elemente zu entfernen gibt, verwenden Sie besser [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Konvertiert das Element in ein einzelnes SVG-Bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Konvertiert das Element in eine einzelne SVG-Bilddatei. |

### Siehe auch

* Klasse [GraphicElement](../graphicelement/)
* Namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../)