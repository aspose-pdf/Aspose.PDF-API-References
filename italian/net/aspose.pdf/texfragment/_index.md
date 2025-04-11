---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.TeXFragment. Rappresenta un frammento TeX
type: docs
weight: 10360
url: /it/net/aspose.pdf/texfragment/
---
## Classe TeXFragment

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
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Ottiene o imposta le opzioni di caricamento TeX che saranno utilizzate per il caricamento (e il rendering) di LaTeX in questa istanza della classe. Si prega di utilizzarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di LaTeX per questa o quella istanza (ad esempio quando questa o quella istanza deve utilizzare un BasePath specifico per LaTeX importato o deve utilizzare un caricatore specifico di risorse esterne). Se il parametro è predefinito (null), verranno utilizzate le opzioni di caricamento standard di LaTeX. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. Lo ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Clona il frammento. |

### Vedi Anche

* classe [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)