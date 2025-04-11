---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.CharInfoCollection. Rappresenta una collezione di oggetti CharInfo
type: docs
weight: 10450
url: /it/net/aspose.pdf.text/charinfocollection/
---
## Classe CharInfoCollection

Rappresenta una collezione di oggetti CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Ottiene il numero di elementi oggetto [`CharInfo`](../charinfo/) effettivamente contenuti nella collezione. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Ottiene un valore che indica se la collezione è di sola lettura |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso alla collezione è sincronizzato (thread safe). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Ottiene l'elemento CharInfo all'indice specificato. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso alla collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | La collezione è di sola lettura, genera NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | La collezione è di sola lettura. Genera sempre NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Determina se la collezione contiene un valore specifico. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Copia l'intera collezione in un array unidimensionale compatibile, a partire dall'indice specificato dell'array di destinazione |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Restituisce un enumeratore per l'intera collezione. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | La collezione è di sola lettura, genera NotImplementedException. |

## Osservazioni

Fornisce accesso alle informazioni di posizionamento dei caratteri dei segmenti di testo.

## Esempi

L'esempio dimostra come iterare su tutti i caratteri e recuperare il carattere

```csharp
//open document
Document pdfDocument = new Document(inFile);
//create TextFragmentAbsorber object to collect all the text objects of the page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accept the absorber for all the pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//get the extracted text fragments
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop through the fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop through the segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop through the characters
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // print character position and rectangle info
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Vedi Anche

* classe [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)