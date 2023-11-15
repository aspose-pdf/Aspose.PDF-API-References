---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection class. Represents font collection
type: docs
weight: 7640
url: /net/aspose.pdf.text/fontcollection/
---
## FontCollection class

Represents font collection.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Gets the number of [`Font`](../font/) object elements actually contained in the collection. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Gets a value indicating whether collection is read-only |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Gets the font element at the specified index. (2 indexers) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Gets an object that can be used to synchronize access to the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Adds new font to font resources and returns automatically assigned name of font resource. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Determines whether the collection contains a specific value. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Checks if font exists in font collection. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Returns an enumerator for the entire collection. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Deletes specified item from collection. |

## Remarks

Font collections represented by `FontCollection` class are used in several scenarios. For example, in resources with [`Fonts`](../../aspose.pdf/resources/fonts/) property.

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

### See Also

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


