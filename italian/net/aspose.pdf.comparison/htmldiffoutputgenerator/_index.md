---
title: "Class HtmlDiffOutputGenerator"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. Rappresenta una classe per generare la rappresentazione html delle differenze di testo. Le interruzioni di riga eliminate sono indicate dal segno di paragrafo"
type: docs
weight: 3310
url: /it/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

Rappresenta una classe per generare la rappresentazione HTML delle differenze di testo. Le interruzioni di riga eliminate sono indicate dal segno di paragrafo.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Crea un'istanza della classe `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Crea un'istanza della classe `HtmlDiffOutputGenerator`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Ottiene e imposta la stringa in stile CSS per l'operazione Delete. Esempio: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Ottiene e imposta la stringa in stile CSS per l'operazione Equal. Esempio: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Ottiene e imposta la stringa in stile CSS per l'operazione Insert. Esempio: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Ottieni o imposta lo stile text-decoration: line-through per l'operazione delete. Il valore predefinito è `False`. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |

### Vedi anche

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


