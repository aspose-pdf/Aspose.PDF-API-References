---
title: "Enum PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum. Alcuni documenti hanno dimensioni elevate dopo la conversione in formato PDF/A. Per ridurre le dimensioni del file per questi documenti è necessario definire una strategia di rimozione dei caratteri. Questa enumerazione dichiara le strategie che possono essere utilizzate per ottimizzare l'uso dei caratteri. Ogni strategia di questa enumerazione ha senso solo quando è impostata la flag OptimizeFileSize"
type: docs
weight: 8540
url: /it/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

Alcuni documenti hanno dimensioni elevate dopo la conversione in formato PDF/A. Per ridurre le dimensioni del file per questi documenti è necessario definire una strategia di rimozione dei caratteri. Questa enumerazione dichiara le strategie che possono essere utilizzate per ottimizzare l'uso dei caratteri. Ogni strategia di questa enumerazione ha senso solo quando è impostata la flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/).

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Questa strategia rimuove tutti i caratteri che hanno duplicati nel documento. Se il documento contiene un gruppo di caratteri duplicati, solo un carattere di questo gruppo viene incorporato nel documento. Tutti gli altri caratteri di questo gruppo vengono rimossi dal documento, ogni carattere rimosso viene sostituito con l'analogo già incorporato. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Questa strategia è simile a RemoveDuplicatedFonts ma rimuove non i caratteri completamente duplicati, bensì i caratteri che sono simili tra loro e differiscono solo per il parametro "Widths". Questo parametro contiene un insieme di larghezze per i simboli specificati del carattere. Ogni valore di larghezza di questo insieme "Widths" non è la larghezza reale del simbolo (glifo), la larghezza reale di questo simbolo è già definita nei dati binari del carattere. Il valore di larghezza dell'insieme "Widths" indica la larghezza visiva per questo simbolo – la larghezza che il software visualizzatore PDF deve impostare durante la visualizzazione del simbolo al posto della larghezza reale definita nel carattere. Più precisamente, la specifica indica: i visualizzatori Acrobat 5.0 e successivi usano le larghezze dei glifi memorizzate nel dizionario del carattere per sovrascrivere le larghezze dei glifi nel programma del carattere stesso, il che migliora la coerenza della visualizzazione e della stampa del documento. Questa strategia è più efficace di RemoveDuplicatedFonts ma l'uso di questa strategia in alcuni casi potrebbe teoricamente danneggiare la presentazione visiva del documento convertito. Questo difetto è possibile perché le larghezze dichiarate dei caratteri potrebbero differire per lo stesso simbolo e, in tal caso, la larghezza di questo simbolo verrà modificata in una nuova dopo la sostituzione del carattere – quando il carattere rimosso verrà sostituito nel documento con quello già incorporato. E se la larghezza visiva del simbolo verrà modificata – verrà mostrata in modo errato e questa differenza potrebbe causare difetti visivi come sovrapposizione del testo o altri problemi. Tuttavia il difetto visivo descritto è un caso molto raro e questa strategia riduce le dimensioni del documento in modo più efficace. |
| SubsetFonts | `2` | Questa è la strategia più efficace per ridurre le dimensioni del documento. Prende set di caratteri completamente incorporati e li riduce solo ai sottoinsiemi utilizzati. È consigliato utilizzare questa strategia in combinazione con RemoveDuplicatedFonts o RemoveSimilarFontsWithDifferentWidths per ottenere un effetto di compressione multipla delle dimensioni del file. L'uso simultaneo di tutte e tre le strategie non ha senso e la strategia RemoveSimilarFontsWithDifferentWidths non verrà utilizzata in questo caso. |

### Vedi anche

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


