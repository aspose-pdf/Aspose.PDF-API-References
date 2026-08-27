---
title: "Classe CosPdfDictionary"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.DataEditor.CosPdfDictionary. Una classe per accedere al dizionario di un oggetto"
type: docs
weight: 3540
url: /it/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

Una classe per accedere al dizionario di un oggetto.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Crea un dizionario dalle risorse. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Raccolta completa di chiavi. Contiene chiavi modificabili e non modificabili. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Ottiene il numero di elementi contenuti nel `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Ottiene un valore che indica se il `CosPdfDictionary` è di sola lettura. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Ottiene o imposta l'elemento con la chiave specificata. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Raccolta di chiavi modificabili. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Ottiene una ICollection contenente i valori nel `CosPdfDictionary`. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Crea un dizionario vuoto che verrà allegato al documento. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Crea un dizionario vuoto che verrà allegato alla pagina. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Imposta [`ICosPdfPrimitive`](../icospdfprimitive/) al dizionario. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Imposta [`ICosPdfPrimitive`](../icospdfprimitive/) al dizionario. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Rimuove tutti gli elementi dal `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina se il `CosPdfDictionary` contiene un valore specifico. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Determina se il `CosPdfDictionary` contiene un elemento con la chiave specificata. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Rimuove la prima occorrenza di un oggetto specifico dal `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Rimuove l'elemento con la chiave specificata dal `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Prova a convertire questa istanza in [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Prova a convertire questa istanza in `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Prova a convertire questa istanza in [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Prova a convertire questa istanza in [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Prova a convertire questa istanza in [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Per l'accesso a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi. |

### Vedi anche

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


