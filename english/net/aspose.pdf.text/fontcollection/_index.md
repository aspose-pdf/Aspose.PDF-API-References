---
title: "FontCollection Class"
linktitle: "FontCollection"
articleTitle: "FontCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.FontCollection class. Represents font collection."
type: docs
weight: 140
url: "/net/aspose.pdf.text/fontcollection/"
keywords: "FontCollection, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FontCollection class

Represents font collection.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Examples

The example demonstrates how to make all font declared on page as embedded.

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

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets the number of [`Font`](../../aspose.pdf.text/font/) object elements actually contained in the collection. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether collection is read-only |
| [IsSynchronized](./issynchronized/) { get; } | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [Item](./item/) { get; } | Gets the font element at the specified index. (2 indexers) |
| [SyncRoot](./syncroot/) { get; } | Gets an object that can be used to synchronize access to the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(Font, out string) | Adds new font to font resources and returns automatically assigned name of font resource. |
| [Contains](./contains/)(Font) | Determines whether the collection contains a specific value. |
| [Contains](./contains/)(string) | Checks if font exists in font collection. |
| [CopyTo](./copyto/)(Font[], int) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [GetEnumerator](./getenumerator/)() | Returns an enumerator for the entire collection. |
| [Remove](./remove/)(Font) | Deletes specified item from collection. |

## Remarks

Font collections represented by [`FontCollection`](../../aspose.pdf.text/fontcollection/) class are used in several scenarios. 
 For example, in resources with `Fonts` property.

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

