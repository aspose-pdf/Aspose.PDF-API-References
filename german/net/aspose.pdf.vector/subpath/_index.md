---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath-Klasse. Stellt ein Vektorgrafikobjekt auf der Seite dar. Grundsätzlich werden Vektorgrafikobjekte durch zwei Gruppen von SubPaths dargestellt. Eine von ihnen wird durch eine Menge von Linien und Kurven dargestellt. Die anderen werden als Rechtecke dargestellt und können manchmal verwechselt werden. Üblicherweise handelt es sich um einen rechteckigen Bereich, der eine Farbe hat, aber sehr oft wird dieses Rechteck am Anfang der Seite platziert und definiert den gesamten Raum der Seite in Weiß. So erhalten Sie den SubPath, aber visuell sehen Sie nur den Text auf der Seite.
type: docs
weight: 11220
url: /de/net/aspose.pdf.vector/subpath/
---
## SubPath-Klasse

Stellt ein Vektorgrafikobjekt auf der Seite dar. Grundsätzlich werden Vektorgrafikobjekte durch zwei Gruppen von SubPaths dargestellt. Eine von ihnen wird durch eine Menge von Linien und Kurven dargestellt. Die anderen werden als Rechtecke dargestellt und können manchmal verwechselt werden. Üblicherweise handelt es sich um einen rechteckigen Bereich, der eine Farbe hat, aber sehr oft wird dieses Rechteck am Anfang der Seite platziert und definiert den gesamten Raum der Seite in Weiß. So erhalten Sie den SubPath, aber visuell sehen Sie nur den Text auf der Seite.

```csharp
public sealed class SubPath : GraphicElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ruft die Matrix des grafischen Elements ab. Die Matrix wird gesetzt, wenn das Element erstellt wird. Sie ändert sich, wenn SetPosition() aufgerufen wird. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ruft eine Sammlung von Operatoren ab, die das Element darstellen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Ruft das aktuelle [`XFormPlacement`](../xformplacement/) ab, in dem sich das Element befindet. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Ruft die Position im aktuellen Koordinatenraum ab oder setzt sie. Wenn [`Parent`](../graphicelement/parent/) nicht !:null ist, hat das Element einen xForm-Koordinatenraum. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ruft die Seite ab, von der das grafische Element extrahiert wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Fügt das aktuelle Element auf der Seite hinzu. Wenn es viele Elemente hinzuzufügen gibt, verwenden Sie besser [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Gibt alle Ressourcen frei, die von der [`GraphicElement`](../graphicelement/) Klasse verwendet werden. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Entfernt das aktuelle Element von der Seite. Wenn es viele Elemente zu entfernen gibt, verwenden Sie besser [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Konvertiert das Element in ein einzelnes SVG-Bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Konvertiert das Element in eine einzelne SVG-Bilddatei. |

### Siehe auch

* Klasse [GraphicElement](../graphicelement/)
* Namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../)