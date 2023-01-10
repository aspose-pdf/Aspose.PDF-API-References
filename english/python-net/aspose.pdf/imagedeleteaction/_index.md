---
title: ImageDeleteAction
second_title: Aspose.PDF for Python via .NET API Reference
description: Action which performed with image object when image is removed from collection. If image object is removed
type: docs
weight: 6450
url: /python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Action which performed with image object when image is removed from collection. If image object is removed

## Members
| Member name | Description |
| :- | :- |
|KEEP_CONTENTS|Image will be removed from the collection. If page contents contains references to the image they will not be removed. Document may became invalid.|
|NONE|Image will be removed from the collection and from page contents, but image object will not be deleted. File size will not be decreased.|
|FORCE_DELETE|Image will be removed from the collection and image object will be removed from the document. If other references on the same object exist the document may be corrupted.|
|CHECK|Image will be removed from the collection and image object will be removed only if no other references to the image from other pages. This may require more time in comparision with ForceDelete option.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

