---
title: "Classe CharInfoCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.CharInfoCollection. Rappresenta una raccolta di oggetti CharInfo"
type: docs
weight: 10630
url: /it/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

Rappresenta la collezione di oggetti CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Ottiene il numero di elementi oggetto [`CharInfo`](../charinfo/) effettivamente contenuti nella raccolta. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso alla raccolta è sincronizzato (thread safe). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Ottiene l'elemento CharInfo all'indice specificato. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Ottiene un oggetto che può essere usato per sincronizzare l'accesso alla raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | La raccolta è di sola lettura, genera NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | La raccolta è di sola lettura. Genera sempre NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Determina se la raccolta contiene un valore specifico. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Copia l'intera raccolta in un Array monodimensionale compatibile, iniziando all'indice specificato dell'array di destinazione |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Restituisce un enumeratore per l'intera raccolta. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | La raccolta è di sola lettura, genera NotImplementedException. |

## Osservazioni

Fornisce l'accesso alle informazioni di posizionamento dei caratteri del segmento di testo.

## Esempi

L'esempio dimostra come iterare attraverso tutti i caratteri e recuperare il carattere

```csharp
//apri documento
Document pdfDocument = new Document(inFile);
//crea un oggetto TextFragmentAbsorber per raccogliere tutti gli oggetti di testo della pagina
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accetta l'assorbitore per tutte le pagine
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//ottieni i frammenti di testo estratti
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//itera attraverso i frammenti
foreach (TextFragment textFragment in textFragmentCollection)
{
    //itera attraverso i segmenti
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //itera attraverso i caratteri
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // stampa la posizione del carattere e le informazioni del rettangolo
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Vedi anche

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


