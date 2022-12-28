---
title: XImageCollection
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing XImage collection.
type: docs
weight: 1690
url: /python-net/aspose.pdf/ximagecollection/
---

## XImageCollection class

Class representing XImage collection.

The XImageCollection type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_synchronized|Returns true if object is synchronized.|
|sync_root|Returns synchronization object.|
|names|Gets array of image names.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets image from collection by its index.|
## Methods
| Name | Description |
| :- | :- |
|add(image)|Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size)|
|add(image)|Adds entity to the end of the collection, so entity can be accessed by the last index.|
|add(image, filter_type)|Adds entity to the end of the collection, so entity can be accessed by the last index.|
|add(image, quality)|Adds entity to the end of the collection, so entity can be accessed by the last index.|
|delete(index)|Removes index from collection by index.|
|delete(index, action)|Removes image from collection by index performing action specified by action parameter.|
|delete(name)|Removes item from collection by name.|
|delete(name, action)|Removes item from collection by name.|
|delete()|Removes index from collection by index.|
|replace(index, stream)|Replace image in collection with another image.|
|replace(index, stream, quality, is_black_and_white)|Replace image in collection with another image.|
|replace(index, stream, quality)|Replace image in collection with another image.|
|get_image_name(image)|Returns name in images list which is key of the given image.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

