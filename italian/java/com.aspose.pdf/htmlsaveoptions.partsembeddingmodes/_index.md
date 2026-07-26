---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa enum enumera le possibili modalità di incorporamento dei file referenziati in HTML. Consente di controllare se i file referenziati (HTML, Font, Immagini, CSS) saranno incorporati nel documento principale."
type: docs
weight: 2130
url: /it/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Questo enum enumera le possibili modalità di incorporamento dei file referenziati in HTML. Consente di controllare se i file referenziati (HTML, font, immagini, CSS) saranno incorporati nel file HTML principale o generati come entità binarie separate.

## Campi

| Campo | Descrizione |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Imponi l'incorporamento di tutti i file referenziati (Css, Immagini, Font) nel markup HTML generato (cioè nell'HTML stesso). Questo approccio genera un unico file HTML, ma la dimensione totale dell'output diventa più grande (a causa della codifica Base64 dei binari) e non tutti i browser (soprattutto i legacy) elaborano correttamente i binari incorporati nell'HTML. Tuttavia consente di ottenere un HTML che contiene l'intero risultato, senza file aggiuntivi. |
| [EmbedCssOnly](#EmbedCssOnly) | Imponi la separazione di tutti i file referenziati eccetto i CSS (Immagini e Font). Cioè i CSS saranno incorporati nell'HTML risultante, mentre tutti gli altri file referenziati (Immagini e Font) saranno trattati come parti esterne. Genera un HTML adatto a un'ampia gamma di browser. |
| [NoEmbedding](#NoEmbedding) | Imponi la separazione dei file referenziati (Css, Immagini, Font). Questo approccio genera un insieme di file, ma la dimensione totale dell'output diventa più piccola (poiché non viene utilizzata la codifica Base64 dei binari). Inoltre tale approccio genera un HTML adatto a un'ampia gamma di browser. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Imponi l'incorporamento di tutti i file referenziati (Css, Immagini, Font) nel markup HTML generato (cioè nell'HTML stesso). Questo approccio genera un unico file HTML, ma la dimensione totale dell'output diventa più grande (a causa della codifica Base64 dei binari) e non tutti i browser (soprattutto i legacy) elaborano correttamente i binari incorporati nell'HTML. Tuttavia consente di ottenere un HTML che contiene l'intero risultato, senza file aggiuntivi.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Imponi la separazione di tutti i file referenziati eccetto i CSS (Immagini e Font). Cioè i CSS saranno incorporati nell'HTML risultante, mentre tutti gli altri file referenziati (Immagini e Font) saranno trattati come parti esterne. Genera un HTML adatto a un'ampia gamma di browser.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Imponi la separazione dei file referenziati (Css, Immagini, Font). Questo approccio genera un insieme di file, ma la dimensione totale dell'output diventa più piccola (poiché non viene utilizzata la codifica Base64 dei binari). Inoltre tale approccio genera un HTML adatto a un'ampia gamma di browser.
