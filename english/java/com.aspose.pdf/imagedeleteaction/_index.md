---
title: ImageDeleteAction
second_title: Aspose.PDF for Java API Reference
description: Action which performed with image object when image is removed from collection. If image object is removed
type: docs
weight: 2290
url: /java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Action which performed with image object when image is removed from collection. If image object is removed

## Fields

| Field | Description |
| --- | --- |
| [Check](#Check) | Image will be removed from the collection and image object will be removed only if no other references to the image from other pages. This may require more time in comparison with ForceDelete option. |
| [ForceDelete](#ForceDelete) | Image will be removed from the collection and image object will be removed from the document. If other references on the same object exist the document may be corrupted. |
| [KeepContents](#KeepContents) | Image will be removed from the collection. If page contents contains references to the image they will not be removed. Document may became invalid. |
| [None](#None) | Image will be removed from the collection and from page contents, but image object will not be deleted. File size will not be decreased. |

### Check {#Check}
```
public static final int Check
```

Image will be removed from the collection and image object will be removed only if no other references to the image from other pages. This may require more time in comparison with ForceDelete option.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

Image will be removed from the collection and image object will be removed from the document. If other references on the same object exist the document may be corrupted.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

Image will be removed from the collection. If page contents contains references to the image they will not be removed. Document may became invalid.

### None {#None}
```
public static final int None
```

Image will be removed from the collection and from page contents, but image object will not be deleted. File size will not be decreased.
