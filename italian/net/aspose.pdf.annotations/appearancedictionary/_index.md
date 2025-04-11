---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary class. Annotation appearance dictionary specifying how the annotation shall be presented visually on the page
type: docs
weight: 1490
url: /it/net/aspose.pdf.annotations/appearancedictionary/
---
## Classe AppearanceDictionary

Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Ottiene il numero di elementi contenuti nel dizionario. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Ottiene un valore che indica se il dizionario ha una dimensione fissa. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Ottiene un valore che indica se il dizionario è di sola lettura. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso al dizionario è sincronizzato (thread safe). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Rappresenta una forma conveniente per ottenere i flussi di aspetto. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Ottiene le chiavi del dizionario. Se il dizionario di aspetto ha sottodizionari, allora [`Keys`](./keys/) contiene valori di stato (N&#x7C;R&#x7C;D), dove N - aspetto normale, R - aspetto rollover, D - aspetto down e stato - il nome dello stato (ad es. On, Off per le caselle di controllo). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso al dizionario. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Ottiene l'elenco dei valori del dizionario. La collezione risultante contiene l'elenco degli oggetti XForm. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Aggiunge una coppia con chiave e valore nel dizionario. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Aggiunge un modulo X per la chiave specificata. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Rimuove tutti gli elementi dal dizionario. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Controlla se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Determina se questo dizionario contiene la chiave specificata. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Copia gli elementi del dizionario in un Array, a partire da un particolare indice dell'Array. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Restituisce un oggetto IDictionaryEnumerator per il dizionario. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Rimuove la coppia chiave/valore dalla collezione. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Rimuove la chiave dal dizionario. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Tenta di trovare la chiave nel dizionario e recupera il valore se trovato. |

### Vedi Anche

* classe [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)