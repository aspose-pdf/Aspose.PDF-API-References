---
title: "Classe Collection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Collection. Rappresenta la classe per Collection12.3.5 Collections"
type: docs
weight: 3130
url: /it/net/aspose.pdf/collection/
---
## Collection class

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
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nome predefinito del file incorporato. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso a questa raccolta è sincronizzato (thread-safe). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Ottiene il file incorporato per indice. (2 indicizzatori) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Restituisce l'elenco delle chiavi degli allegati file. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Ottiene uno "Schema" di una collezione di Document. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Ottiene un oggetto che può essere usato per sincronizzare l'accesso a questa raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Aggiunge la specifica del file incorporato nella collezione. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Aggiunge un file ai file incorporati con la chiave specificata. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copia l'array di oggetti FileSpecification nella collezione. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Rimuove tutti i file incorporati dal Document. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Elimina il file incorporato per nome. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Elimina il file dalla collezione per la sua chiave nella collezione. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Restituisce il file incorporato per nome. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Restituisce l'enumeratore della collezione. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Ottiene una collezione di file ordinati secondo la specifica. |

### Vedi anche

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


