---
title: "Classe GraphicElement"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Vector.GraphicElement. Rappresenta la classe base per l'oggetto grafico nella pagina"
type: docs
weight: 11370
url: /it/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

Rappresenta la classe base per l'oggetto grafico nella pagina.

```csharp
public abstract class GraphicElement : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento è creato. Cambia quando viene chiamato SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ottiene una collezione di operatori che rappresentano l'elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Restituisce l'attuale [`XFormPlacement`](../xformplacement/) in cui si trova l'elemento. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Ottiene o imposta la posizione nello spazio di coordinate corrente. Se [`Parent`](./parent/) non è !:null, l'elemento dispone di uno spazio di coordinate xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Restituisce il rettangolo di delimitazione del `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ottiene la pagina da cui è estratto l'elemento grafico. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Rilascia tutte le risorse utilizzate dalla classe `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere è meglio usare [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Converte l'elemento in una singola immagine SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Converte l'elemento in un singolo file immagine SVG. |

### Vedi anche

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


