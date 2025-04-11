---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files HTML FontsImages CSSes will be embedded into main HTML file or will be generated as apart binary entities
type: docs
weight: 5710
url: /it/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

Questo enum elenca i possibili modi di incorporamento dei file referenziati in HTML. Permette di controllare se i file referenziati (HTML, Fonts, Images, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate.

```csharp
public enum PartsEmbeddingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Impone di incorporare tutti i file referenziati (Css, Images, Fonts) nel markup HTML generato (cioè nell'HTML stesso). Questo approccio genera un file HTML, ma la dimensione totale dell'output diventa più grande (perché viene utilizzata la codifica Base64 dei binari) e non tutti i browser (soprattutto quelli legacy) elaborano con successo i binari incorporati nell'HTML. Ma consente di ottenere HTML che contiene l'intero risultato, senza file aggiuntivi. |
| EmbedCssOnly | `1` | Impone di mettere separati tutti i file referenziati tranne CSS (Images e Fonts). Cioè, il CSS sarà incorporato nell'HTML risultante, e tutti gli altri file referenziati (Images e Fonts) saranno elaborati come parti esterne. Genera HTML che è adatto per un ampio insieme di browser. |
| NoEmbedding | `2` | Impone di mettere separati i file referenziati (Css, Images, Fonts). Questo approccio genera un insieme di file, ma la dimensione totale dell'output diventa più piccola (perché non viene utilizzata la codifica Base64 dei binari). Inoltre, tale approccio genera HTML che è adatto per un ampio insieme di browser. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)