---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Rappresenta una classe per generare la rappresentazione html delle differenze di testi. Le interruzioni di riga eliminate sono indicate dal segno di paragrafo
type: docs
weight: 3200
url: /it/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## Classe HtmlDiffOutputGenerator

Rappresenta una classe per generare la rappresentazione html delle differenze di testi. Le interruzioni di riga eliminate sono indicate dal segno di paragrafo.

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
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Ottiene e imposta la stringa di stile CSS per l'operazione di eliminazione. Esempio: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Ottiene e imposta la stringa di stile CSS per l'operazione di uguaglianza. Esempio: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Ottiene e imposta la stringa di stile CSS per l'operazione di inserimento. Esempio: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Ottiene o imposta lo stile text-decoration: line-through per l'operazione di eliminazione. Il valore predefinito è `False`. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |

### Vedi Anche

* interfaccia [IFileOutputGenerator](../ifileoutputgenerator/)
* interfaccia [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)