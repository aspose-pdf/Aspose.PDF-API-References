---
title: "Classe HtmlFragment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.HtmlFragment. Rappresenta un frammento html."
type: docs
weight: 5650
url: /it/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

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
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del paragrafo. |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Ottiene o imposta HtmlLoadOptions che verranno utilizzate per il caricamento (e il rendering) di HTML in questa istanza della classe. Si prega di usarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di HTML per questa o quella istanza (ad es. quando questa o quella istanza deve usare un BasePath specifico per l'HTML importato o deve usare un loader specifico per risorse esterne). Se il parametro è predefinito (null), verranno utilizzate le opzioni standard di caricamento HTML. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Ottiene o imposta l'interruzione delle parole. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Ottiene o imposta se il paragrafo ha margine predefinito, altrimenti il margine è 0. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Ottiene il rettangolo dell'HtmlFragment. |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Ottiene o imposta il font. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clona il frammento html. |

### Vedi anche

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


