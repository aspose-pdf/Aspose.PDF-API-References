---
title: "Classe SubPath"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Vector.SubPath. Rappresenta un oggetto di grafica vettoriale nella pagina. Fondamentalmente gli oggetti di grafica vettoriale sono rappresentati da due gruppi di SubPath. Uno di essi è rappresentato da un insieme di linee e curve. Gli altri sono presentati come rettangoli e a volte possono creare confusione. Di solito è un'area rettangolare che ha un colore, ma molto spesso questo rettangolo è posizionato all'inizio della pagina e definisce l'intero spazio della pagina in bianco. Quindi ottieni il SubPath ma visivamente vedi solo il testo nella pagina."
type: docs
weight: 11410
url: /it/net/aspose.pdf.vector/subpath/
---
## SubPath class

Rappresenta un oggetto di grafica vettoriale nella pagina. Fondamentalmente, gli oggetti di grafica vettoriale sono rappresentati da due gruppi di SubPath. Uno di essi è rappresentato da un insieme di linee e curve. Gli altri sono presentati come rettangoli e a volte possono creare confusione. Di solito è un'area rettangolare che ha un colore, ma molto spesso questo rettangolo è posizionato all'inizio della pagina e definisce l'intero spazio della pagina in bianco. Quindi ottieni il SubPath, ma visivamente vedi solo il testo nella pagina.

```csharp
public sealed class SubPath : GraphicElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento è creato. Cambia quando viene chiamato SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Ottiene una collezione di operatori che rappresentano l'elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Restituisce l'attuale [`XFormPlacement`](../xformplacement/) in cui si trova l'elemento. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Ottiene o imposta la posizione nello spazio di coordinate corrente. Se [`Parent`](../graphicelement/parent/) non è !:null, l'elemento dispone di uno spazio di coordinate xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Ottiene la pagina da cui è estratto l'elemento grafico. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Rilascia tutte le risorse utilizzate dalla classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere è meglio usare [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converte l'elemento in una singola immagine SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converte l'elemento in un singolo file immagine SVG. |

### Vedi anche

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


