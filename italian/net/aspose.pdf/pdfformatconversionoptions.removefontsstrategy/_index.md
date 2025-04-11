---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: L'enumerazione `Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy` dichiara le strategie che possono essere utilizzate per ottimizzare l'uso dei font. Alcuni documenti hanno un dimensione grande dopo la conversione nel formato PDF/A. Per ridurre la dimensione del file per questi documenti è necessario definire una strategia per l'eliminazione dei font. L'enumerazione dichiara le strategie che possono essere utilizzate per ottimizzare l'uso dei font. Ogni strategia dell'enumerazione ha un significato solo quando la bandiera OptimizeFileSize è attivata.
type: docs
weight: 8400
url: /it/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## Enumerazione PdfFormatConversionOptions.RemoveFontsStrategy

Alcuni documenti hanno una grande dimensione dopo la conversione nel formato PDF/A. Per ridurre la dimensione del file per questi documenti è necessario definire una strategia di rimozione dei font. Questa enumerazione dichiara delle strategie che possono essere utilizzate per ottimizzare l'uso dei font. Ogni strategia di questa enumerazione ha senso solo quando il flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) è impostato.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Questa strategia rimuove tutti i font che hanno duplicati nel documento. Se il documento contiene un gruppo di font duplicati, solo un font di questo gruppo è incorporato nel documento. Tutti gli altri font di questo gruppo vengono rimossi dal documento, ogni font rimosso è sostituito con l'analogo già incorporato. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Questa strategia è simile a RemoveDuplicatedFonts ma rimuove non i font completamente duplicati, ma i font che sono simili tra loro e differiscono solo per il parametro "Widths". Questo parametro contiene un insieme di alcune larghezze per simboli specificati del font. Ogni valore di larghezza di questo insieme di "Widths" non è la reale larghezza del simbolo (glyph), la reale larghezza per questo simbolo è già definita nei dati binari del font. Il valore di larghezza dell'insieme di "Widths" significa la larghezza visiva per questo simbolo - la larghezza che il software di visualizzazione PDF deve impostare nella visualizzazione del simbolo invece della reale larghezza definita nel font. Più precisamente, la specifica dice: i visualizzatori Acrobat 5.0 e successivi utilizzano le larghezze dei glyph memorizzate nel dizionario del font per sovrascrivere le larghezze dei glyph nel programma del font stesso, il che migliora la coerenza della visualizzazione e della stampa del documento. Questa strategia è più efficace di RemoveDuplicatedFonts, ma l'uso di questa strategia in alcuni casi potrebbe teoricamente danneggiare la presentazione visiva del documento convertito. Questo difetto è possibile poiché le larghezze dichiarate dei font potrebbero essere diverse per lo stesso simbolo e in questo caso la larghezza di questo simbolo verrà cambiata in una nuova dopo la sostituzione del font - quando il font rimosso verrà sostituito nel documento con quello già incorporato. E se la larghezza visiva del simbolo verrà cambiata - verrà mostrata in modo errato e questa distinzione potrebbe causare difetti visivi come sovrapposizioni di testo o altri problemi. Ma il difetto visivo descritto è un caso molto raro e questa strategia riduce la dimensione del documento in modo più efficace. |
| SubsetFonts | `2` | Questa è la strategia più efficace per ridurre la dimensione del documento. Prende set di font completamente incorporati e li riduce solo ai sottoinsiemi utilizzati. Si consiglia di utilizzare questa strategia in combinazione con RemoveDuplicatedFonts o RemoveSimilarFontsWithDifferentWidths per ottenere un effetto di compressione multiplo per la dimensione del file. L'uso di tutte e tre le strategie simultaneamente non ha senso e la strategia RemoveSimilarFontsWithDifferentWidths non verrà utilizzata in questo caso. |

### Vedi Anche

* classe [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)