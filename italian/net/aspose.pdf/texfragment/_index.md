---
title: "Classe TeXFragment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.TeXFragment. Rappresenta un frammento TeX"
type: docs
weight: 10540
url: /it/net/aspose.pdf/texfragment/
---
## TeXFragment class

Rappresenta un frammento TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Inizializza una nuova istanza della classe HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Inizializza una nuova istanza della classe HtmlFragment. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del paragrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Ottiene o imposta TeXLoadOptions che verranno usati per il caricamento (e il rendering) di LaTeX in questa istanza della classe. Si prega di usarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di LaTeX per questa o quella istanza (ad es. quando questa o quella istanza deve usare un BasePath specifico per LaTeX importato o deve usare un loader specifico di risorse esterne). Se il parametro è predefinito (null), verranno usate le opzioni di caricamento standard di LaTeX. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Clona il frammento. |

### Vedi anche

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


