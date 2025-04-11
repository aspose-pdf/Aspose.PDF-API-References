---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.GraphicElement. Rappresenta la classe base per l'oggetto grafico nella pagina
type: docs
weight: 11180
url: /it/net/aspose.pdf.vector/graphicelement/
---
## Classe GraphicElement

Rappresenta la classe base per l'oggetto grafico nella pagina.

```csharp
public abstract class GraphicElement : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento viene creato. Cambia quando viene chiamato SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ottiene una collezione di operatori che rappresentano l'elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Ottiene l'attuale [`XFormPlacement`](../xformplacement/) in cui si trova l'elemento. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Ottiene o imposta la posizione nello spazio delle coordinate attuale. Se [`Parent`](./parent/) non è !:null allora l'elemento ha uno spazio delle coordinate xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Ottiene il rettangolo di delimitazione del `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ottiene la pagina da cui è estratto l'elemento grafico. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Aggiunge l'elemento corrente sulla pagina. Se ci sono molti elementi da aggiungere è meglio usare [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Rilascia tutte le risorse utilizzate dalla classe `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere è meglio usare [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Converte l'elemento in un'unica immagine SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Converte l'elemento in un file immagine SVG unico. |

### Vedi Anche

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)