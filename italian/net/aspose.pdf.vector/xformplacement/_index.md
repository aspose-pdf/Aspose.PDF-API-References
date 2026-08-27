---
title: "Classe XFormPlacement"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Vector.XFormPlacement. Rappresenta il posizionamento di XForm. Se l'XForm viene visualizzato nella pagina più di una volta, tutti gli XFormPlacement associati a questo XForm avranno elementi grafici comuni ma stati grafici diversi."
type: docs
weight: 11450
url: /it/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

Rappresenta il posizionamento di XForm. Se l'XForm viene visualizzato nella pagina più di una volta, tutti gli XformPlacements associati a questo XForm condivideranno gli stessi elementi grafici, ma avranno stati grafici diversi.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Ottiene gli elementi grafici all'interno di questo XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento è creato. Cambia quando viene chiamato SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Ottiene il nome dell'XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ottiene una collezione di operatori che rappresentano l'elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Ottiene l'attuale `XFormPlacement` in cui l'elemento è situato. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ottiene la pagina da cui è estratto l'elemento grafico. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Ottiene l'XForm associato a questo XFormPlacement. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Rilascia tutte le risorse utilizzate dalla classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere è meglio usare [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converte l'elemento in una singola immagine SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converte l'elemento in un singolo file immagine SVG. |

### Vedi anche

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


