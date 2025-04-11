---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator. Rappresenta una classe per generare la rappresentazione markdown delle differenze di testo. A causa della sintassi markdown, non è possibile mostrare le modifiche ai caratteri di spaziatura. La selezione delle modifiche rende necessario aggiungere caratteri di spaziatura attorno alla formattazione, altrimenti il visualizzatore markdown non mostrerà correttamente il testo. Le interruzioni di riga eliminate sono indicate dal segno di paragrafo.
type: docs
weight: 3250
url: /it/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

Rappresenta una classe per generare la rappresentazione markdown delle differenze di testo. A causa della sintassi markdown, non è possibile mostrare le modifiche ai caratteri di spaziatura. La selezione delle modifiche rende necessario aggiungere caratteri di spaziatura attorno alla formattazione, altrimenti il visualizzatore markdown non mostrerà correttamente il testo. Le interruzioni di riga eliminate sono indicate dal segno di paragrafo.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | Il costruttore predefinito. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |

### See Also

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)