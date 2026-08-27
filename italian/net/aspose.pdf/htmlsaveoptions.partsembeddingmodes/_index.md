---
title: "Enum HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes. Questo enum elenca le possibili modalità di incorporamento dei file referenziati in HTML. Consente di controllare se i file referenziati (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate."
type: docs
weight: 5840
url: /it/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

Questo enum elenca le possibili modalità di incorporamento dei file referenziati in HTML. Consente di controllare se i file referenziati (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate.

```csharp
public enum PartsEmbeddingModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Forza l'incorporamento di tutti i file referenziati (CSS, Immagini, Font) nel markup HTML generato (cioè nell'HTML stesso). Questo approccio genera un unico file HTML, ma la dimensione totale dell'output diventa maggiore (a causa della codifica Base64 dei binari) e non tutti i browser (soprattutto i più vecchi) elaborano correttamente i binari incorporati nell'HTML. Tuttavia consente di ottenere un HTML che contiene l'intero risultato, senza file aggiuntivi. |
| EmbedCssOnly | `1` | Forza la separazione di tutti i file referenziati eccetto i CSS (Immagini e Font). Cioè i CSS saranno incorporati nell'HTML risultante, mentre tutti gli altri file referenziati (Immagini e Font) saranno trattati come parti esterne. Genera un HTML adatto a un'ampia gamma di browser. |
| NoEmbedding | `2` | Forza la separazione dei file referenziati (CSS, Immagini, Font). Questo approccio genera un insieme di file, ma la dimensione totale dell'output diventa più piccola (poiché non viene utilizzata la codifica Base64 dei binari). Inoltre, questo approccio genera un HTML adatto a un'ampia gamma di browser. |

### Vedi anche

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


