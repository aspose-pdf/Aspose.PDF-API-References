---
title: "XImageCollection Class"
linktitle: "XImageCollection"
articleTitle: "XImageCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XImageCollection class. Class representing XImage collection."
type: docs
weight: 3220
url: "/net/aspose.pdf/ximagecollection/"
keywords: "XImageCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XImageCollection class

Class representing [XImage](../ximage/) collection.

```csharp
public sealed class XImageCollection : IEnumerable
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Count of images in collection. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [IsSynchronized](./issynchronized/) { get; } | Returns true if object is synchronized. |
| [Item](./item/) { get; } |  |
| [Item](./item/) { get; } |  |
| [Names](./names/) { get; } | Gets array of image names. |
| [SyncRoot](./syncroot/) { get; } | Returns synchronization object. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*XImage*) | Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size). |
| [Add](./add/)(*Stream*) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(*BitmapInfo*) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(*Stream, ImageFilterType*) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(*BitmapInfo, ImageFilterType*) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(*Stream, int*) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Clear](./clear/) | Clears all items from the collection. |
| [Contains](./contains/)(*XImage*) | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(*XImage[], int*) | Copies array of images into collection. |
| [Delete](./delete/) | Deletes images from collection. |
| [Delete](./delete/)(*int*) | Removes index from collection by index. |
| [Delete](./delete/)(*string*) | Removes item from collection by name. |
| [Delete](./delete/)(*int, ImageDeleteAction*) | Removes image from collection by index performing action specified by action parameter. |
| [Delete](./delete/)(*string, ImageDeleteAction*) | Removes item from collection by name. |
| [GetEnumerator](./getenumerator/) | Returns collection enumerator. |
| [GetImageName](./getimagename/)(*XImage*) | Returns name in images list which is key of the given image. |
| [Remove](./remove/)(*XImage*) | Removes item from collection, throws NotImplementedException. |
| [Replace](./replace/)(*int, Stream*) | Replace image in collection with another image. |
| [Replace](./replace/)(*int, Stream, int*) | Replace image in collection with another image. |
| [Replace](./replace/)(*int, Stream, int, bool*) | Replace image in collection with another image. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

