---
title: "Classe FontCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.FontCollection. Rappresenta una collezione di caratteri."
type: docs
weight: 10710
url: /it/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

Rappresenta la collezione di font.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Restituisce il numero di elementi oggetto [`Font`](../font/) effettivamente contenuti nella raccolta. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso alla raccolta è sincronizzato (thread safe). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Ottiene l'elemento del carattere all'indice specificato. (2 indicizzatori) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Ottiene un oggetto che può essere usato per sincronizzare l'accesso alla raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Aggiunge un nuovo carattere alle risorse dei caratteri e restituisce il nome assegnato automaticamente alla risorsa del carattere. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Determina se la raccolta contiene un valore specifico. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Verifica se il carattere esiste nella collezione di caratteri. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Copia l'intera raccolta in un Array monodimensionale compatibile, iniziando all'indice specificato dell'array di destinazione |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Restituisce un enumeratore per l'intera raccolta. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Elimina l'elemento specificato dalla raccolta. |

## Osservazioni

Le collezioni di caratteri rappresentate dalla classe `FontCollection` sono utilizzate in diversi scenari. Ad esempio, nelle risorse con la proprietà [`Fonts`](../../aspose.pdf/resources/fonts/).

## Esempi

L'esempio dimostra come rendere tutti i caratteri dichiarati nella pagina incorporati.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// assicurati che tutti i caratteri dichiarati nelle risorse della pagina siano incorporati
// nota che se i caratteri sono dichiarati nelle risorse del modulo non sono accessibili dalle risorse della pagina
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Vedi anche

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


