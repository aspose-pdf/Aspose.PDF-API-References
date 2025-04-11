---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.XFormPlacement. Rappresenta il posizionamento dell'XForm. Se l'XForm è visualizzato sulla pagina più di una volta, tutti i posizionamenti XForm associati a questo XForm avranno elementi grafici comuni ma stati grafici diversi
type: docs
weight: 11260
url: /it/net/aspose.pdf.vector/xformplacement/
---
## Classe XFormPlacement

Rappresenta il posizionamento dell'XForm. Se l'XForm è visualizzato sulla pagina più di una volta, tutti i posizionamenti XForm associati a questo XForm avranno elementi grafici comuni, ma stati grafici diversi.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Ottiene gli elementi grafici all'interno di questo XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento viene creato. Cambia quando viene chiamato SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Ottiene il nome dell'XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ottiene una collezione di operatori che rappresentano l'elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Ottiene l'attuale `XFormPlacement` in cui si trova l'elemento. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ottiene la pagina da cui è estratto l'elemento grafico. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Ottiene l'XForm associato a questo XFormPlacement. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Aggiunge l'elemento corrente sulla pagina. Se ci sono molti elementi da aggiungere, è meglio usare [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Rilascia tutte le risorse utilizzate dalla classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere, è meglio usare [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converte l'elemento in un'unica immagine SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converte l'elemento in un file immagine SVG unico. |

### Vedi Anche

* classe [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)