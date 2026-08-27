---
title: "Classe MarkupParagraph"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Text.MarkupParagraph class. Rappresenta un paragrafo"
type: docs
weight: 10810
url: /it/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

Rappresenta un paragrafo.

```csharp
public sealed class MarkupParagraph
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Elenco dei numeri di pagina su cui il paragrafo è continuato. Corrisponderà alla pagina in cui il paragrafo è iniziato se continua nella colonna successiva sulla stessa pagina. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Raccolta di oggetti [`TextFragment`](../textfragment/) non vuoti del paragrafo. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Righe del paragrafo. Ogni riga è rappresentata da un elenco di frammenti di testo. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Punti del poligono che descrive il paragrafo. Il punto di partenza è l'angolo inferiore sinistro del paragrafo. I punti successivi sono in sequenza antioraria. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Punti del poligono secondario che descrive la continuazione del paragrafo. Non sarà nullo se il paragrafo è continuato nella colonna o nella pagina successiva. Il punto di partenza è l'angolo inferiore sinistro del paragrafo. I punti successivi sono in sequenza antioraria. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Ottiene o imposta il testo del paragrafo. |

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


