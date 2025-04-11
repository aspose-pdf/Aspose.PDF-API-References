---
title: Class EmbeddedFileCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EmbeddedFileCollection class. Class representing embedded files collection
type: docs
weight: 4010
url: /it/net/aspose.pdf/embeddedfilecollection/
---
## Classe EmbeddedFileCollection

Classe che rappresenta una collezione di file incorporati.

```csharp
public class EmbeddedFileCollection : ICollection<FileSpecification>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Ottiene il numero di file incorporati nella collezione. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Ottiene il file incorporato in base al suo indice. (2 indicizzatori) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Restituisce l'elenco delle chiavi degli allegati di file. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso a questa collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add)(FileSpecification) | Aggiunge la specifica del file incorporato nella collezione. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add_1)(string, FileSpecification) | Aggiunge un file ai file incorporati con la chiave specificata. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copia un array di oggetti FileSpecification nella collezione. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete)() | Rimuove tutti i file incorporati dal documento. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete_1)(string) | Elimina il file incorporato per nome. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Elimina il file dalla collezione in base alla sua chiave nella collezione. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Restituisce il file incorporato in base al suo nome. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Restituisce l'enumeratore della collezione. |

### Vedi Anche

* classe [FileSpecification](../filespecification/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)