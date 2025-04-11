---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Metadata. Fornisce accesso al flusso di metadati XMP
type: docs
weight: 6950
url: /it/net/aspose.pdf/metadata/
---
## Classe Metadata

Fornisce accesso al flusso di metadati XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Ottiene il conteggio degli elementi nella collezione. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Ottiene il dizionario dei campi di estensione. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Controlla se la collezione ha una dimensione fissa. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Controlla se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Controlla se la collezione è sincronizzata. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Ottiene o imposta i dati dai metadati. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Ottiene la collezione delle chiavi dei metadati. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Ottiene il gestore dei namespace. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Ottiene l'oggetto di sincronizzazione della collezione. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Ottiene i valori nei metadati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Aggiunge una coppia con chiave e valore nel dizionario. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Aggiunge un valore ai metadati. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Aggiunge un'estensione pdf ai metadati. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Aggiunge un valore ai metadati. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Pulisce i metadati. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Controlla se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Controlla se la chiave è contenuta nei metadati. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Determina se questo dizionario contiene la chiave specificata. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Restituisce l'enumeratore del dizionario. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Restituisce l'URI del namespace per prefisso. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Restituisce il prefisso per URI del namespace. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registra l'URI del namespace. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registra l'URI del namespace. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Rimuove la coppia chiave/valore dalla collezione. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Rimuove l'elemento dai metadati. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Tenta di trovare la chiave nel dizionario e recupera il valore se trovato. |

### Vedi Anche

* classe [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)