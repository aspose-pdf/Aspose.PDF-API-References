---
title: "XImageCollection Class"
linktitle: "XImageCollection"
articleTitle: "XImageCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XImageCollection class. Class representing XImage collection."
type: docs
weight: 3180
url: "/net/aspose.pdf/ximagecollection/"
keywords: "XImageCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## XImageCollection class

Class representing [XImage](../ximage/) collection.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | Count of images in collection. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | Returns true if object is synchronized. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | Gets image from collection by its index. (2 indexers) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | Gets array of image names. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | Returns synchronization object. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(XImage) | Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size) |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(Stream) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(BitmapInfo) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream, ImageFilterType) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(BitmapInfo, ImageFilterType) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | Clears all items from the collection. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | Determines whether the collection contains a specific value. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | Copies array of images into collection. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)(int) | Removes index from collection by index. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int, ImageDeleteAction) | Removes image from collection by index performing action specified by action parameter. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(string) | Removes item from collection by name. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string, ImageDeleteAction) | Removes item from collection by name. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)() | Deletes images from collection. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | Returns collection enumerator. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | Returns name in images list which is key of the given image. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | Removes item from collection, throws NotImplementedException. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | Replace image in collection with another image. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int, bool) | Replace image in collection with another image. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int) | Replace image in collection with another image. |

### See Also

* class [XImage](../ximage/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

