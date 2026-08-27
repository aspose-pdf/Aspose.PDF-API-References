---
title: "Classe Metadata"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Metadata. Fornisce l'accesso al flusso di metadati XMP"
type: docs
weight: 7090
url: /it/net/aspose.pdf/metadata/
---
## Metadata class

Fornisce l'accesso al flusso di metadati XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Ottiene il conteggio degli elementi nella collezione. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Ottiene il dizionario dei campi di estensione. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Verifica se la collezione ha dimensione fissa. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Verifica se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Verifica se la collezione è sincronizzata. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Ottiene o imposta i dati dai metadati. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Ottiene la collezione di chiavi dei metadati. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Ottiene il gestore dello spazio dei nomi. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Ottiene l'oggetto di sincronizzazione della collezione. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Ottiene i valori nei metadati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Aggiunge una coppia chiave-valore nel dizionario. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Aggiunge un valore ai metadati. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Aggiunge l'estensione pdf ai metadati. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Aggiunge un valore ai metadati. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Cancella i metadati. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Verifica se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Verifica se la chiave è contenuta nei metadati. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Determina se questo dizionario contiene la chiave specificata. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Restituisce l'enumeratore del dizionario. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Restituisce l'URI dello spazio dei nomi per prefisso. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Restituisce il prefisso per l'URI dello spazio dei nomi. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registra l'URI dello spazio dei nomi. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registra l'URI dello spazio dei nomi. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Rimuove la coppia chiave/valore dalla collezione. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Rimuove la voce dai metadati. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Cerca di trovare la chiave nel dizionario e recupera il valore se trovata. |

### Vedi anche

* class [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


