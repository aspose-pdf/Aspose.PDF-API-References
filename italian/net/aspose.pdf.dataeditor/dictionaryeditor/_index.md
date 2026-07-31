---
title: "Classe DictionaryEditor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.DataEditor.DictionaryEditor classe. Una classe per accedere a un albero di documenti, dizionario di documenti, dizionario di pagine, dizionario di risorse."
type: docs
weight: 3590
url: /it/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class

Una classe per accedere al dizionario ad albero di un documento (document dictionary, page dictionary, resources dictionary).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Raccolta completa di chiavi. Contiene chiavi modificabili e non modificabili. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Ottiene il numero di elementi contenuti in `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Ottiene un valore che indica se `DictionaryEditor` è di sola lettura. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Ottiene o imposta l'elemento con la chiave specificata. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Raccolta di chiavi modificabili. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Restituisce un ICollection contenente i valori nel `DictionaryEditor`. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Imposta [`ICosPdfPrimitive`](../icospdfprimitive/) al dizionario. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Imposta [`ICosPdfPrimitive`](../icospdfprimitive/) al dizionario. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Rimuove tutti gli elementi dal `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina se il `DictionaryEditor` contiene un valore specifico. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Determina se il `DictionaryEditor` contiene un elemento con la chiave specificata. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Rimuove la prima occorrenza di un oggetto specifico dal `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Rimuove l'elemento con la chiave specificata dal `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Per l'accesso a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi. |

### Vedi anche

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


