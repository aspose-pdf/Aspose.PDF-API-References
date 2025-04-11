---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.CharInfoCollection klass. Representerar en samling av CharInfo-objekt
type: docs
weight: 10450
url: /sv/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection klass

Representerar en samling av CharInfo-objekt.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Hämtar antalet [`CharInfo`](../charinfo/) objekt som faktiskt finns i samlingen. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Hämtar CharInfo-elementet vid det angivna indexet. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Samlingen är skrivskyddad, kastar NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Samlingen är skrivskyddad. Kastar alltid NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Kopierar hela samlingen till en kompatibel en-dimensionell Array, med början vid det angivna indexet i målarrayen |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Returnerar en enumerator för hela samlingen. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Samlingen är skrivskyddad, kastar NotImplementedException. |

## Kommentarer

Ger åtkomst till positionsinformation för tecken i textsegment.

## Exempel

Exemplet visar hur man itererar genom alla tecken och hämtar tecknet

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

### Se Även

* klass [CharInfo](../charinfo/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)