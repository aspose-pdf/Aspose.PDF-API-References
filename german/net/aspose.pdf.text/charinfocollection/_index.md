---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.CharInfoCollection-Klasse. Stellt eine Sammlung von CharInfo-Objekten dar
type: docs
weight: 10450
url: /de/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection-Klasse

Stellt eine Sammlung von CharInfo-Objekten dar.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen [`CharInfo`](../charinfo/) Objektelemente zurück. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Gibt das CharInfo-Element am angegebenen Index zurück. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die Sammlung zu synchronisieren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Sammlung ist schreibgeschützt, wirft NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Sammlung ist schreibgeschützt. Wirft immer NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend am angegebenen Index des Zielarrays. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Sammlung ist schreibgeschützt, wirft NotImplementedException. |

## Bemerkungen

Bietet Zugriff auf Positionsinformationen der Zeichen von Textsegmenten.

## Beispiele

Das Beispiel zeigt, wie man durch alle Zeichen iteriert und das Zeichen abruft.

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

### Siehe auch

* Klasse [CharInfo](../charinfo/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)