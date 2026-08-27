---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe descrive le regole che possono essere utilizzate per ottimizzare il processo di copia dei dati di codifica nei casi in cui il font simbolico TrueType abbia più di una codifica. Alcuni documenti PDF dopo."
type: docs
weight: 3690
url: /it/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Questa classe descrive le regole che possono essere utilizzate per affinare il processo di copia dei dati di codifica nei casi in cui il font simbolico TrueType abbia più di una codifica. Alcuni documenti PDF, dopo la conversione in formato PDF/A, potrebbero generare un errore "More than one encoding in symbolic TrueType font's cmap". Qual è la ragione di questo errore? Tutti i font simbolici TrueType hanno una tabella speciale "cmap" nei loro dati interni. Questa tabella mappa i codici dei caratteri agli indici dei glifi. E questa tabella può contenere diverse sotto‑tabelle di codifica che descrivono le codifiche utilizzate. Vedi informazioni avanzate sulle tabelle cmap su https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Di solito la tabella cmap contiene diverse sotto‑tabelle di codifica, ma lo standard PDF/A richiede che o venga lasciata una sola sotto‑tabella di codifica per questo font nel documento PDF/A, oppure che tra le sotto‑tabelle del font sia presente una sotto‑tabella di codifica (3,0). E la domanda chiave qui è: quali dati devono essere presi da altre sotto‑tabelle per essere copiati nella tabella di codifica di destinazione (3,0)? La maggior parte dei font ha tabelle cmap "well‑formed" in cui ogni sotto‑tabella di codifica è pienamente coerente con un'altra sotto‑tabella. Ma alcuni font hanno tabelle cmap con collisioni — dove, ad esempio, una sotto‑tabella ha l'indice di glifo 100 per Unicode 100, ma un'altra sotto‑tabella ha l'indice di glifo 200 per lo stesso Unicode 100. Per risolvere questi problemi è necessaria una strategia speciale. Per impostazione predefinita viene utilizzata la seguente strategia: si cerca la sotto‑tabella mac (1,0). Se questa tabella viene trovata, solo questi dati vengono usati per riempire la tabella di destinazione (3,0). Se la sotto‑tabella mac non viene trovata, allora tutte le sotto‑tabelle eccetto (3,0) vengono iterate e usate per copiare i dati nella sotto‑tabella di destinazione (3,0). Inoltre la mappatura per ogni unicode (unicode, indice del glifo) viene copiata nella tabella di destinazione solo se la tabella di destinazione non contiene ancora quel unicode al momento. Quindi, per esempio, se la prima sotto‑tabella ha l'indice di glifo 100 per Unicode 100, e la successiva sotto‑tabella ha l'indice di glifo 200 per lo stesso Unicode 100, verranno copiati solo i dati dalla prima sotto‑tabella (unicode=100, indice del glifo = 100). Quindi ogni sotto‑tabella precedente ha precedenza su quella successiva. Le proprietà di questa classe { PdfASymbolicFontEncodingStrategy} aiutano a regolare il comportamento predefinito. Se la proprietà {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) di tipo { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} è impostata, allora la sotto‑tabella pertinente verrà usata con precedenza rispetto alla sotto‑tabella mac (1,0). Il valore 'MacTable' dell'enumerazione {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} non ha senso in questo caso, poiché punta alla stessa sotto‑tabella mac (1,0) che verrà usata per impostazione predefinita. La proprietà {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) scarta tutte le priorità per qualsiasi sotto‑tabella. Se questa proprietà è impostata, allora solo le sotto‑tabelle della coda dichiarata verranno usate nell'ordine specificato. Se le sotto‑tabelle specificate non vengono trovate, verrà usata l'iterazione predefinita di tutte le sotto‑tabelle e la strategia di copia descritta sopra. L'oggetto { PdfASymbolicFontEncodingStrategy.QueueItem} specifica la sotto‑tabella di codifica utilizzata. Questa sotto‑tabella può essere impostata tramite una combinazione di membri (PlatformID, PlatformSpecificId) o tramite l'enumerazione { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Nel caso in cui il font non abbia una sotto‑tabella (3,0), verrà usata un'altra sotto‑tabella per mantenere la compatibilità PDF/A. La scelta della sotto‑tabella da utilizzare viene effettuata secondo le stesse regole descritte in precedenza, in modo che le proprietà {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) e {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) vengano usate per determinare la sotto‑tabella risultante, e se il font non dispone della/e sotto‑tabella/e richiesta/e, verrà utilizzata qualsiasi sotto‑tabella esistente.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Costruttore. Imposta la sotto-tabella predefinita (mac 1,0). |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Costruttore. Imposta la sotto-tabella predefinita (mac 1,0). |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Specifica la coda di sotto-tabelle di codifica da elaborare. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Specifica la sotto-tabella che sarà usata in precedenza alla sotto-tabella mac (1,0). Il valore 'MacTable' dell'enumerazione {@code QueueItem.CMapEncodingTableType} non ha senso in questo caso. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Specifica la coda di sotto-tabelle di codifica da elaborare. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Specifica la sotto-tabella che sarà usata in precedenza alla sotto-tabella mac (1,0). Il valore 'MacTable' dell'enumerazione {@code QueueItem.CMapEncodingTableType} non ha senso in questo caso. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Costruttore. Imposta la sotto-tabella predefinita (mac 1,0).

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Costruttore. Imposta la sotto-tabella predefinita (mac 1,0).

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Costruttore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| preferredEncodingTable |  | sotto-tabella di codifica che sarà usata in precedenza alla sotto-tabella mac (1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Specifica la coda di sotto-tabelle di codifica da elaborare.

**Returns:**
Coda di QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Specifica la sotto-tabella che sarà usata in precedenza alla sotto-tabella mac (1,0). Il valore 'MacTable' dell'enumerazione {@code QueueItem.CMapEncodingTableType} non ha senso in questo caso.

**Returns:**
Elemento CMapEncodingTableType @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Specifica la coda di sotto-tabelle di codifica da elaborare.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Specifica la sotto-tabella che sarà usata in precedenza alla sotto-tabella mac (1,0). Il valore 'MacTable' dell'enumerazione {@code QueueItem.CMapEncodingTableType} non ha senso in questo caso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | sottotabella di codifica preferredEncodingTable che sarà usata in precedenza alla sottotabella mac(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
