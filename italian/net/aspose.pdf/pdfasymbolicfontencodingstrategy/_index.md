---
title: PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF per .NET API Reference
description: Questa classe descrive le regole che possono essere utilizzate per ottimizzare il processo di copia dei dati di codifica per i casi quando il font simbolico TrueType ha più di una codifica. Alcuni documenti PDF dopo la conversione in formato PDF/A potrebbero avere un errore Più di una codifica in simbolico cmap del carattere TrueType. Qual è il motivo di questo errore Tutti i caratteri simbolici TrueType hanno una tabella speciale cmap nei suoi dati interni. Questa tabella associa i codici dei caratteri agli indici dei glifi. E questa tabella potrebbe contenere diverse sottotabelle di codifica che descrivono le codifiche utilizzate. Vedi le informazioni avanzate sulle tabelle cmap su https//developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Solitamente la tabella cmap contiene diverse sottotabelle di codifica ma lo standard PDF/A richiede che una sola codifica la sottotabella 30 deve essere lasciata per questo font nel documento PDF/A. E la domanda chiave qui quali dati devono essere presi da altre sottotabelle per copiare nella tabella di codifica di destinazione 30 La maggior parte dei caratteri ha tabelle cmap ben formate in cui ogni sottotabella di codifica è completamente coerente con unaltra sottotabella. Ma alcuni font hanno tabelle cmap con collisioni dove ad esempio una sottotabella ha indice glifo 100 per unicode 100 ma unaltra sottotabella ha indice glifo 200 per lo stesso unicode 100. Per risolvere questi problemi è necessaria una strategia speciale. Per impostazione predefinita viene utilizzata la seguente strategia mac subtable10 viene cercato. Se viene trovata questa tabella solo questi dati vengono utilizzati per riempire la tabella destination 30. Se la sottotabella mac non viene trovata tutte le sottotabelle tranne 30 vengono ripetute e utilizzate per copiare i dati nella sottotabella di destinazione 30. Anche la mappatura per ogni unicodeunicode glyph index viene copiata nella tabella di destinazione solo se la tabella di destinazione non ha questo unicode al momento attuale. Quindi ad esempio se la prima sottotabella ha glyph index 100 per unicode 100 e la successiva sottotable ha glyph index 200 per lo stesso unicode 100 verranno copiati solo i dati della prima sottotabella unicode100 glyph index  100. Quindi ogni sottotabella precedente ha la precedenza sulla successiva. Proprietà di questa classePdfASymbolicFontEncodingStrategy./pdfasymbolicfontencodingstrategyaiuta a ottimizzare il comportamento predefinito. Se proprietàPreferredCmapEncodingTable./pdfasymbolicfontencodingstrategy/preferredcmapencodingtable di tipoCMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype è impostato quindi la sottotabella pertinente verrà utilizzata in precedenza rispetto alla sottotabella mac10. Valore MacTable dallenumerazione CMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype non ha senso in questo caso fa in modo che punti sulla stessa sottotabella mac 10 che verrà utilizzata per impostazione predefinita. Proprietà CmapEncodingTablesPriorityQueue./pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue elimina tutte le priorità per qualsiasi sottotabella. Se questa proprietà è impostata verranno utilizzate solo le sottotabelle dalla coda dichiarata nellordine specificato. Se le sottotabelle specificate non vengono trovate verrà utilizzata literazione predefinita di tutte le sottotabelle e la strategia di copia descritta sopra . OggettoQueueItem./pdfasymbolicfontencodingstrategy.queueitem specifica la sottotabella di codifica utilizzata. Questa sottotabella può essere impostata tramite una combinazione di membri PlatformID PlatformSpecificId o tramiteCMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype enumerazione.
type: docs
weight: 5980
url: /it/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy class

Questa classe descrive le regole che possono essere utilizzate per ottimizzare il processo di copia dei dati di codifica per i casi quando il font simbolico TrueType ha più di una codifica. Alcuni documenti PDF dopo la conversione in formato PDF/A potrebbero avere un errore "Più di una codifica in simbolico cmap del carattere TrueType". Qual è il motivo di questo errore? Tutti i caratteri simbolici TrueType hanno una tabella speciale "cmap" nei suoi dati interni. Questa tabella associa i codici dei caratteri agli indici dei glifi. E questa tabella potrebbe contenere diverse sottotabelle di codifica che descrivono le codifiche utilizzate. Vedi le informazioni avanzate sulle tabelle cmap su https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Solitamente la tabella cmap contiene diverse sottotabelle di codifica, ma lo standard PDF/A richiede che una sola codifica la sottotabella (3,0) deve essere lasciata per questo font nel documento PDF/A. E la domanda chiave qui: quali dati devono essere presi da altre sottotabelle per copiare nella tabella di codifica di destinazione (3,0)? La maggior parte dei caratteri ha tabelle cmap "ben formate" in cui ogni sottotabella di codifica è completamente coerente con un'altra sottotabella. Ma alcuni font hanno tabelle cmap con collisioni, dove ad esempio una sottotabella ha indice glifo 100 per unicode 100, ma un'altra sottotabella ha indice glifo 200 per lo stesso unicode 100. Per risolvere questi problemi è necessaria una strategia speciale. Per impostazione predefinita viene utilizzata la seguente strategia: mac subtable(1,0) viene cercato. Se viene trovata questa tabella, solo questi dati vengono utilizzati per riempire la tabella destination (3,0). Se la sottotabella mac non viene trovata, tutte le sottotabelle tranne (3,0) vengono ripetute e utilizzate per copiare i dati nella sottotabella di destinazione (3,0). Anche la mappatura per ogni unicode(unicode, glyph index) viene copiata nella tabella di destinazione solo se la tabella di destinazione non ha questo unicode al momento attuale. Quindi, ad esempio, se la prima sottotabella ha glyph index 100 per unicode 100, e la successiva sottotable ha glyph index 200 per lo stesso unicode 100, verranno copiati solo i dati della prima sottotabella (unicode=100, glyph index = 100). Quindi ogni sottotabella precedente ha la precedenza sulla successiva. Proprietà di questa classe[`PdfASymbolicFontEncodingStrategy`](../pdfasymbolicfontencodingstrategy)aiuta a ottimizzare il comportamento predefinito. Se proprietà[`PreferredCmapEncodingTable`](./preferredcmapencodingtable) di tipo[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) è impostato, quindi la sottotabella pertinente verrà utilizzata in precedenza rispetto alla sottotabella mac(1,0). Valore 'MacTable' dall'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) non ha senso in questo caso, fa in modo che punti sulla stessa sottotabella mac (1,0) che verrà utilizzata per impostazione predefinita. Proprietà [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue) elimina tutte le priorità per qualsiasi sottotabella. Se questa proprietà è impostata, verranno utilizzate solo le sottotabelle dalla coda dichiarata nell'ordine specificato. Se le sottotabelle specificate non vengono trovate, verrà utilizzata l'iterazione predefinita di tutte le sottotabelle e la strategia di copia descritta sopra . Oggetto[`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem) specifica la sottotabella di codifica utilizzata. Questa sottotabella può essere impostata tramite una combinazione di membri (PlatformID, PlatformSpecificId) o tramite[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) enumerazione.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy#constructor)() | Costruttore. Imposta la sottotabella predefinita (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy#constructor_1)(CMapEncodingTableType) | Costruttore |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy#constructor_2)(Queue&lt;QueueItem&gt;) | Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue) { get; set; } | Specifica la coda di codifica delle sottotabelle da elaborare. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable) { get; set; } | Specifica la sottotabella che verrà utilizzata in precedenza rispetto alla sottotabella mac(1,0). Valore 'MacTable' dall'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) non ha senso in questo caso. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->