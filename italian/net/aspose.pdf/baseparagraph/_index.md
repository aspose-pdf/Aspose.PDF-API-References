---
title: Class BaseParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseParagraph class. Represents a abstract base object can be added to the pagedoc.Paragraphs.Add
type: docs
weight: 2840
url: /it/net/aspose.pdf/baseparagraph/
---
## Classe BaseParagraph

Rappresenta un oggetto base astratto che può essere aggiunto alla pagina (doc.Paragraphs.Add()).

```csharp
public abstract class BaseParagraph : ICloneable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllineamentoOrizzontale](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| virtual [CollegamentoIpertestuale](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [ÈPrimoParagrafoNellaColonna](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione di pdf) |
| [ÈParagrafoInLinea](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione di pdf) |
| [ÈInNuovaPagina](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione di pdf) |
| [ÈMantenutoConSuccessivo](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione di pdf) |
| [Margine](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| virtual [AllineamentoVerticale](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex maggiore sarà posizionato sopra il grafico con ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clona](../../aspose.pdf/baseparagraph/clone/)() | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)