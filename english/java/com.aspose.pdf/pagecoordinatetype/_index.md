---
title: PageCoordinateType
second_title: Aspose.PDF for Java API Reference
description: Describes page coordinate type.
type: docs
weight: 261
url: /java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PageCoordinateType extends System.Enum
```

Describes page coordinate type.

MediaBox = 0
CropBox = 1
## Fields

| Field | Description |
| --- | --- |
| [MediaBox](#MediaBox) | The MediaBox is used to specify the width and height of the page. |
| [CropBox](#CropBox) | The CropBox defines the region to which the page contents are to be clipped. |
### MediaBox {#MediaBox}
```
public static final int MediaBox
```


The MediaBox is used to specify the width and height of the page. For the average user, this probably equals the actual page size. The MediaBox is the largest page box in a PDF. The other page boxes can equal the size of the MediaBox but they cannot be larger.

### CropBox {#CropBox}
```
public static final int CropBox
```


The CropBox defines the region to which the page contents are to be clipped. Acrobat uses this size for screen display and printing.

