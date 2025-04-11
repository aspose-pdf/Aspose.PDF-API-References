---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlFragment. Rappresenta un frammento html
type: docs
weight: 5520
url: /it/net/aspose.pdf/htmlfragment/
---
## Classe HtmlFragment

Rappresenta un frammento html.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Inizializza una nuova istanza della classe HtmlFragment. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Ottiene o imposta HtmlLoadOptions che verranno utilizzate per il caricamento (e il rendering) di HTML in questa istanza della classe. Si prega di utilizzarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di HTML per questa o quella istanza (ad esempio quando questa o quella istanza deve utilizzare un BasePath specifico per l'HTML importato o deve utilizzare un caricatore specifico di risorse esterne) Se il parametro è predefinito (null), verranno utilizzate le opzioni di caricamento HTML standard. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Ottiene o imposta la rottura delle parole |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il predefinito è falso. (per la generazione pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il predefinito è falso. (per la generazione pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il predefinito è falso. (per la generazione pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il predefinito è falso. (per la generazione pdf) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Ottiene o imposta se il paragrafo ha un margine predefinito altrimenti il margine è 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Ottiene il rettangolo dell'HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Ottiene o imposta il font |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clona il frammento html. |

### Vedi Anche

* classe [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)