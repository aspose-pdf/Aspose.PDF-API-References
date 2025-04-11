---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.FontCollection. Rappresenta una collezione di caratteri
type: docs
weight: 10530
url: /it/net/aspose.pdf.text/fontcollection/
---
## Classe FontCollection

Rappresenta una collezione di caratteri.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Ottiene il numero di elementi oggetto [`Font`](../font/) effettivamente contenuti nella collezione. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Ottiene un valore che indica se la collezione è di sola lettura |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso alla collezione è sincronizzato (thread safe). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Ottiene l'elemento font all'indice specificato. (2 indicizzatori) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso alla collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Aggiunge un nuovo font alle risorse di font e restituisce il nome automaticamente assegnato della risorsa font. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Determina se la collezione contiene un valore specifico. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Controlla se il font esiste nella collezione di font. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Copia l'intera collezione in un array unidimensionale compatibile, a partire dall'indice specificato dell'array di destinazione |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Restituisce un enumeratore per l'intera collezione. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Elimina l'elemento specificato dalla collezione. |

## Osservazioni

Le collezioni di font rappresentate dalla classe `FontCollection` sono utilizzate in diversi scenari. Ad esempio, nelle risorse con la proprietà [`Fonts`](../../aspose.pdf/resources/fonts/).

## Esempi

L'esempio dimostra come rendere tutti i font dichiarati nella pagina come incorporati.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Vedi Anche

* classe [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)