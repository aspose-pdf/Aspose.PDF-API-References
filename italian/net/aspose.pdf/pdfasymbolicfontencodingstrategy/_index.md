---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.PdfASymbolicFontEncodingStrategy. Questa classe descrive le regole che possono essere utilizzate per ottimizzare il processo di copia dei dati di codifica nei casi in cui un font simbolico TrueType presenti più di una codifica.
type: docs
weight: 8330
url: /it/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## Classe PdfASymbolicFontEncodingStrategy

Questa classe descrive le regole che possono essere utilizzate per ottimizzare il processo di copia dei dati di codifica nei casi in cui un font simbolico TrueType abbia più di una codifica. Alcuni documenti PDF, dopo la conversione in formato PDF/A, potrebbero generare un errore "More than one encoding in symbolic TrueType font's cmap". Qual è la ragione di questo errore? Tutti i font simbolici TrueType possiedono una tabella speciale "cmap" nei loro dati interni. Questa tabella mappa i codici dei caratteri agli indici dei glifi. Inoltre, essa può contenere diverse sottotabelle di codifica che descrivono le codifiche utilizzate. Vedi informazioni avanzate sulle tabelle cmap su https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Di solito la tabella cmap contiene diverse sottotabelle di codifica, ma lo standard PDF/A richiede che o venga mantenuta una sola sottotabella di codifica per questo font nel documento PDF/A oppure debba essere presente una sottotabella di codifica (3,0) tra le sottotabelle del font. La domanda chiave qui è: quali dati devono essere prelevati dalle altre sottotabelle per essere copiati nella tabella di codifica di destinazione (3,0)? La maggior parte dei font ha tabelle cmap "ben formate" in cui ogni sottotabella di codifica è pienamente coerente con le altre. Tuttavia, alcuni font presentano tabelle cmap con collisioni, in cui ad esempio una sottotabella assegna l'indice glifo 100 per Unicode 100, mentre un'altra assegna l'indice glifo 200 per lo stesso Unicode 100. Per risolvere questi problemi è necessaria una strategia speciale. Per impostazione predefinita viene utilizzata la seguente strategia: viene cercata la sottotabella mac subtable(1,0). Se questa tabella viene trovata, ne vengono utilizzati solo i dati per popolare la tabella di destinazione (3,0). Se la sottotabella mac non viene trovata, allora tutte le sottotabelle, ad eccezione della (3,0), vengono iterate e i dati copiati nella sottotabella di destinazione (3,0). Inoltre, la mappatura di ogni coppia (unicode, indice glifo) viene copiato nella tabella di destinazione solo se essa non contiene già quell'unicode al momento della copia. Ad esempio, se la prima sottotabella assegna l'indice glifo 100 per Unicode 100 e la successiva assegna l'indice glifo 200 per lo stesso Unicode 100, verranno copiati solo i dati della prima sottotabella (unicode=100, indice glifo=100). Di conseguenza, ogni sottotabella precedente ha la precedenza su quelle successive. Le proprietà di questa classe `PdfASymbolicFontEncodingStrategy` aiutano a personalizzare il comportamento predefinito. Se la proprietà [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) di tipo [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) è impostata, la sottotabella corrispondente verrà utilizzata con precedenza rispetto alla sottotabella mac subtable(1,0). Il valore 'MacTable' dall'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) non ha senso in questo caso, in quanto punta alla stessa sottotabella mac subtable(1,0) che verrà utilizzata per impostazione predefinita. La proprietà [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) annulla tutte le priorità per ogni sottotabella. Se questa proprietà è impostata, verranno utilizzate solo le sottotabelle dichiarate nella coda, nell'ordine specificato. Se le sottotabelle dichiarate non vengono trovate, verrà utilizzata l'iterazione predefinita di tutte le sottotabelle e la strategia di copia descritta sopra. L'oggetto [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) specifica la sottotabella di codifica utilizzata. Questa sottotabella può essere impostata tramite la combinazione dei membri (PlatformID, PlatformSpecificId) oppure tramite l'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). Nel caso in cui il font non disponga della sottotabella (3,0), verrà utilizzata un'altra sottotabella per mantenere la compatibilità con PDF/A. La scelta della sottotabella da utilizzare avviene secondo le stesse regole descritte in precedenza, in modo che le proprietà [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) e [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) vengano utilizzate per determinare la sottotabella risultante; se il font non dispone nemmeno delle sottotabelle richieste, verrà utilizzata una qualsiasi sottotabella esistente.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Costruttori

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | Costruttore. Imposta la sottotabella predefinita (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | Costruttore |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | Costruttore |

## Proprietà

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | Specifica la coda delle sottotabelle di codifica da elaborare. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | Specifica la sottotabella che verrà utilizzata con precedenza rispetto alla sottotabella mac subtable(1,0). Il valore 'MacTable' dall'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) non ha senso in questo caso. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)