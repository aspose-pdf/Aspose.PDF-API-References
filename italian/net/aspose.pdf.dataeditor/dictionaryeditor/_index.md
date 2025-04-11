---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.DataEditor.DictionaryEditor. Una classe per accedere a un dizionario ad albero di documenti, dizionario di documenti, dizionario di pagine, dizionario di risorse.
type: docs
weight: 3470
url: /it/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Classe DictionaryEditor

Una classe per accedere al dizionario ad albero di un documento (dizionario di documenti, dizionario di pagine, dizionario di risorse).

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
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Collezione completa di chiavi. Contiene chiavi modificabili e non modificabili. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Ottiene il numero di elementi contenuti nel `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Ottiene un valore che indica se il `DictionaryEditor` è di sola lettura. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Ottiene o imposta l'elemento con la chiave specificata. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Collezione di chiavi modificabili. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Ottiene un ICollection contenente i valori nel `DictionaryEditor`. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Imposta [`ICosPdfPrimitive`](../icospdfprimitive/) nel dizionario. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Imposta [`ICosPdfPrimitive`](../icospdfprimitive/) nel dizionario. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Rimuove tutti gli elementi dal `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina se il `DictionaryEditor` contiene un valore specifico. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Determina se il `DictionaryEditor` contiene un elemento con la chiave specificata. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Rimuove la prima occorrenza di un oggetto specifico dal `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Rimuove l'elemento con la chiave specificata dal `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Per l'accesso a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi. |

### Vedi Anche

* interfaccia [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)