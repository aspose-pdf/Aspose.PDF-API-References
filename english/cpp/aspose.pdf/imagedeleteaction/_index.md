---
title: Aspose::Pdf::ImageDeleteAction enum
linktitle: ImageDeleteAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ImageDeleteAction enum. Action which performed with image object when image is removed from collection. If image object is removed in C++.'
type: docs
weight: 24400
url: /cpp/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enum


Action which performed with image object when image is removed from collection. If image object is removed.

```cpp
enum class ImageDeleteAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| KeepContents | 0 | [Image](../image/) will be removed from the collection. If page contents contains references to the image they will not be removed. [Document](../document/) may became invalid. |
| None | 1 | [Image](../image/) will be removed from the collection and from page contents, but image object will not be deleted. File size will not be decreased. |
| ForceDelete | 2 | [Image](../image/) will be removed from the collection and image object will be removed from the document. If other references on the same object exist the document may be corrupted. |
| Check | 3 | [Image](../image/) will be removed from the collection and image object will be removed only if no other references to the image from other pages. This may require more time in comparision with ForceDelete option. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
