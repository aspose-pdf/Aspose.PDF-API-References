---
title: ImageDeleteAction
second_title: Aspose.PDF for Java API Reference
description: Action which performed with image object when image is removed from collection.
type: docs
weight: 165
url: /java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageDeleteAction extends System.Enum
```

Action which performed with image object when image is removed from collection. If image object is removed
## Fields

| Field | Description |
| --- | --- |
| [KeepContents](#KeepContents) | Image will be removed from the collection. |
| [None](#None) | Image will be removed from the collection and from page contents, but image object will not be deleted. |
| [ForceDelete](#ForceDelete) | Image will be removed from the collection and image object will be removed from the document. |
| [Check](#Check) | Image will be removed from the collection and image object will be removed only if no other references to the image from other pages. |
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

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```


Image will be removed from the collection and image object will be removed from the document. If other references on the same object exist the document may be corrupted.

### Check {#Check}
```
public static final int Check
```


Image will be removed from the collection and image object will be removed only if no other references to the image from other pages. This may require more time in comparison with ForceDelete option.

