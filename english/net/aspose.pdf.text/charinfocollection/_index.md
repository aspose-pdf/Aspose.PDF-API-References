---
title: "CharInfoCollection Class"
linktitle: "CharInfoCollection"
articleTitle: "CharInfoCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.CharInfoCollection class. Represents CharInfo objects collection."
type: docs
weight: 60
url: "/net/aspose.pdf.text/charinfocollection/"
keywords: "CharInfoCollection, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CharInfoCollection class

Represents [CharInfo](../charinfo/) objects collection.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Examples

The example demonstrates how to iterate throught all the characters and retrieve the charact

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

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets the number of [`CharInfo`](../../aspose.pdf.text/charinfo/) object elements actually contained in the collection. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether collection is read-only |
| [IsSynchronized](./issynchronized/) { get; } | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [Item](./item/) { get; } | Gets the CharInfo element at the specified index. |
| [SyncRoot](./syncroot/) { get; } | Gets an object that can be used to synchronize access to the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(CharInfo) | Collection is read-only, throws NotImplementedException. |
| [Clear](./clear/)() | Collection is read-only. Always throws NotImplementedException. |
| [Contains](./contains/)(CharInfo) | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(CharInfo[], int) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [GetEnumerator](./getenumerator/)() | Returns an enumerator for the entire collection. |
| [Remove](./remove/)(CharInfo) | Collection is read-only, throws NotImplementedException. |

## Remarks

Provides access to positioning information of text segment characters.

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

