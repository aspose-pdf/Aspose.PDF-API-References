---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Collection. Rappresenta la classe per Collection12.3.5 Collections
type: docs
weight: 3020
url: /it/net/aspose.pdf/collection/
---
## Classe Collection

Rappresenta la classe per Collection(12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Collection](collection/)() | Inizializza un nuovo oggetto Collection. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Ottiene il numero di file incorporati nella collezione. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nome del file incorporato predefinito. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Ottiene il file incorporato in base al suo indice. (2 indicizzatori) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Restituisce l'elenco delle chiavi degli allegati di file. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Ottiene uno "Schema" di una collezione di documenti. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso a questa collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Aggiunge la specifica del file incorporato nella collezione. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Aggiunge un file ai file incorporati con la chiave specificata. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copia un array di oggetti FileSpecification nella collezione. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Rimuove tutti i file incorporati dal documento. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Elimina il file incorporato per nome. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Elimina il file dalla collezione in base alla sua chiave nella collezione. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Restituisce il file incorporato in base al suo nome. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Restituisce l'enumeratore della collezione. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Ottiene una collezione di file ordinati secondo la specifica. |

### Vedi Anche

* classe [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)