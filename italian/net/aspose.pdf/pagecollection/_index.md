---
title: "Classe PageCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PageCollection. Collezione di pagine di documento PDF"
type: docs
weight: 8220
url: /it/net/aspose.pdf/pagecollection/
---
## PageCollection class

Raccolta di pagine di documento PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Restituisce il conteggio delle pagine nel documento. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Restituisce il valore che indica se la collezione è di sola lettura. Restituisce sempre false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Restituisce true se l'oggetto è sincronizzato. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Restituisce la pagina per indice. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Restituisce l'oggetto di sincronizzazione della collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Accetta l'oggetto visitor [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) che fornisce funzionalità per lavorare con le annotazioni. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Accetta l'oggetto visitor [`ImagePlacementAbsorber`](../imageplacementabsorber/) che fornisce funzionalità per lavorare con gli oggetti di posizionamento immagine. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Accetta l'oggetto visitor [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Accetta l'oggetto visitor [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni diverse, verrà selezionata la dimensione della pagina più frequente. Nel caso in cui vi siano solo due pagine diverse, verrà utilizzata la dimensione della prima pagina. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Aggiunge alla collezione tutte le pagine dall'elenco. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Aggiunge una pagina alla collezione. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Aggiunge alla collezione tutte le pagine dall'array. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Cancella la collezione di pagine. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Determina se questa istanza contiene l'oggetto. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Copia le pagine nel documento. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Elimina tutte le pagine dalla collezione. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Elimina la pagina specificata. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Elimina le pagine specificate i cui numeri sono specificati nell'array. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Rimuove tutti i campi presenti nelle pagine e ne inserisce i valori al loro posto. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Cancella i dati memorizzati nella cache |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Restituisce l'enumeratore delle pagine. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Restituisce l'indice della pagina specificata. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Inserisce una pagina vuota nella raccolta nella posizione specificata. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso in cui vi siano solo due pagine diverse, verrà utilizzata la dimensione della prima pagina. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Inserisce pagine dalla raccolta nel documento. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Inserisce una pagina nella raccolta di pagine nel punto specificato. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Inserisce le pagine dell'array nel documento. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Rimuove l'elemento specificato, genera NotSupportedException. |

### Vedi anche

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


